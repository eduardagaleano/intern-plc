---
tags: [internacionalizacao, eua, govtech, icp, revops, bi]
status: rascunho
origem: anotações em papel "Internacionalização → pesquisa de mercado"
---

# Internacionalização Ospa Place: EUA (prefeituras)

> **Objetivo:** reduzir o risco antes de entrar de fato no mercado. A ideia é responder a três perguntas com dados: **(1) os EUA são o país certo e em quais condições?**, **(2) quais estados e municípios priorizar pelo ICP?** e **(3) o que precisamos validar com as pessoas (prefeituras e mercado imobiliário) antes de vender?**
>
> Estrutura: **Parte 1:** país (desk research) · **Parte 2:** cidades (desk research + scoring) · **Parte 3:** diagnóstico consultivo com prefeituras e profissionais do mercado imobiliário · **Parte 4:** entregáveis, RevOps e BI · **Parte 5:** dúvidas em aberto.
>
> ⚠️ Os números, leis e nomes de fornecedores citados servem como **ponto de partida para pesquisa**. Confirme cada um na fonte primária antes de usar em decisão ou apresentação.

---

## Parte 1: Estudo de mercado do país

Expande o item ① da folha (câmbio, fuso, idioma, questão jurídica, nº de cidades, grau do mercado imobiliário, maturidade em governo digital).

### 1.1 Tamanho e estrutura do mercado (o "nº de cidades?")
- [ ] **Mapear os tipos de governo local.** Os EUA têm cerca de 19 mil municípios incorporados, cerca de 3 mil condados, *townships* e *special districts* (fonte: Census of Governments). Em muitos estados, **licenciamento, zoneamento e cadastro ficam com o condado**, não com a cidade. Definir se o ICP inclui **counties** é decisão crítica.
- [ ] **Home rule vs. Dillon's rule por estado.** Isso define quanta autonomia a cidade tem para contratar tecnologia e mudar regras urbanísticas.
- [ ] **Forma de governo:** *council-manager* (quem compra de fato costuma ser o **City Manager**) vs. *mayor-council* (o prefeito tem mais peso). Isso muda a persona decisora.
- [ ] **TAM / SAM / SOM** em nº de entidades e em US$:
  - TAM: todos os governos locais com a dor que resolvemos.
  - SAM: os que cabem no ICP (porte, orçamento, maturidade digital, estados-alvo).
  - SOM: o que dá para capturar em 24–36 meses com o time e o canal disponíveis.
- [ ] **Estimar o gasto atual** das prefeituras com a categoria (licenciamento, GIS, planejamento urbano, dados imobiliários) usando orçamentos públicos e contratos de concorrentes.

### 1.2 Economia e câmbio (o "câmbio R$")
- [ ] Modelar receita em **USD** e custo em **BRL**: margem, sensibilidade a ±20% no câmbio e política de preço (preço em USD, reajuste anual, *multi-year contracts*).
- [ ] **Preço de referência local:** quanto concorrentes cobram das prefeituras. Contratos públicos são acessíveis por *public records requests* e por portais de compras.
- [ ] **Custos locais de operação:** entidade, contador, seguros, advogado, viagens, eventos e pessoal local (SDR/AE/solutions engineer).
- [ ] **Remessa e tributação Brasil ↔ EUA:** não há tratado para evitar bitributação entre os dois países. Consultar tributarista sobre estrutura (holding, transfer pricing, remessa de royalties/serviços).

### 1.3 Fuso e operação (o "fuso (p/ EXE)")
- [ ] Brasília (UTC-3, sem horário de verão) fica **1 a 2 h à frente do Eastern**, 2 a 3 h do Central, 3 a 4 h do Mountain e **4 a 5 h do Pacific**.
  - Isso favorece a costa leste e o centro do país para atendimento, CS e implantação feitos a partir do Brasil.
  - Na costa oeste, o suporte ao vivo sai da janela útil brasileira.
- [ ] Definir **SLA de suporte** e cobertura de horário que prefeitura americana espera: horário comercial local, às vezes *on-call* em implantação.

### 1.4 Idioma e localização (o "idioma → EN")
- [ ] Localizar **produto, documentação, contrato, termos de uso, material comercial e suporte** em inglês americano. Avaliar **espanhol** para estados como TX, FL, CA, NM e AZ (acessibilidade e atendimento ao cidadão).
- [ ] **Localização técnica**, não só tradução:
  - unidades imperiais (ft², acres);
  - formatos de data e moeda;
  - nomenclatura urbanística local: *zoning*, *setbacks*, *FAR*, *parcel*, *APN*, *permits*, *variance*, *conditional use*, *plat*;
  - integrações com padrões locais (Esri/ArcGIS é quase onipresente em governo local).
- [ ] Traduzir **cases brasileiros** com métricas que o comprador americano valoriza: tempo de aprovação de *permit*, *backlog*, receita de *fees*, horas de staff economizadas, satisfação do cidadão/desenvolvedor.

### 1.5 Questão jurídica, compliance e compras públicas (a "questão jurídica")
- [ ] **Entidade local:** normalmente uma *Delaware C-Corp* ou LLC, com conta bancária nos EUA, EIN e W-9. Muitas prefeituras não contratam empresa estrangeira sem isso.
- [ ] **Procurement:** cada estado e cidade tem regras próprias. Mapear:
  - **limites de compra direta** (*small purchase / sole source thresholds*), que variam muito por cidade;
  - **RFP / RFQ / RFI** e prazos típicos;
  - **contratos cooperativos / piggyback** (ex.: Sourcewell, NASPO ValuePoint, OMNIA Partners, TIPS/TAPS). Estar num contrato cooperativo encurta o ciclo de venda drasticamente;
  - **revendedores de governo** (ex.: Carahsoft, SHI, CDW-G) como veículo de contratação;
  - **"cone of silence" / blackout period:** durante uma RFP aberta, o fornecedor **não pode** falar com servidores. Isso impacta a Parte 3.
- [ ] **Segurança e certificações** que aparecem em RFPs: **SOC 2 Type II**, **GovRAMP** (antigo StateRAMP), eventualmente FedRAMP. Também hospedagem de dados **nos EUA**, questionários de segurança, *cyber insurance*.
- [ ] **Acessibilidade:** ADA Title II. A regra do DOJ de 2024 exige WCAG 2.1 AA para conteúdo web de governos locais, com prazos escalonados por população (verificar datas e status atuais). Section 508 e VPAT/ACR costumam ser pedidos em RFP.
- [ ] **Privacidade e dados:** leis estaduais (ex.: CCPA na Califórnia), *public records laws* (tudo que a prefeitura recebe pode virar público) e retenção de dados.
- [ ] **Seguros exigidos em contrato:** *general liability*, *professional liability / E&O*, *cyber*.
- [ ] **Ética e lobby:** regras de presentes/refeições para servidores e, em algumas cidades, registro de lobista para quem faz reunião com eleitos.
- [ ] **Fontes de recursos** que as prefeituras usam para comprar tecnologia:
  - orçamento geral;
  - *enterprise funds* (taxas de licenciamento costumam financiar o próprio departamento de *building/permits*);
  - *grants* federais e estaduais (HUD, programas de habitação, infraestrutura). Mapear quais estão ativos em 2026–2027. O ARPA já está no fim do ciclo.

### 1.6 Grau do mercado imobiliário
- [ ] **Déficit habitacional e pressão por produção:** métricas nacionais e por estado (Census Building Permits Survey, HUD, NAR, Zillow/Redfin research).
- [ ] **Leis estaduais de habitação e reforma de zoneamento** que *forçam* as cidades a agir. Isso é gatilho de compra. Exemplos a verificar: Califórnia (RHNA / Housing Element, leis de *streamlining*), Flórida (Live Local Act), Washington (middle housing), Oregon, Montana, Texas, Colorado, Arizona.
- [ ] **Ciclo do mercado:** juros, volume de lançamentos, *permits* emitidos, tempo médio de aprovação e *backlogs* noticiados.
- [ ] **Quem são os agentes:** *developers*, *homebuilders*, *brokers/realtors*, *title companies*, *land use attorneys*, *permit expediters*, associações (*Home Builders Association*, *Board of Realtors*, NAIOP, ULI).

### 1.7 Maturidade em governo digital
- [ ] **Benchmarks:** Center for Digital Government (*Digital Cities Survey*), certificação *What Works Cities* (Bloomberg Philanthropies), existência de CIO/CDO/*innovation office*, portais de dados abertos (Socrata/Tyler, ArcGIS Hub).
- [ ] **Stack típica** que vamos encontrar e com a qual teremos de integrar ou competir. Validar nomes e participação:
  - licenciamento e *permitting*: Accela, Tyler (EnerGov), CentralSquare, OpenGov, Clariti, Cloudpermit, iWorQ, CityView, entre outros;
  - GIS: Esri;
  - dados de parcelas e zoneamento: Regrid, Zoneomics, Gridics, UrbanFootprint, entre outros.
- [ ] **Mapa competitivo:** para cada concorrente, levantar posicionamento, preço (via contratos públicos), clientes, pontos fracos (reviews, notícias de implantações falhas) e onde a Ospa se diferencia.

### 1.8 Decisão de país (o "USA / Europa?")
- [ ] Mesmo com foco nos EUA, fazer um **scorecard comparativo leve** com 2 ou 3 alternativas (ex.: Canadá, México/LatAm hispânica, Portugal/Espanha) usando os mesmos critérios. Isso documenta o *porquê* dos EUA e deixa um plano B.
- [ ] Critérios sugeridos, com peso a definir:
  - tamanho do SAM;
  - facilidade de compra pública;
  - barreira regulatória;
  - fuso;
  - idioma;
  - intensidade competitiva;
  - ticket médio;
  - aderência do produto sem grandes adaptações.

---

## Parte 2: Estudo das cidades e priorização pelo ICP

Expande o item ② da folha (nº populacional, capacidade orçamentária, maturidade de dados, capacidade do mercado imobiliário, maturidade de governo digital, perfil da economia).

### 2.1 Primeiro: escolher estados-cabeça-de-ponte (beachhead)
Prospectar cidade por cidade no país inteiro dilui o esforço. Benchmark comum em govtech: **concentrar em 1 a 3 estados**. Motivos:
- governos locais se referenciam muito entre vizinhos, via associações estaduais de municípios e capítulos estaduais da APA/ICMA;
- as regras de compra se repetem dentro do estado;
- dá para cobrir eventos e visitas com um único deslocamento.

Critérios para ranquear **estados**:
- [ ] Pressão legal por habitação ou agilidade de licenciamento (gatilho de compra).
- [ ] Nº de cidades que caem no ICP.
- [ ] Crescimento populacional e volume de *permits*.
- [ ] Fuso (preferência por ET/CT).
- [ ] Presença de contrato cooperativo acessível e regras de compra amigáveis.
- [ ] Comunidade hispânica, se o espanhol for vantagem, ou conexão Brasil (ex.: Flórida).
- [ ] Densidade de concorrentes e satisfação com eles.

### 2.2 Modelo de scoring de municípios (ICP Fit Score)
Montar uma base (planilha ou BI) com **uma linha por município** dos estados escolhidos e calcular um score de 0 a 100. Pesos são sugestão inicial e devem ser calibrados depois das entrevistas da Parte 3.

| Dimensão (da sua folha) | Indicadores sugeridos | Fontes | Peso sugerido |
|---|---|---|---|
| **Nº populacional** | População, crescimento em 5 e 10 anos, faixa do ICP (ex.: 50 mil a 500 mil) | US Census (Decennial, ACS, Population Estimates) | 15% |
| **Capacidade orçamentária** | Orçamento anual, orçamento de TI, receita de *permit fees*, rating de crédito, saúde fiscal, **início do ano fiscal** | Budget book e ACFR da cidade, Census Annual Survey of State & Local Government Finances | 20% |
| **Maturidade de dados** | Portal de dados abertos, ArcGIS Hub, dados de *parcels* e *zoning* publicados, existência de GIS team / CDO | Sites das cidades, Socrata/ArcGIS Hub, What Works Cities | 15% |
| **Capacidade do mercado imobiliário** | *Permits* emitidos por ano (res/comercial), valor de construção, preço mediano e valorização, estoque, *backlog* de aprovação | Census Building Permits Survey, Zillow/Redfin data, relatórios da própria cidade | 20% |
| **Maturidade de governo digital** | Serviços online, sistema de *permitting* atual (e ano do contrato), Digital Cities ranking, cargo de CIO/Innovation | CDG, sites, contratos públicos | 15% |
| **Perfil da economia** | Setores dominantes, renda mediana, emprego, investimento privado anunciado, polos de crescimento | BLS, BEA, ACS, EDC local | 5% |
| **Timing / gatilho de compra** | Contrato do sistema atual vencendo, RFP/RFI recente, novo *City Manager* ou CIO, plano diretor (*comprehensive plan*) ou revisão de zoneamento em curso, reclamações públicas de lentidão | Portais de compras (BidNet, DemandStar, OpenGov Procurement, Periscope/GovSpend), atas de *council meetings*, notícias locais | 10% |

Complementos ao score:
- [ ] **Fit negativo / desqualificadores:** contrato recente (< 2 anos) com concorrente enterprise, congelamento orçamentário, licenciamento feito pelo condado, população fora da faixa.
- [ ] **Tiering:** **Tier A** (top 20 a 30 contas para ABM 1:1), **Tier B** (ABM 1:few, por cluster/estado), **Tier C** (nurturing 1:many).
- [ ] **Clusters:** agrupar cidades próximas (mesma região metropolitana ou condado) para otimizar visitas e gerar efeito de referência.
- [ ] **Account mapping** nas contas Tier A:
  - nomes e cargos do comitê de compra: City Manager, Planning Director, Building Official, IT Director/CIO, Finance/Procurement, membro do *council* engajado em habitação;
  - LinkedIn de cada pessoa;
  - atas e vídeos de *council meetings* onde o tema aparece.
- [ ] **Calendário orçamentário** de cada conta Tier A. A maioria das cidades tem ano fiscal de **1º de julho a 30 de junho**, mas há outros calendários. A proposta precisa entrar **antes** da montagem do orçamento, geralmente vários meses antes do início do ano fiscal.

### 2.3 Hipóteses a registrar antes de ir a campo
Escrever explicitamente o que acreditamos, para as entrevistas confirmarem ou derrubarem:
1. A dor principal é ______ (ex.: tempo de aprovação de projetos, falta de dados territoriais integrados, receita não capturada).
2. O comprador econômico é ______ e o usuário principal é ______.
3. O orçamento sai de ______ (fundo geral, *enterprise fund* de *permits*, *grant*).
4. O ciclo de venda esperado é de ___ meses e o caminho de compra é ______ (compra direta abaixo do limite, cooperativo, RFP).
5. O ticket anual viável é de US$ ___.
6. O diferencial percebido vs. a stack atual é ______.

---

## Parte 3: Diagnóstico consultivo com prefeituras e mercado imobiliário

### 3.1 Formato e boas práticas
- **Objetivo:** fazer entrevista de descoberta, não demo. Vendas consultivas começam com diagnóstico: entender a dor, quantificar e mapear o processo de decisão.
- **Amostra sugerida:** 15 a 25 entrevistas com prefeituras (misturando Tier A e B e cargos diferentes) e 10 a 15 com mercado imobiliário, nos 1 a 3 estados escolhidos.
- **Canais para conseguir as conversas:**
  - associações estaduais de municípios (*state municipal leagues*), ICMA, NLC, capítulos estaduais da APA e do ICC;
  - Home Builders Associations e Boards of Realtors;
  - eventos: APA National Planning Conference, ICMA Annual Conference, NLC City Summit, Esri User Conference, eventos estaduais;
  - câmaras de comércio Brasil–EUA e ApexBrasil.
- **Regras:**
  - checar se a conta tem **RFP aberta** (*cone of silence*: nesse caso, não contatar);
  - respeitar regras de presentes e refeições;
  - enviar pauta antecipada;
  - pedir permissão para gravar;
  - mandar resumo por escrito depois.
- **Padronizar o registro no CRM:** mesmo roteiro, mesmos campos e uma nota de 1 a 5 por dimensão (ver 3.5). Isso transforma entrevista qualitativa em dado comparável.

### 3.2 Roteiro com prefeituras, por dimensão da sua folha

**Contexto e prioridades (abertura)**
1. Quais são as 3 prioridades da cidade para os próximos 12 a 24 meses? Onde habitação, desenvolvimento e licenciamento aparecem nisso?
2. Existe meta, mandato estadual ou pressão política (*council*, eleição, imprensa) ligada a habitação ou tempo de aprovação?
3. Como a cidade vai estar crescendo daqui a 5 anos? Onde estão os vetores de crescimento?

**Processo atual e dor (maturidade de governo digital)**
4. Descreva a jornada de um projeto, da consulta de viabilidade ou zoneamento até o *permit* emitido. Quantas etapas, departamentos e sistemas estão envolvidos?
5. Qual é o **tempo médio de aprovação** hoje e qual seria o aceitável? Existe *backlog*? Quantos processos?
6. Quais tarefas consomem mais horas do staff? Quantas pessoas trabalham nisso? Há vagas não preenchidas?
7. Quais sistemas vocês usam hoje (*permitting*, GIS, ERP, portal do cidadão)? **Quando vence o contrato?** O que funciona e o que não funciona?
8. Qual parte já é 100% digital para o requerente? O que ainda é papel, PDF ou e-mail?

**Dados (maturidade de dados)**
9. Onde vivem os dados de parcelas, zoneamento, uso do solo e *permits*? Quem mantém? Com que frequência são atualizados?
10. Há equipe de GIS ou dados? Que ferramentas usam (ArcGIS, dados abertos, BI)?
11. Que decisões vocês gostariam de tomar com dados e hoje não conseguem? (ex.: capacidade de adensamento, impacto de mudança de zoneamento, previsão de receita)
12. Que restrições existem para compartilhar ou integrar dados com um fornecedor externo: segurança, privacidade, *public records*?

**Orçamento e compra (capacidade orçamentária)**
13. Quando começa o ano fiscal e quando começa a montagem do orçamento do próximo ciclo?
14. Iniciativas como essa são pagas com qual fonte (fundo geral, taxas de *permit*, *grant*)? Existe verba já aprovada para modernização?
15. Qual é o limite para compra direta? Vocês usam contratos cooperativos? Quais?
16. Quem participa da decisão (técnico, TI, financeiro, *City Manager*, *council*) e em que ordem? Quem pode vetar?
17. O que um fornecedor novo, e estrangeiro, precisa apresentar para ser considerado (certificações, seguros, referências nos EUA, entidade local)?
18. Qual foi a última compra de tecnologia parecida? Como foi o processo e quanto tempo levou?

**Mercado imobiliário local (visão da prefeitura)**
19. Como está a relação com incorporadores e construtores? Quais são as principais reclamações deles?
20. Há iniciativas para atrair investimento (*opportunity zones*, incentivos, *fast-track* para habitação acessível)?

**Valor e sucesso**
21. Se em 12 meses esse problema estivesse resolvido, o que teria mudado? Como vocês mediriam (KPIs)?
22. Quanto custa, em horas, receita perdida ou desgaste político, não resolver?
23. Vocês topariam um **piloto** ou *design partnership*? Em que condições (escopo, prazo, custo, critério de sucesso)?
24. Quem mais, nesta cidade ou em cidades vizinhas, deveríamos ouvir?

### 3.3 Roteiro com profissionais do mercado imobiliário
Incorporadores, *homebuilders*, *brokers*, arquitetos, *permit expediters*, *land use attorneys*, associações.

**Dor com o poder público**
1. Quanto tempo leva, em média, para aprovar um projeto nesta cidade? E nas vizinhas? Quais cidades são referência positiva e quais são negativas?
2. Onde o processo trava: zoneamento, análise técnica, idas e vindas de correções, falta de informação clara?
3. Quanto custa um mês de atraso num empreendimento típico (juros, *carrying cost*, perda de janela de mercado)?

**Uso de dados**
4. Como vocês fazem a análise de viabilidade e prospecção de terrenos hoje? Que ferramentas e fontes pagas usam?
5. Que informação da prefeitura vocês gostariam de ter e não têm, ou que só conseguem com muito esforço?
6. Pagariam por dados ou ferramentas que acelerem viabilidade ou aprovação? Quanto? Hoje pagam por algo equivalente?

**Influência sobre a prefeitura**
7. As associações do setor pressionam a prefeitura por modernização? Por quais canais (audiências, *council*, grupos de trabalho)?
8. Vocês apoiariam publicamente, com carta, depoimento ou presença em reunião, uma cidade que adotasse uma solução que reduzisse prazos?

**Mercado**
9. Onde vocês veem mais crescimento nos próximos 3 a 5 anos? Que cidades estão "no radar"?
10. Quem mais deveríamos ouvir?

> 💡 Se o modelo da Ospa Place tiver um lado B2B (mercado imobiliário) além do B2G, essas entrevistas também validam uma **segunda fonte de receita** e um **argumento de venda para a prefeitura**: "o seu mercado imobiliário quer isso".

### 3.4 Métodos de qualificação a aplicar
- **MEDDPICC** (padrão em enterprise/gov): *Metrics, Economic buyer, Decision criteria, Decision process, Paper process* (crítico em governo: o caminho de compra), *Identify pain, Champion, Competition*.
- **SPIN** para a condução da conversa: Situação → Problema → Implicação → Necessidade de solução.

### 3.5 Scorecard pós-diagnóstico (preencher após cada conversa)
| Critério | 1 (fraco) → 5 (forte) |
|---|---|
| Intensidade e urgência da dor | |
| Dor quantificada (tempo, US$, staff) | |
| Orçamento identificado / fonte de recurso | |
| Caminho de compra viável (≤ limite direto, cooperativo ou RFP previsível) | |
| Champion identificado | |
| Acesso ao decisor econômico | |
| Maturidade de dados para implantar | |
| Timing (vencimento de contrato, ciclo orçamentário, mandato) | |
| Pressão do mercado imobiliário local | |
| Potencial de referência (cidade influente no estado) | |

O resultado **reajusta os pesos do ICP Fit Score** (Parte 2) e define as contas para **pilotos / lighthouse accounts**.

---

## Parte 4: Entregáveis, RevOps e BI

### 4.1 Entregáveis sugeridos, em sequência
1. **Country brief EUA** (Parte 1) com recomendação go/no-go e condições.
2. **Base de municípios com score** (Parte 2), versionada, com fontes documentadas.
3. **Lista Tier A/B/C e account maps** das contas Tier A.
4. **Relatório de descoberta** (Parte 3): padrões de dor, citações, validação das hipóteses e ICP e personas revisados.
5. **Go-to-market plan:**
   - posicionamento e *messaging* em inglês;
   - pricing em USD;
   - caminho de compra (cooperativo, revenda, direto);
   - plano de pilotos;
   - metas e orçamento.

### 4.2 RevOps: preparar a operação antes da primeira oportunidade
- [ ] **CRM** com hierarquia **Estado → Condado → Cidade → Departamento → Contatos**. Campos específicos de governo:
  - população;
  - início do ano fiscal;
  - sistema atual e vencimento do contrato;
  - limite de compra direta;
  - contratos cooperativos aceitos;
  - status de RFP (*cone of silence*);
  - Fit Score e Tier.
- [ ] **Pipeline com estágios aderentes ao processo público:**
  1. Discovery
  2. Diagnóstico
  3. Champion confirmado
  4. Orçamento / fonte identificada
  5. Caminho de compra definido
  6. Proposta ou resposta a RFP
  7. Aprovação no *council*
  8. Contrato
- [ ] **Métricas de funil** por estágio, **ciclo de venda** (esperar 6 a 18 meses) e *win rate* por via de compra.
- [ ] **Alertas de gatilho** automatizados: novas RFPs/RFIs em portais de compras, vencimento de contratos, mudança de *City Manager*/CIO, palavras-chave em pautas de *council*.

### 4.3 Growth / go-to-market
- **ABM por tier:**
  - conteúdo por estado (lei estadual X → como cumprir);
  - webinars com associações;
  - cases traduzidos.
- **Parcerias e canal:**
  - Esri Partner Network;
  - revendedores de governo;
  - integradores e consultorias de planejamento urbano já presentes nas cidades.
- **Lighthouse accounts:** 1 a 3 cidades influentes no estado com condições especiais em troca de *case*, referência e co-apresentação em eventos.
- **Prova social local** vale mais que *case* estrangeiro. O primeiro cliente nos EUA é o maior desbloqueio comercial.

### 4.4 BI: painel de acompanhamento da internacionalização
- Mapa de municípios por Fit Score e Tier.
- Cobertura: contas pesquisadas → contatadas → diagnosticadas → em pipeline.
- Hipóteses validadas vs. invalidadas.
- Pipeline por estado, estágio e via de compra.
- Calendário de janelas orçamentárias e vencimentos de contrato.
- CAC estimado e *payback* no mercado EUA vs. Brasil.

---

## Parte 5: Dúvidas em aberto (para alinhar antes de detalhar)

1. **Produto:** qual é exatamente a proposta da Ospa Place hoje (licenciamento, inteligência territorial, dados imobiliários, marketplace)? Isso muda concorrentes, comprador e categoria de compra nos EUA.
2. **ICP atual no Brasil:** porte de município, comprador, ticket e ciclo de venda. É a base para traduzir o ICP para os EUA.
3. **Escopo do ICP nos EUA:** só *cities* ou também *counties*? Faixa populacional?
4. **Modelo:** só B2G ou também B2B (mercado imobiliário) nos EUA?
5. **Recursos:** orçamento, time dedicado (alguém baseado nos EUA?), prazo esperado para o primeiro contrato.
6. **Estado jurídico:** já existe entidade nos EUA e certificações (SOC 2 etc.)?
7. **Estados preferenciais:** há alguma conexão, contato ou cliente em potencial já existente que puxe para um estado específico?
8. **Formato final:** este documento no vault, uma planilha de scoring, um deck para a liderança?
