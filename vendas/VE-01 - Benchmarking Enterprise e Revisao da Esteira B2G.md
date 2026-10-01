# Benchmarking Enterprise e Revisão da Esteira de Vendas B2G

**Data:** 2026-10-01 · **Área:** Revenue Operations · OSPA Place
**Tipo:** Benchmarking + proposta de esteira em análise
**Status:** #em-analise

> Revisão da "PLC | esteira de vendas B2G" (quadro 2026.1) à luz de referências de vendas enterprise de ciclo longo, ticket alto e múltiplos decisores. O documento não substitui a esteira atual: ele mostra o que os modelos de referência fazem, aponta onde a nossa esteira já está alinhada, onde há lacunas de desenho e quais práticas fazem ou não sentido para prefeituras como público e para a plataforma da OSPA Place como produto. Cada proposta termina numa tabela de decisão.

Tipo: Benchmarking + proposta de processo
Fonte: pesquisa web em referências enterprise (Gartner, Forrester, Winning by Design, Bain, McKinsey, Ebsta/Pavilion, literatura de MEDDPICC e mutual action plan, capture management de govtech) e legislação brasileira de contratações públicas
Resumo: a esteira atual tem boa intuição de jornada (comitê de parceria, foco em inexigibilidade, CS com 24 meses), mas mistura objetos (lead, conta, comitê), usa marcos de atividade do vendedor em vez de evidência do comprador, define pipeline tarde demais e deixa o caminho de contratação e o orçamento para o fundo do funil
Como usar: ler a seção 0; depois a seção 3 (diagnóstico) e a seção 4 (esteira proposta); marcar decisões na seção 10
Tags: #revops #funil #pipeline #b2g #vendas-enterprise #em-analise

Conecta com: [[DE-02 - Benchmarking e Propostas para Analise]] · [[DE-01 - Diretriz Editorial OSPA Place]] · [[CW-06 - Copywriting para Vendas B2G no Setor Publico]]

---

## 0. Leitura rápida

1. **Pare de medir pessoas e passe a medir contas e oportunidades.** A estrutura MQL/SQL vem do funil B2C/inbound (o próprio quadro registra que "RD possui estrutura B2C, não uma estrutura MQA"). O modelo de referência para venda a comitês é o B2B Revenue Waterfall da Forrester, reescrito em 2021 justamente para trocar o lead individual pela oportunidade com grupo comprador.
2. **Marco de etapa é evidência do comprador, não atividade nossa.** "Foi realizada a reunião" é atividade. "O secretário formulou a dor com as próprias palavras e indicou quem mais precisa participar" é evidência. Todo modelo enterprise maduro usa critérios de saída verificáveis.
3. **Pipeline começa antes.** Hoje a palavra PIPELINE aparece só na etapa NGC pipeline (20 pts, ETP e TR enviados). Em enterprise, pipeline é toda oportunidade qualificada com dor validada; o que vem depois disso é *commit*. Com a definição atual, indicadores como pipeline coverage e forecast ficam distorcidos.
4. **O caminho de contratação e o orçamento são critérios de qualificação, não de fechamento.** Em B2G, a pergunta "por qual rito e com qual dotação a prefeitura compra?" decide se existe negócio. Ela precisa estar respondida no meio do funil.
5. **O comitê de parceria é o nosso melhor ativo de desenho.** Ele é exatamente o que Gartner chama de criação de consenso: grupos compradores que chegam a consenso têm 2,5 vezes mais chance de fechar um negócio de alta qualidade. O ajuste é transformá lo em compromisso do comprador (membros nomeados pela prefeitura) e acoplar a ele um plano de trabalho conjunto.
6. **O fechamento real é empenho, não contrato no jurídico interno.** "Contrato enviado para o jurídico interno" é um marco nosso. O cliente só se comprometeu quando o contrato está assinado, o extrato publicado e o empenho emitido.
7. **O lado direito do funil (CS) precisa de marcos tão claros quanto o esquerdo.** O modelo Bowtie da Winning by Design organiza o pós venda em onboarding, impacto e expansão; para nós, expansão em B2G tem caminhos próprios (aditivo, outras secretarias, consórcios, prefeituras vizinhas) e o cliente ativo é a principal fonte de novas contas.

---

## 1. Critério para decidir o que serve para nós

Quase todo benchmark enterprise disponível foi produzido com dados de SaaS privado nos Estados Unidos e na Europa. Antes de adotar qualquer prática, ela passa por quatro filtros:

| Filtro | Pergunta | Por que importa |
|---|---|---|
| Rito público | A prática é compatível com a Lei 14.133/2021, com a LRF e com as regras eleitorais? | Prefeitura não pode "assinar rápido" porque o vendedor criou urgência. O processo administrativo tem etapas obrigatórias. |
| Grupo comprador | Ajuda a mover um grupo heterogêneo (técnico, secretário, procuradoria, controle, fazenda, gabinete)? | Em B2G o comitê é ainda mais diverso que em B2B, e inclui quem não usa o produto mas pode vetar. |
| Calendário | Respeita o calendário de gestão (PPA, LOA, mandato, eleição)? | O "evento crítico" em governo é quase sempre de calendário, e ele é público e previsível. |
| Marca e experiência | Faz a prefeitura se sentir conduzida por um parceiro especialista, e não pressionada por um fornecedor? | O cliente ativo vende a próxima prefeitura. A experiência de compra é parte do produto. |

---

## 2. As referências

### 2.1 Gartner: jobs de compra, buyer enablement e consenso

**O que é.** O Gartner descreve a compra B2B como seis "jobs" que o grupo comprador precisa cumprir, não como etapas lineares: identificação do problema, exploração de soluções, construção de requisitos, seleção de fornecedor, validação e criação de consenso. Os jobs acontecem em paralelo e em loop; 95% dos grupos revisitam ao menos um deles antes de decidir ([Gartner](https://www.gartner.com/en/sales/insights/b2b-buying-journey), [Growth Method](https://growthmethod.com/gartner-b2b-buying-journey/)).

**Dados que importam para nós.**
- Grupos que chegam a consenso têm 2,5 vezes mais chance de reportar um negócio de alta qualidade, e 74% dos grupos compradores vivem conflito "não saudável" durante a decisão ([Gartner, 2025](https://www.gartner.com/en/newsroom/press-releases/2025-05-07-gartner-sales-survey-finds-74-percent-of-b2b-buyer-teams-demonstrate-unhealthy-conflict-during-the-decision-process)).
- Grupos compradores chegam a 16 pessoas de até quatro funções ([Intentsify, sobre a pesquisa Gartner](https://intentsify.io/blog/how-b2b-buying-groups-are-evolving/)).
- Compradores expostos a conteúdo de *buyer enablement* (orientação prescritiva para cumprir os jobs de compra, e não material sobre o produto) têm três vezes mais chance de fazer uma compra de alta qualidade, mais ambiciosa e com preço maior ([Gartner, Marketing's Role in Buyer Enablement](https://www.gartner.com/en/marketing/insights/articles/marketings-role-in-buyer-enablement)).
- Em 2026, 67% dos compradores B2B dizem preferir uma experiência sem vendedor ([Gartner, 2026](https://www.gartner.com/en/newsroom/press-releases/2026-03-09-gartner-sales-survey-finds-67-percent-of-b2b-buyers-prefer-a-rep-free-experience)).

**O que copiar.** Desenhar cada etapa a partir do job que a prefeitura precisa cumprir naquele momento, e entregar o material que ajuda a cumpri lo. Em B2G, os jobs "construção de requisitos" e "validação" têm forma concreta: DFD, ETP, TR, pesquisa de preço e parecer jurídico. Quem entrega à prefeitura o caminho das pedras desse processo está fazendo buyer enablement no sentido mais literal.

**O que não serve.** A preferência por compra sem vendedor não se aplica à contratação em si (o rito exige interação formal), mas se aplica fortemente à fase de autoeducação: o técnico de planejamento quer explorar o produto, ver cases e entender preço antes de expor o assunto ao secretário.

### 2.2 Forrester: B2B Revenue Waterfall (conta, oportunidade e grupo comprador)

**O que é.** Depois de comprar a SiriusDecisions, a Forrester reescreveu o Demand Waterfall em 2021 para ser centrado em oportunidade: o grupo comprador fica vinculado à oportunidade e avança junto com ela, das contas alvo até o fechamento, incluindo retenção e expansão ([Forrester, guia do Waterfall](https://www.forrester.com/b2b-marketing/b2b-revenue-waterfall-guide/), [LeanData](https://www.leandata.com/blog/your-cheat-sheet-for-b2b-revenue-waterfall-transformation/)).

**Estágios de conta:** *detected* (sinal de interesse), *engaged* (pessoas do grupo comprador interagindo), *prioritized* (interações múltiplas que indicam intenção séria) e *qualified* (vendas aceita e qualifica) ([Full Circle Insights](https://www.fullcircleinsights.com/resource/forresters-b2b-revenue-abm-measurement)). Os programas de demanda têm três objetivos: ativar, validar (capturar mais membros do grupo) e acelerar.

**Dados que importam para nós.** Oportunidades de aquisição têm o ciclo mais longo e a menor conversão; upsell converte melhor que cross sell, e retenção é a que mais converte ([Forrester, via Axcient](https://axcient.com/blog/demand-waterfall-8-ways-to-optimize-your-sales-cycle/)).

**O que copiar.** É o modelo que resolve a mistura de objetos da nossa esteira (seção 3, achado 1). A unidade de gestão passa a ser a prefeitura (conta), depois a oportunidade (uma dor, uma solução, um caminho de contratação) e, dentro dela, o grupo comprador com papéis.

**O que não serve.** O *detected* da Forrester depende de provedores de dados de intenção (Bombora, 6sense, Demandbase), que não cobrem prefeituras brasileiras. Para nós, o sinal vem de fontes públicas (seção 2.6).

### 2.3 Winning by Design: Bowtie, SPICED e impacto

**O que é.** O Bowtie estende o funil para depois da venda: Awareness, Education, Selection, **Mutual Commit**, Onboarding, Impact e Expansion. A tese é que valor é promessa de impacto futuro e impacto é o cumprimento dessa promessa; em receita recorrente, a pergunta que conecta os dois lados é "que impacto nos comprometemos a entregar no fechamento, e até quando?" ([Winning by Design, The Bowtie](https://winningbydesign.com/wp-content/uploads/2026/02/The-Bowtie-A-Proposed-Standard.pdf), [RevPartners](https://blog.revpartners.io/en/revops-articles/bowtie-funnel)).

A metodologia de descoberta associada é o **SPICED**: Situation, Pain, Impact, Critical Event, Decision ([RevenueFlow](https://www.revenueflow.com/blog/winning-design-sales-methodology)).

**O que copiar.**
- O nome "Mutual Commit": o fechamento é um compromisso dos dois lados, e não um evento do vendedor. Encaixa com a linguagem de "parceria" que já usamos.
- O conceito de **Critical Event**, que é o que mais falta no nosso quadro (o desafio "como passar senso de urgência conforme calendário de gestão" é exatamente isso). Em prefeitura, o evento crítico é quase sempre público: revisão do plano diretor, envio da LOA, fim de mandato, prazo de financiamento.
- Medir o lado direito com o mesmo rigor do esquerdo: tempo até o primeiro impacto, impacto recorrente, expansão.

**O que não serve.** O Bowtie pressupõe que o cliente decide renovar ou expandir com relativa liberdade. Em contrato público, renovação é prorrogação contratual e expansão é aditivo (com limite legal) ou nova contratação. A lógica vale; os gatilhos são outros.

### 2.4 MEDDPICC e critérios de saída baseados em evidência

**O que é.** MEDDPICC (Metrics, Economic buyer, Decision criteria, Decision process, Paper process, Identify pain, Champion, Competition) é o padrão de qualificação de venda enterprise. A prática madura não usa MEDDPICC como etapa, e sim como fonte de critérios de saída: cada etapa tem de 2 a 4 critérios objetivos e verificáveis, porque "sem eles, avançar de etapa é otimismo registrado num campo do CRM" ([Digital Applied](https://www.digitalapplied.com/blog/sales-pipeline-stage-definitions-2026-crm-framework), [Federico Presicci](https://federicopresicci.com/blog/sales-methodology/how-to-implement-the-meddpicc-sales-methodology/)).

**O que copiar.** O quadro já cita BANT, SPIN e MEDDPICC como desafio. A recomendação é escolher um só como linguagem comum (MEDDPICC, adaptado na seção 5) e usar SPIN como técnica de conversa, não como critério. BANT é o menos adequado: "Budget" e "Timing" em governo não são perguntas, são documentos públicos (LOA, PPA, calendário).

**Destaque para nós:** o "P" de **Paper process** é, em B2G, o próprio rito de contratação. É o elemento que mais diferencia a nossa venda e o que mais precisa de método.

### 2.5 Mutual Action Plan (plano de trabalho conjunto)

**O que é.** Um plano construído com o grupo comprador, com etapas, responsáveis nomeados dos dois lados e datas, que transforma a reta final em projeto conjunto ([Highspot](https://www.highspot.com/blog/mutual-action-plan/), [Aviso](https://www.aviso.com/blog/mutual-action-plan)). Análises de fornecedores de sales engagement reportam ganhos de taxa de conversão relevantes em negócios com plano conjunto (26% maior segundo a Outreach; outros relatos chegam a quase o dobro). Os números vêm de fornecedores que vendem a ferramenta, então valem como direção, não como meta.

**Por que serve muito para B2G.** "Plano de trabalho" é linguagem nativa da administração pública (convênios, termos de cooperação). Um documento chamado **Plano de Trabalho da Parceria**, com as etapas do rito (DFD, ETP, TR, parecer, dotação, publicação), quem da prefeitura responde por cada uma, e o que a OSPA Place entrega em cada uma, resolve três desafios do quadro de uma vez: manter o comitê engajado durante a fase jurídica, prever a data de fechamento e mostrar profissionalismo ("deixar docs + profissional").

### 2.6 Captura pré edital em govtech

**O que é.** Em vendas para governo nos EUA (SLED), a prática de *capture management* trabalha a conta de 12 a 18 meses antes da licitação: descoberta (o órgão discute o problema, sem orçamento), planejamento (o orçamento aparece) e contratação (requisitos e documentos sendo redigidos). O edital publicado é o sinal de **menor** valor, porque o fornecedor preferido já está estabelecido ([Starbridge](https://starbridge.ai/blog/sled-sales), [Civic IQ](https://blogs.civiciq.com/2026/05/07/10-pre-rfp-signals-every-b2g-sales-team-should-track-with-real-examples/)).

**Dados.** Fornecedores que se engajam 12 meses ou mais antes do edital ganham cerca de 34%, contra 18% de quem chega no edital e 10% a 15% de quem só responde. Compras de tecnologia em governo levam em média 22 meses nos EUA ([Starbridge](https://starbridge.ai/blog/sled-sales)). Esses números são de mercado americano e de fonte comercial; servem para dimensionar ordem de grandeza.

**O que copiar.** A lista de sinais, traduzida para prefeituras brasileiras:

| Sinal público | Onde ver | Por que indica compra |
|---|---|---|
| Revisão do plano diretor (obrigatória a cada 10 anos pelo Estatuto da Cidade, art. 40, §3º) | site da prefeitura, câmara, audiências públicas | é o maior gatilho de demanda por planejamento urbano e dados territoriais |
| Item no PPA ou na LOA ligado a planejamento, geo, cadastro, licenciamento ou inovação | portal da transparência, câmara | existe dotação |
| Financiamento ou programa com componente de modernização (BID, CAF, Caixa, programas federais) | diário oficial, sites dos financiadores | há recurso carimbado e prazo |
| Atualização da planta genérica de valores ou do cadastro imobiliário | diário oficial, câmara | conecta com arrecadação, que é o argumento da Fazenda |
| Novo secretário de planejamento, urbanismo, inovação ou fazenda | diário oficial | janela de agenda nova |
| Contratação de fornecedor da mesma categoria (ou vencimento de contrato) | PNCP, portal da transparência | demanda já reconhecida, e contrato com data para acabar |
| Menção à categoria em plano de governo ou plano estratégico | site da prefeitura | prioridade política declarada |

**O que não serve.** A lógica de "influenciar os critérios do edital" precisa ser feita com cuidado no Brasil: contribuir com informação técnica e com consulta pública é legítimo; redigir requisitos que direcionem a licitação não é. Na inexigibilidade a lógica é outra (seção 3, achado 4), mas o princípio do trabalho antecipado continua valendo.

### 2.7 Bain: B2B Elements of Value (marca e experiência)

**O que é.** A Bain identificou 40 elementos de valor em B2B, em cinco camadas: requisitos mínimos (especificação, preço aceitável, conformidade regulatória, ética), valor funcional (econômico e de desempenho), facilidade de fazer negócio, valor individual (redução de risco pessoal, reputação, crescimento na carreira) e valor inspiracional (visão, esperança, responsabilidade social) ([HBR/Bain](https://hbr.org/2018/03/the-b2b-elements-of-value), [Bain, gráfico interativo](https://media.bain.com/b2b-eov/)).

**Por que é a referência certa para "jornada como design de experiência com a marca".** Em prefeitura, as camadas superiores pesam muito. Valor individual tem nome: o servidor que patrocina a compra está expondo a própria reputação diante do secretário, da procuradoria e do controle; o secretário quer entregar algo visível na gestão. Valor inspiracional também: "cidade que funciona melhor para quem vive nela" e "cidades responsivas" (DE-01, 3.3). E "facilidade de fazer negócio" em B2G significa, concretamente, facilitar o processo administrativo.

**Cuidado:** o desafio do quadro "como usar o fechamento como capital político" é legítimo enquanto o protagonista for a instituição. Promoção pessoal de autoridade é vedada (CF, art. 37, §1º; ver DE-02, P2).

### 2.8 Benchmarks numéricos de referência

Usar como ordem de grandeza, nunca como meta. São dados de SaaS privado, majoritariamente nos EUA.

| Indicador | Referência | Fonte |
|---|---|---|
| Taxa de conversão média B2B (oportunidade para ganho) | 19% em 2025, contra 29% no ano anterior | [Ebsta e Pavilion, via Gradient Works](https://www.gradient.works/blog/2025-b2b-sales-performance-benchmarks) |
| Ciclo de venda mediano, ticket acima de US$ 100 mil/ano | 192 dias (84 dias abaixo de US$ 50 mil) | idem |
| Conversão por duração do ciclo | cerca de 47% quando fecha em até 50 dias; cerca de 20% depois disso | idem |
| Envolvimento precoce de quem decide | aumenta a conversão em 55% | idem |
| Multithreading (vários contatos no cliente) | aumenta a conversão em 130% em negócios acima de US$ 50 mil; negócios ganhos têm cerca de 2 vezes mais contatos que os perdidos | idem |
| Tamanho do grupo de decisão | 13 pessoas internas e 9 externas; procurement decide em 53% dos ciclos | idem |
| Canais usados na compra | 10,2 canais em média; regra dos terços (presencial, remoto, autosserviço) | [McKinsey B2B Pulse 2024](https://www.mckinsey.com/capabilities/growth-marketing-and-sales/our-insights/five-fundamental-truths-how-b2b-winners-keep-growing) |
| Ciclo de tecnologia em governo (EUA) | 22 meses em média; receita fecha 6 a 18 meses depois do primeiro contato | [Starbridge](https://starbridge.ai/blog/sled-sales), [SaasDash](https://saasdash.ai/blog/govtech-saas-procurement-sales-cycle) |

**Leitura para a OSPA Place.** A soma dos objetivos do quadro (90 + 75 + 90 dias, cerca de 8,5 meses) está dentro do esperado para govtech. O que os dados sugerem não é encurtar a meta total, mas separar o **tempo de maturação da conta** (que pode levar 12 meses ou mais e não deve contar contra o vendedor) do **ciclo da oportunidade** (a partir da dor validada, que precisa de SLA por etapa). E o dado de "procurement decide em 53% dos ciclos" tem tradução direta: procuradoria e controle interno são parte do comitê desde o meio do funil, não só no fundo.

---

## 3. Diagnóstico da esteira atual

### Achado 1. A esteira mistura três objetos diferentes

**No quadro:** MQL e MQL engajado contam pessoas ("lead GOV"); MQL interação conta contas ("conta / prefeitura relevante", #MQA); SQL interação volta para pessoa ("essencial ter SQL"); SQL intenção conta o comitê; NGC conta negociação e LTV.

**Problema:** quando o objeto muda no meio do funil, as taxas de conversão entre etapas deixam de ser comparáveis (uma prefeitura pode ter 5 leads e 1 SQL; outra, 1 lead e 3 SQLs), e o CRM não consegue mostrar quantas *prefeituras* estão em cada etapa. O próprio quadro já sente isso ("MQA sem SQL; MQA dif. SQA").

**Referência:** Forrester Waterfall (2.2).

**Recomendação:** três camadas explícitas, cada uma com o seu funil:
- **Conta (prefeitura):** ICP, sinal, engajada, priorizada (MQA).
- **Oportunidade:** uma dor, uma solução, um caminho de contratação. É a única que tem valor, data e probabilidade.
- **Grupo comprador:** pessoas com papel atribuído dentro da oportunidade (seção 5). A métrica "#contatos x comitê" do quadro vira cobertura do grupo comprador: quantos dos papéis necessários já estão engajados.

### Achado 2. Os marcos descrevem a nossa atividade, não o compromisso do comprador

**No quadro:** "foi realizada a primeira reunião", "foi realizada a demonstração", "foi realizada a reunião de proposta", "contrato enviado para o jurídico interno".

**Problema:** todos podem ser cumpridos sem que a prefeitura tenha avançado nada. É o que gera as dores de previsibilidade listadas no quadro (opp forecasting, data de fechamento, deal aging).

**Referência:** critérios de saída verificáveis (2.4); Bowtie, Mutual Commit (2.3).

**Recomendação:** reescrever cada marco como algo que o cliente fez ou disse, verificável por registro (e mail, ata, documento protocolado, nomeação). A seção 4 traz a versão proposta. Exemplo: "SQL consideração" deixa de ser "foi realizada a demonstração com +1 secretaria" e passa a ser "duas ou mais secretarias confirmaram por escrito a dor e o resultado esperado, e o patrocinador indicou quem mais precisa participar". A boa intuição do quadro, "dor explícita formulada", já está lá; ela só precisa virar o critério principal, e não um selo.

### Achado 3. "Pipeline" está definido tarde demais

**No quadro:** a seta PIPELINE e os "20 pts" ficam entre NGC negociação e NGC pipeline (ETP e TR enviados).

**Problema:** em enterprise, pipeline é o conjunto de oportunidades qualificadas, com valor e data, a partir do momento em que a dor está validada. O que o quadro chama de pipeline é o que o mercado chama de *commit*. Com a definição atual, pipeline coverage (indicador listado no CX) mede a cobertura apenas dos negócios quase fechados, e o forecast fica sem base para o trimestre seguinte.

**Recomendação:** pipeline a partir da etapa de dor validada (O2 na seção 4) e categorias de forecast padronizadas: *pipeline* (O2 e O3), *best case* (O4), *commit* (O5) e *fechado* (O6). A etapa hoje chamada "NGC pipeline" passa a se chamar "Formalização" ou "Commit".

### Achado 4. Caminho de contratação e orçamento aparecem só no fundo

**No quadro:** "foco: inex" aparece na NGC negociação; "quem paga + quem assina" aparece como desafio na SQL intenção; ETP e TR, na NGC pipeline.

**Problema:** em B2G, uma oportunidade sem caminho de contratação viável e sem fonte de recurso não é oportunidade, por mais engajado que esteja o comitê. Descobrir isso no fundo custa 3 a 5 meses de ciclo.

**Recomendação:** um critério de saída do meio do funil é **"rota de contratação e fonte de recurso definidas"**: qual modalidade (inexigibilidade, CPSI, adesão a ata, licitação), qual dotação ou financiamento, quem é o ordenador de despesa. As rotas mais comuns e o que cada uma exige:

| Rota | Base legal | Quando faz sentido | O que exige da OSPA Place |
|---|---|---|---|
| Inexigibilidade | Lei 14.133/2021, art. 74 (inviabilidade de competição) | solução sem concorrente equivalente demonstrável | demonstração da inviabilidade de competição no ETP, justificativa de preço com contratos e notas fiscais de outros entes (art. 23, §4º), habilitação, divulgação do ato (art. 72) |
| CPSI (contrato público para solução inovadora) | LC 182/2021 (Marco Legal das Startups) | prefeitura quer testar em escala real antes de contratar por mais tempo | resposta a edital de problema; contrato de teste com teto e prazo legais, e possibilidade de fornecimento posterior sem nova licitação ([AGU, manual do CPSI](https://www.gov.br/agu/pt-br/assuntos-1/labori/minutas/manual-do-contrato-publico-para-solucao-inovadora.pdf)) |
| Adesão a ata de registro de preços | Lei 14.133/2021, art. 86 | existe ata vigente compatível | ata de outro ente que permita adesão, nos limites legais |
| Licitação | Lei 14.133/2021 | não há inviabilidade de competição | trabalho anterior ao edital (2.6), sem direcionamento |

*Valores, prazos e limites de cada rota precisam ser validados com o jurídico antes de virarem material de vendas.*

### Achado 5. Falta o evento crítico (calendário de gestão)

**No quadro:** "como passar senso de urgência conforme calendário de gestão / prioridades do gabinete" e "estabelecer urgência na dor" aparecem como desafios.

**Referência:** SPICED, Critical Event (2.3).

**Recomendação:** registrar em toda oportunidade a data e a natureza do evento crítico, e usá la para o plano de trabalho conjunto. O calendário de 2026 a 2028 já tem os eventos mais fortes:
- **LOA de cada ano:** o envio à câmara (prazo definido na Lei Orgânica de cada município, normalmente no segundo semestre) decide se existe dotação para o ano seguinte. Oportunidade sem dotação em 2027 precisa estar na LOA 2027 agora.
- **Últimos dois quadrimestres do mandato (a partir de maio de 2028):** a LRF, art. 42, restringe a assunção de despesa que não possa ser paga dentro do mandato sem disponibilidade de caixa.
- **Período eleitoral de 2028 (a partir de julho):** a prefeitura não pode fazer publicidade institucional, então não divulga a parceria (DE-02, P2). Transferências voluntárias também ficam restritas nos três meses antes de eleições, o que afeta negócios financiados por convênio.
- **Revisão do plano diretor, financiamentos com prazo e início de gestão de secretário.**

Na prática, isso significa que **2027 é a principal janela de fechamento do mandato atual**, e que oportunidades que não chegarem à formalização até o início de 2028 tendem a ficar para o próximo mandato. *Validar as leituras jurídicas com o jurídico.*

### Achado 6. "Fechamento" termina antes do compromisso do cliente

**No quadro:** NGC fechamento = "contrato enviado para o jurídico interno".

**Recomendação:** dividir em dois marcos: *Formalização* (processo administrativo completo do lado da prefeitura: ETP e TR aprovados, parecer jurídico, reserva orçamentária) e *Contratação* (contrato assinado, ato publicado no PNCP e no diário oficial, empenho emitido). O empenho é o que dá segurança de receita em B2G; é ele que deve contar como ganho no CRM.

### Achado 7. O score de 20 pontos não é transparente

**No quadro:** "quando a negociação atingiu 20 pts = ETP e TR enviados".

**Problema:** se o score não diz de onde vêm os pontos, ele não ajuda o vendedor a saber o que falta, nem a liderança a inspecionar o negócio.

**Recomendação:** substituir pelo scorecard da seção 5, com pontuação por elemento e mínimo por etapa. Mantém a ideia de "pontos para avançar", mas cada ponto tem evidência.

### Achado 8. O lado direito tem intenção, mas não tem etapas

**No quadro:** CX/CS com "6 + 24 meses", passagem de bastão, portal do cliente, jornada de encantamento, capacitação, data storytelling.

**Recomendação:** etapas do Bowtie adaptadas (seção 4, C1 a C5), com um marco de impacto que **já foi prometido na venda**. O resultado esperado combinado com o comitê na etapa O2 é o que o CS precisa entregar e medir, e é o que alimenta o case aprovado (DE-02, P4: registrar a linha de base no início do projeto). Isso fecha o ciclo entre vendas, CS e marketing.

---

## 4. Esteira proposta (versão detalhada)

### 4.1 Visão geral

```
CONTA (prefeitura)                 OPORTUNIDADE                                                     CLIENTE
A0 ICP > A1 Sinal > A2 Engajada > A3 Priorizada (MQA)
                                   O1 Descoberta > O2 Dor validada > O3 Comitê e plano > O4 Rota e proposta > O5 Formalização > O6 Contratação
                                                   |-- pipeline ------------------------------|-- commit ----|-- ganho --|
                                                                                                                         C1 Kickoff > C2 Primeiro impacto > C3 Impacto recorrente > C4 Expansão e prorrogação > C5 Referência
                                                                                                                                                                                                  |
                                                                       (C5 volta para A1 de prefeituras vizinhas, consórcios e pares) <----------------------------------------------------------+
```

### 4.2 Camada de conta (antigo topo de funil)

| Etapa | Equivale hoje a | Critério de saída (evidência) | KPI | Ativos de experiência |
|---|---|---|---|---|
| **A0 Conta no ICP** | (não existe) | prefeitura classificada em tier: Tier 1 (abordagem individual), Tier 2 (cluster), Tier 3 (escala), com base em porte (o quadro cita acima de 15 mil habitantes), maturidade digital, sinais e fit de produto | # contas por tier; % do ICP coberto | nenhum ativo: é trabalho interno de inteligência |
| **A1 Conta com sinal** | MQL (parcial) | ao menos um sinal público da tabela da seção 2.6, ou um contato da prefeitura converteu em ação de marketing | # contas com sinal; idade do sinal | conteúdo de ponto de vista ligado ao sinal (plano diretor, arrecadação, licenciamento) |
| **A2 Conta engajada** | MQL engajado | duas ou mais pessoas da mesma prefeitura interagiram, ou uma pessoa levantou a mão explicitamente | # contas engajadas; pessoas por conta | cases de prefeituras de porte parecido; evento ou webinar com pares |
| **A3 Conta priorizada (MQA)** | MQL interação | conta engajada, no tier certo, com resposta direta a uma abordagem e um interlocutor da área de negócio identificado | # MQA; taxa A2 para A3; tempo em A2 | convite para conversa de diagnóstico (não para demo) |

**Regra:** a conta pode ficar em A1 e A2 por muitos meses sem penalizar ninguém. O SLA de tempo começa em A3.

### 4.3 Camada de oportunidade (antigos meio e fundo)

| Etapa | Equivale hoje a | Job de compra (Gartner) | Critério de saída (evidência do comprador) | KPI e SLA sugerido | Ativos de experiência |
|---|---|---|---|---|---|
| **O1 Descoberta** | SQL interação e SQL apresentação | identificação do problema | reunião com quem tem a dor; situação atual descrita; hipótese de dor e de evento crítico registradas; próximo passo com data aceito pelo cliente | # O1 criadas; no show; SLA 30 dias | roteiro de diagnóstico (SPIN como técnica); material de leitura prévia; demo gravada para quem não esteve |
| **O2 Dor validada** (entra no pipeline) | SQL consideração | exploração de soluções | dor formulada pelo cliente com as próprias palavras; resultado esperado com uma métrica; ao menos duas secretarias envolvidas; patrocinador (champion) testado; evento crítico com data | # e valor de pipeline criado; taxa O1 para O2; SLA 45 dias | demonstração feita sobre o território do município; estimativa de impacto (tempo de licenciamento, arrecadação, transparência) |
| **O3 Comitê e plano de trabalho** | SQL intenção | construção de requisitos e consenso | prefeitura indica formalmente os membros do comitê de parceria (técnico, negócio, procuradoria ou controle, fazenda, gabinete); workshop de sensibilização realizado; **plano de trabalho conjunto aceito** | cobertura do grupo comprador (papéis engajados / papéis necessários); SLA 45 dias | workshop (já previsto no quadro); Plano de Trabalho da Parceria; "kit do comitê" com um ângulo por papel (DE-02, P8) |
| **O4 Rota e proposta** | NGC negociação | seleção de fornecedor e validação | rota de contratação e fonte de recurso definidas; ordenador de despesa identificado; proposta apresentada ao comitê e aval por escrito (e mail) | valor médio; taxa O3 para O4; SLA 30 dias | proposta organizada por resultado, não por funcionalidade; tabela de preço com justificativa (contratos de outros entes); visita técnica ou conversa com prefeitura cliente |
| **O5 Formalização** (commit) | NGC pipeline (20 pts) | validação e consenso final | processo administrativo aberto pela prefeitura (DFD); ETP e TR protocolados; pesquisa ou justificativa de preço anexada; reserva orçamentária; parecer jurídico solicitado | % O4 para O5; data de fechamento prevista com base no plano; SLA 60 dias | **dossiê de contratação** por rota (modelos de ETP e TR, documentos de habilitação, atestados, justificativa de preço); ponto focal da OSPA Place para dúvidas da procuradoria |
| **O6 Contratação** (ganho) | NGC fechamento | (fim da compra) | ato de contratação autorizado e publicado; contrato assinado; **empenho emitido** | taxa de ganho; ciclo O1 a O6; valor contratado | kickoff já agendado na assinatura; comunicado conjunto aprovado pela Secom (DE-02, P1) |

Os SLAs somam cerca de 210 dias (aproximadamente 7 meses) de oportunidade, coerentes com os 165 dias de meio e fundo do quadro somados à parte de SQL que hoje está no topo. São propostas iniciais: o certo é calibrar com o tempo mediano real de cada etapa nos negócios ganhos dos últimos 18 meses.

**Saídas laterais (toda etapa):** *perdida* com motivo padronizado (sem dor, sem rota, sem recurso, concorrente, status quo, mudança política) e *em espera* com data de reativação ligada a um evento crítico (nova LOA, novo secretário, próximo mandato). Em B2G, muita oportunidade não morre, hiberna; tratá la como perda distorce a taxa de ganho, e tratá la como aberta distorce o pipeline.

### 4.4 Camada de cliente (CX/CS)

| Etapa | Critério de saída | KPI | O que conecta com a venda |
|---|---|---|---|
| **C1 Kickoff** (passagem de bastão) | reunião com comitê, CS e gestão de projeto; plano de implantação e linha de base registrados | tempo entre empenho e kickoff | o resultado esperado de O2 e o plano de trabalho de O3 passam integralmente para o CS |
| **C2 Primeiro impacto** | primeiro resultado do resultado esperado, reconhecido pelo cliente | tempo até o primeiro impacto (time to first value) | é a primeira prova da promessa de venda |
| **C3 Impacto recorrente** | uso regular por servidores; capacitação concluída; relatório de impacto periódico (o "data storytelling" do quadro) | uso ativo; impacto medido contra a linha de base | alimenta case e renovação |
| **C4 Expansão e prorrogação** | aditivo (dentro dos limites do art. 125 da Lei 14.133), nova secretaria, novo módulo, ou prorrogação contratual | receita de expansão; taxa de prorrogação | expansão para outras secretarias reabre o grupo comprador (volta a O2 dentro da mesma conta) |
| **C5 Referência** | case aprovado pela prefeitura; disponibilidade para receber visita técnica ou conversar com outra prefeitura | # referências ativas; contas novas originadas por referência | prefeituras vizinhas, consórcios intermunicipais e redes de secretários entram em A1 com sinal forte |

---

## 5. Scorecard de qualificação (substitui os "20 pts")

MEDDPICC adaptado a governo, com um elemento a mais (G, governo e calendário). Cada elemento recebe de 0 a 3 pontos, sempre com evidência registrada no CRM. Máximo de 27 pontos.

| Elemento | O que significa em prefeitura | 0 | 1 | 2 | 3 |
|---|---|---|---|---|---|
| **M** Métrica | resultado mensurável esperado (tempo de licenciamento, arrecadação, atendimento ao cidadão) | nada | genérico | métrica citada pelo cliente | métrica com linha de base e meta aceitas |
| **E** Decisor econômico | ordenador de despesa e, quando aplicável, gabinete | desconhecido | identificado | já ouviu da proposta | apoia explicitamente |
| **D1** Critérios de decisão | o que o comitê vai avaliar (técnico, jurídico, preço, aderência a política pública) | desconhecidos | supostos | declarados | declarados e favoráveis a nós |
| **D2** Processo de decisão | quem participa e em que ordem até o "sim" político | desconhecido | parcial | mapeado | mapeado e validado com o champion |
| **P** Rito de contratação | rota, documentos, prazos, parecer jurídico, publicação | desconhecido | rota hipotética | rota definida com a prefeitura | processo aberto e em andamento |
| **I** Dor | dor explícita, com consequência para a gestão | hipótese nossa | dor de uma pessoa | dor reconhecida por duas ou mais secretarias | dor priorizada pelo gabinete |
| **C1** Champion | quem vende por nós quando não estamos na sala | nenhum | simpatizante | defende internamente | já moveu alguém ou algo a nosso favor |
| **C2** Concorrência | outro fornecedor, solução interna (TI própria, empresa municipal de TI) ou não fazer nada | desconhecida | conhecida | mapeada com estratégia | neutralizada |
| **G** Governo e calendário | evento crítico, dotação e janela política | nada | evento crítico identificado | dotação ou fonte identificada | evento crítico e dotação confirmados |

**Mínimos sugeridos por etapa:** O2 com 8 pontos (com I de pelo menos 2), O3 com 13, O4 com 17 (com P e G de pelo menos 2), O5 com 21. Os números são ponto de partida; o importante é que a etapa não avança se o elemento mínimo não tiver evidência.

**Papéis do grupo comprador a mapear em toda oportunidade:** técnico usuário (geo, planejamento, TI), dono da dor (secretário de área), ordenador de despesa, procuradoria e controle interno, fazenda (quando o argumento é arrecadação), gabinete e, quando houver, empresa municipal de TI ou instituto de planejamento. Isso responde diretamente ao desafio "descobrir níveis decisórios internos: equipe tech/geo + jurídico + quem paga + quem assina".

---

## 6. Jornada de experiência com a marca

A pergunta de desenho em cada etapa é: **o que a prefeitura precisa saber, sentir e conseguir fazer para dar o próximo passo sozinha?** Isso é buyer enablement (2.1) aplicado aos elementos de valor (2.7).

| Momento | O que a prefeitura precisa | Momento da verdade | Ativo de marca sugerido |
|---|---|---|---|
| Sinal e engajamento | reconhecer o próprio problema numa história de outra prefeitura | o primeiro conteúdo que chega via vendedor | case com a prefeitura protagonista (DE-01) e conteúdo ligado ao evento crítico |
| Descoberta | sentir que foi entendida antes de ver o produto | a primeira reunião é diagnóstico, não demo | roteiro de diagnóstico; resumo da conversa enviado depois, com as palavras do cliente |
| Dor validada | ver o próprio município na plataforma | a demonstração sobre o território dela | demo com dados do município; estimativa de impacto |
| Comitê | ter argumentos para convencer os colegas | o workshop | kit do comitê, um ângulo por papel; plano de trabalho conjunto |
| Rota e proposta | sentir segurança jurídica | a primeira pergunta da procuradoria | dossiê de contratação por rota; conversa com prefeitura cliente |
| Formalização | não se sentir sozinha no processo administrativo | o momento em que o processo trava | ponto focal com resposta rápida; acompanhamento do plano de trabalho |
| Contratação e kickoff | ver valor rápido e poder comunicar | o primeiro mês | kickoff em até X dias; comunicado conjunto aprovado pela Secom |
| Impacto | provar resultado para dentro e para fora | o primeiro relatório de impacto | relatório periódico; portal do cliente; trilha de capacitação |
| Referência | ser reconhecida como cidade inovadora | o convite para ser case | case aprovado; visita técnica; participação em eventos de pares |

O ponto que a maioria das empresas perde, e que os modelos de referência enfatizam, é que **o material mais valioso para o comprador não é sobre o produto, é sobre como comprar**. Para a OSPA Place, o dossiê de contratação e o plano de trabalho conjunto são provavelmente os dois ativos de maior retorno a construir, e respondem ao desafio "quais docs de inex enviamos em cada etapa?".

---

## 7. Métricas de RevOps

| Métrica | Definição proposta | Observação |
|---|---|---|
| Conversão por etapa | % de oportunidades que saem de uma etapa para a seguinte, por coorte de entrada | medir por coorte, não por mês corrente, porque o ciclo é longo |
| Tempo em etapa (deal aging) | dias desde a entrada na etapa, comparado ao SLA | alerta quando passar de 1,5 vez o SLA |
| Sales velocity | (# oportunidades no pipeline × valor médio × taxa de ganho) / ciclo médio em dias | indicador já listado no quadro; só funciona com pipeline definido em O2 |
| Pipeline coverage | valor em O2 a O5 com data de fechamento no período / meta do período | a referência usual em SaaS é de 3 a 4 vezes; com taxa de ganho menor e ciclo político, provavelmente precisamos de mais (calibrar com histórico) |
| Forecast | soma por categoria (pipeline, best case, commit) | commit = O5; só entra com plano de trabalho com datas |
| Cobertura do grupo comprador | papéis engajados / papéis necessários | substitui "#contatos x comitê" |
| Taxa de ganho | ganhas / (ganhas + perdidas), excluindo "em espera" | separar por rota de contratação e por tier |
| Tempo até o primeiro impacto | dias entre empenho e C2 | principal indicador de CS no primeiro semestre |
| Receita líquida retida | receita do período seguinte dos mesmos clientes, incluindo aditivos e prorrogações / receita atual | adaptação do NRR para contratos públicos |
| Contas originadas por referência | contas em A1 cuja origem é um cliente em C5 | mede o loop do Bowtie |

---

## 8. Resposta aos desafios do quadro

| Desafio no quadro | Onde está a resposta |
|---|---|
| RD com estrutura B2C, não MQA; MQA diferente de SQA | Achado 1; camada de conta (4.2) |
| Medir prefeituras acima de 15 mil; ICP; clusterizar contas | A0 com tiers (4.2); sinais públicos (2.6) |
| Só entraria outro GOV se engajado; qual a relevância do GOV UF | decidir se governo estadual é ICP próprio ou canal (convênios, consórcios); seção 10 |
| Intermediar contatos para chegar ao SQL; construir confiança | A2 exige duas pessoas; C5 e prefeituras clientes como ponte |
| Como medir interação; critérios para demos agendadas; no show | critérios de saída de A3 e O1; primeira reunião é diagnóstico |
| SQL é diferente de tomador de decisão; champions; BANT/SPIN/MEDDPICC | scorecard (seção 5): E e C1 separados; SPIN como técnica |
| Descobrir momento de compra ideal; urgência na dor | evento crítico e elemento G (achado 5) |
| Níveis decisórios: tech/geo, jurídico, quem paga, quem assina | papéis do grupo comprador (seção 5) |
| Como se aproximar do gabinete | E e I no nível 3 exigem gabinete; o workshop e o kit do comitê são a ponte |
| Como trabalhar com o comitê de parceria (não obrigatório) | O3 com nomeação formal e plano de trabalho (2.5) |
| Quais docs de inex enviar em cada etapa | dossiê de contratação (O4 e O5; seção 6) |
| Manter o comitê engajado na negociação e na fase jurídica | plano de trabalho conjunto; ponto focal em O5 |
| Medir proposta, negociação, pipeline, deal | categorias de forecast (achado 3) e conversão por coorte (seção 7) |
| Previsibilidade da data de fechamento | data derivada do plano de trabalho, não da intuição do vendedor |
| Usar fechamento como capital político | comunicado conjunto institucional, aprovado pela Secom, fora do período eleitoral (DE-02, P2) |
| Antecipar kickoff e informações para tech e data | kickoff agendado em O6; linha de base em C1 |
| Portal do cliente, trilha de relacionamento, encantamento | C1 a C5 (4.4) e seção 6 |

---

## 9. O que compete e o que não compete ao nosso público e produto

| Prática enterprise | Aplica? | Por quê | Adaptação para a OSPA Place |
|---|---|---|---|
| Funil centrado em conta e grupo comprador (Forrester) | **Sim** | prefeitura compra em comitê | três camadas: conta, oportunidade, grupo |
| Critérios de saída com evidência do comprador | **Sim** | resolve forecast e deal aging | seção 4 |
| MEDDPICC como linguagem comum | **Sim, adaptado** | Paper process é o rito público | scorecard com G (seção 5) |
| Mutual action plan | **Sim, forte** | linguagem nativa de "plano de trabalho" | Plano de Trabalho da Parceria |
| Buyer enablement | **Sim, forte** | o maior atrito é o processo administrativo | dossiê de contratação e kit do comitê |
| Bowtie (pós venda como funil) | **Sim, adaptado** | renovação e expansão seguem regras contratuais | C1 a C5; expansão por aditivo, secretarias e vizinhos |
| SPICED, evento crítico | **Sim, forte** | calendário público e previsível | elemento G; janela de 2027 |
| Dados de intenção de terceiros (6sense, Bombora) | **Não** | não cobrem prefeituras brasileiras | sinais públicos (PNCP, diário oficial, LOA, câmara) |
| BANT | **Não** | orçamento e prazo são documentos públicos, não perguntas | substituído por P e G |
| Descontos de fim de trimestre e urgência criada pelo vendedor | **Não** | o rito não acelera por pressão comercial; prejudica a relação | urgência vem do calendário da prefeitura |
| POC ou piloto gratuito | **Com cautela** | entregar serviço sem contrato a um ente público pode gerar questionamento | CPSI como piloto formal; validar com jurídico |
| Venda sem vendedor e autosserviço (Gartner, 67%) | **Parcial** | a contratação exige interação formal | autoeducação forte no topo: cases, demo gravada, faixa de preço, calculadora de impacto |
| Benchmarks numéricos de SaaS privado | **Só como ordem de grandeza** | outro mercado, outro ciclo | calibrar SLAs e metas com o histórico próprio |
| Influenciar requisitos antes do edital | **Com cautela** | limite entre contribuição técnica e direcionamento | informar, apoiar consulta pública, nunca redigir requisito restritivo |

---

## 10. Tabela de decisão

| # | Proposta | Prioridade | Decisão (aprovar / ajustar / descartar) | Observação |
|---|---|---|---|---|
| V1 | Separar conta, oportunidade e grupo comprador no CRM | Alta | | exige revisão da configuração do RD |
| V2 | Reescrever marcos como critérios de saída com evidência | Alta | | seção 4 como base |
| V3 | Pipeline a partir de O2 e categorias de forecast | Alta | | muda indicadores atuais |
| V4 | Rota de contratação e fonte de recurso como critério de O4 | Alta | | validar rotas com jurídico |
| V5 | Evento crítico obrigatório em toda oportunidade | Alta | | priorizar janela de 2027 |
| V6 | Ganho = empenho emitido | Média | | |
| V7 | Scorecard MEDDPICC + G no lugar dos 20 pts | Média | | calibrar mínimos |
| V8 | Plano de Trabalho da Parceria | Alta | | |
| V9 | Dossiê de contratação por rota | Alta | | validar com jurídico |
| V10 | Etapas C1 a C5 no CS | Média | | conecta com DE-02, P1 e P4 |
| V11 | Status "em espera" com data de reativação | Média | | |
| V12 | SLAs por etapa calibrados com histórico | Média | | levantar dados dos últimos 18 meses |

## 11. Pontos em aberto

1. **Ticket e rota predominante:** qual o valor médio de contrato e qual a proporção de negócios por inexigibilidade, CPSI, ata e licitação? Isso muda o peso do dossiê de contratação e os SLAs.
2. **Como os 20 pontos são calculados hoje?** Vale mapear o score atual para o scorecard da seção 5 antes de trocar, para não perder histórico.
3. **Governo estadual:** é ICP próprio, canal para chegar às prefeituras, ou fora do escopo?
4. **Comitê de parceria:** a prefeitura já formaliza o comitê (portaria, ofício, e mail) ou ele é informal? A proposta de O3 depende disso.
5. **CRM:** o RD Station CRM suporta conta, oportunidade e papéis do grupo comprador, ou a mudança exige outra ferramenta?
6. **Histórico:** existem dados de datas por etapa nos negócios ganhos e perdidos para calibrar SLAs e pipeline coverage?

## Fontes

- [Gartner, The B2B Buying Journey](https://www.gartner.com/en/sales/insights/b2b-buying-journey)
- [Growth Method, Gartner's 6-stage framework](https://growthmethod.com/gartner-b2b-buying-journey/)
- [Gartner, 74% of B2B buyer teams demonstrate unhealthy conflict (2025)](https://www.gartner.com/en/newsroom/press-releases/2025-05-07-gartner-sales-survey-finds-74-percent-of-b2b-buyer-teams-demonstrate-unhealthy-conflict-during-the-decision-process)
- [Gartner, 67% of B2B buyers prefer a rep-free experience (2026)](https://www.gartner.com/en/newsroom/press-releases/2026-03-09-gartner-sales-survey-finds-67-percent-of-b2b-buyers-prefer-a-rep-free-experience)
- [Gartner, Marketing's Role in Buyer Enablement](https://www.gartner.com/en/marketing/insights/articles/marketings-role-in-buyer-enablement)
- [Intentsify, How B2B Buying Groups Are Evolving](https://intentsify.io/blog/how-b2b-buying-groups-are-evolving/)
- [Forrester, Put the B2B Revenue Waterfall into practice](https://www.forrester.com/b2b-marketing/b2b-revenue-waterfall-guide/)
- [Forrester, Demand program plays and buying groups](https://www.forrester.com/blogs/demand-program-plays-get-and-move-buying-group-members-through-the-waterfall)
- [Full Circle Insights, Forrester's B2B Revenue and ABM measurement](https://www.fullcircleinsights.com/resource/forresters-b2b-revenue-abm-measurement)
- [LeanData, B2B Revenue Waterfall transformation](https://www.leandata.com/blog/your-cheat-sheet-for-b2b-revenue-waterfall-transformation/)
- [Axcient, B2B Revenue Waterfall](https://axcient.com/blog/demand-waterfall-8-ways-to-optimize-your-sales-cycle/)
- [Winning by Design, The Bowtie: A Proposed Standard](https://winningbydesign.com/wp-content/uploads/2026/02/The-Bowtie-A-Proposed-Standard.pdf)
- [RevPartners, From Bowtie to RPM](https://blog.revpartners.io/en/revops-articles/bowtie-funnel)
- [RevenueFlow, SPICED and the Bowtie](https://www.revenueflow.com/blog/winning-design-sales-methodology)
- [Digital Applied, Sales pipeline stage definitions](https://www.digitalapplied.com/blog/sales-pipeline-stage-definitions-2026-crm-framework)
- [Federico Presicci, Implementing MEDDPICC](https://federicopresicci.com/blog/sales-methodology/how-to-implement-the-meddpicc-sales-methodology/)
- [Highspot, Mutual action plan](https://www.highspot.com/blog/mutual-action-plan/)
- [Aviso, Mutual action plan](https://www.aviso.com/blog/mutual-action-plan)
- [Starbridge, SLED sales: build pipeline before the RFP](https://starbridge.ai/blog/sled-sales)
- [Civic IQ, 10 pre-RFP signals for B2G](https://blogs.civiciq.com/2026/05/07/10-pre-rfp-signals-every-b2g-sales-team-should-track-with-real-examples/)
- [SaasDash, GovTech SaaS procurement cycles](https://saasdash.ai/blog/govtech-saas-procurement-sales-cycle)
- [HBR, The B2B Elements of Value](https://hbr.org/2018/03/the-b2b-elements-of-value)
- [Bain, B2B Elements of Value interactive](https://media.bain.com/b2b-eov/)
- [Gradient Works, 2025 B2B sales performance benchmarks (Ebsta e Pavilion)](https://www.gradient.works/blog/2025-b2b-sales-performance-benchmarks)
- [McKinsey, B2B Pulse 2024](https://www.mckinsey.com/capabilities/growth-marketing-and-sales/our-insights/five-fundamental-truths-how-b2b-winners-keep-growing)
- [AGU, Manual do Contrato Público para Solução Inovadora](https://www.gov.br/agu/pt-br/assuntos-1/labori/minutas/manual-do-contrato-publico-para-solucao-inovadora.pdf)
- [Vale Cursos, inexigibilidade e ETP para plataformas privadas](https://valecursoseconsultoria.com.br/blog/inexigibilidade-contratacao-plataformas-privadas/)
- Lei 14.133/2021 (arts. 23, 72, 74, 86, 125); LC 182/2021; LC 101/2000 (LRF), art. 42; Lei 9.504/1997, art. 73; Lei 10.257/2001 (Estatuto da Cidade), art. 40; Constituição Federal, art. 37, §1º
