# Automação de Tarefas Administrativas: como a tecnologia pode tornar processos mais eficientes

## 1. Contexto e objetivo

As atividades administrativas possuem diversas tarefas repetitivas que consomem tempo e podem estar sujeitas a erros quando realizadas manualmente.

A automação pode ser utilizada para executar ou apoiar essas atividades por meio de ferramentas tecnológicas, permitindo reduzir o trabalho manual, aumentar a padronização e melhorar a eficiência dos processos.

Este projeto foi desenvolvido como parte de um desafio da DIO, utilizando o NotebookLM como ferramenta de apoio à pesquisa, organização das informações e elaboração de um miniguia.

### Questão central

**Como ferramentas de automação e inteligência artificial podem otimizar tarefas administrativas repetitivas, reduzindo o trabalho manual e aumentando a produtividade?**

### Objetivos

* Compreender o conceito de automação de tarefas administrativas;
* Identificar características de atividades que podem ser boas candidatas à automação;
* Entender a importância de analisar e organizar um processo antes de automatizá-lo;
* Identificar benefícios, riscos e cuidados relacionados à automação;
* Utilizar técnicas de prompt engineering para obter informações mais específicas das fontes;
* Avaliar criticamente as respostas geradas pelo NotebookLM;
* Produzir um miniguia prático sobre o tema.

---

## 2. Curadoria das Fontes

Para desenvolver o estudo sobre automação de tarefas administrativas, foram selecionadas cinco fontes abertas em texto, relacionadas à automação de processos, eficiência operacional, padronização de atividades e identificação de tarefas que podem ser automatizadas.

As fontes foram utilizadas como base para as consultas realizadas no NotebookLM.

### 1. Thomson Reuters — Automação de processos administrativos

Material utilizado para compreender conceitos de automação, benefícios, riscos e a importância de analisar e otimizar um processo antes de escolher uma tecnologia.

Link: https://www.thomsonreuters.com.br/pt/conteudo/automacao-de-processos-administrativos.html

### 2. oHub Base Gestão — Automação de tarefas administrativas

Material utilizado principalmente para identificar características de tarefas que podem ser boas candidatas à automação, como repetitividade, frequência, regras claras e volume de trabalho.

Link: https://base.ohub.com.br/gestao/documental/rotinas-administrativas/artigos/automacao-de-tarefas-administrativas

### 3. Jornal Síndico — Tecnologia e automação nos processos de administração

Fonte complementar utilizada para compreender a relação entre tecnologia, automação e eficiência em processos administrativos.

Link: https://jornalsindico.com.br/noticias/tecnologia-e-automacao-nos-processos-de-administracao-revolucao-e-eficiencia

### 4. Substack — IA na automação de tarefas: eficiência

Fonte complementar utilizada para ampliar a análise sobre o uso de inteligência artificial na automação de tarefas.

Link: https://marshalmoricavalheiro.substack.com/p/ia-na-automacao-de-tarefas-eficiencia

### 5. Sebrae Paraná — Automatização de processos: rumo à eficiência e inovação

Fonte institucional utilizada como referência complementar sobre automatização de processos, produtividade, eficiência e inovação.

Link: https://www.sebraepr.com.br/comunidade/artigo/automatizacao-de-processos-rumo-a-eficiencia-e-inovacao

### Critério de seleção

As fontes foram escolhidas por apresentarem conteúdos relacionados diretamente ao tema estudado e por estarem disponíveis em formato aberto na internet.

Durante os testes no NotebookLM, as respostas foram solicitadas com base exclusivamente nas fontes selecionadas. Quando surgiram critérios muito específicos, números ou conclusões apresentadas de forma categórica, foram realizados novos testes para verificar como essas informações estavam sendo interpretadas pela ferramenta. Esse processo ajudou a identificar limitações e aperfeiçoar os prompts utilizados.

---

## 3. Uso do NotebookLM

O NotebookLM foi utilizado como ferramenta de apoio à pesquisa.

As fontes selecionadas foram adicionadas ao notebook e os prompts foram elaborados de forma progressiva.

A estratégia utilizada foi começar com uma pergunta mais ampla e, posteriormente, criar perguntas mais específicas para:

1. compreender o conceito;
2. identificar critérios;
3. comparar abordagens;
4. transformar informações em um checklist;
5. verificar se determinadas afirmações estavam realmente apoiadas pelas fontes.

Essa abordagem permitiu observar como diferentes formas de elaborar um prompt podem alterar o nível de detalhamento e a estrutura da resposta.

---

## 4. Prompt Engineering e testes realizados

## Prompt 1 — Síntese inicial

### Objetivo

Compreender o conceito de automação de tarefas administrativas, suas aplicações, benefícios e cuidados.

### Prompt utilizado

> Com base exclusivamente nas fontes deste notebook, explique o que é automação de tarefas administrativas e qual é sua importância para as organizações. Apresente uma síntese em linguagem simples, destacando:
>
> 1. O que é automação de tarefas administrativas;
> 2. Quais tarefas administrativas podem ser automatizadas;
> 3. Quais benefícios a automação pode trazer;
> 4. Quais riscos ou cuidados devem ser considerados antes de automatizar um processo;
> 5. Qual é a relação entre automação, produtividade e redução de erros.
>
> Ao responder, indique quais fontes sustentam cada ponto apresentado. Não utilize informações que não estejam nas fontes.

### Resultado

O NotebookLM apresentou uma visão geral sobre automação, incluindo tarefas repetitivas, benefícios, redução de erros, padronização e cuidados antes da implementação.

A resposta foi útil como ponto de partida, mas apresentou muitos exemplos diferentes. Por isso, os prompts seguintes foram utilizados para aprofundar pontos específicos.

---

## Prompt 2 — Critérios para identificar tarefas automatizáveis

### Objetivo

Identificar características que tornam uma tarefa administrativa uma boa candidata à automação.

### Prompt utilizado

> Considerando as fontes deste notebook, quais características uma tarefa administrativa deve ter para ser uma boa candidata à automação? Crie uma lista de critérios objetivos que possam ser usados para avaliar uma tarefa antes de decidir automatizá-la. Para cada critério, explique brevemente o motivo. No final, dê 3 exemplos de tarefas que atendem a esses critérios e 2 exemplos de tarefas que não seriam boas candidatas à automação. Baseie a resposta exclusivamente nas fontes e indique as fontes utilizadas.

### Resultado

Foram identificados critérios como:

* repetitividade;
* frequência;
* existência de regras claras;
* possibilidade de padronização;
* volume de trabalho;
* risco de erros;
* pouca necessidade de julgamento subjetivo;
* quantidade de exceções.

Durante esse teste surgiu o critério de **“mais de 30 minutos por ciclo”**. Como esse tipo de informação é muito específico, foi necessário realizar uma nova consulta para verificar sua origem.

---

## Prompt 3 — Processo antes da ferramenta

### Objetivo

Verificar se é mais adequado escolher primeiro uma ferramenta ou analisar o processo antes de decidir pela automação.

### Prompt utilizado

> Com base exclusivamente nas fontes deste notebook, compare estas duas abordagens:
>
> A) Escolher uma ferramenta de automação e depois adaptar o processo a ela.
>
> B) Primeiro analisar, mapear e padronizar o processo e somente depois decidir o que e como automatizar.
>
> Explique:
>
> * qual abordagem é mais recomendada pelas fontes;
> * por quê;
> * quais problemas podem acontecer quando uma empresa automatiza um processo sem analisá-lo previamente;
> * qual seria um passo a passo básico para preparar um processo antes da automação.
>
> Apresente a resposta em uma tabela comparativa e depois faça uma conclusão curta. Utilize somente informações presentes nas fontes e indique as fontes utilizadas.

### Resultado

A resposta indicou que as fontes valorizam a análise do processo antes da escolha da tecnologia.

O principal aprendizado foi que automatizar um processo sem antes compreender seus problemas pode fazer com que as falhas existentes sejam apenas reproduzidas de forma mais rápida.

### Cicatriz identificada

O NotebookLM utilizou expressões muito categóricas, como:

* “única abordagem recomendada”;
* “sequência obrigatória”;
* “fundamentalmente errônea”.

Embora a ideia geral estivesse relacionada às fontes, a forma de apresentar a conclusão poderia ser mais forte do que aquilo que era necessário afirmar.

---

## Prompt 4 — Criação de checklist

### Objetivo

Transformar os critérios encontrados em uma ferramenta prática de avaliação.

### Prompt utilizado

> Com base exclusivamente nas fontes deste notebook, crie um checklist simples para avaliar se uma tarefa administrativa é uma boa candidata à automação.
>
> Para cada item, use uma pergunta que possa ser respondida com Sim ou Não.
>
> Considere aspectos como:
>
> * frequência da tarefa;
> * repetitividade;
> * existência de regras claras;
> * necessidade de julgamento humano;
> * volume de trabalho;
> * risco de erros;
> * possibilidade de padronização;
> * existência de muitas exceções.
>
> Depois do checklist, explique como interpretar o resultado, mas não estabeleça uma pontuação ou número mínimo de respostas positivas que não esteja explicitamente presente nas fontes.
>
> Dê também um exemplo fictício de aplicação do checklist a uma tarefa administrativa.
>
> Utilize somente informações das fontes e indique quais fontes foram utilizadas.

### Resultado

O prompt gerou um checklist com perguntas relacionadas à frequência, repetitividade, regras, padronização, julgamento humano, volume, erros e exceções.

Também foi criado um exemplo fictício de aplicação do checklist a uma tarefa administrativa.

### Cicatriz identificada

Mesmo após solicitar que não fossem criadas regras ou números que não estivessem nas fontes, o critério de “mais de 30 minutos por ciclo” apareceu novamente.

Isso mostrou a importância de verificar não apenas se a resposta atende ao formato solicitado, mas também se cada informação está realmente apoiada pelas fontes.

---

## Prompt 5 — Validação das respostas

### Objetivo

Verificar se afirmações apresentadas nos testes anteriores estavam diretamente sustentadas pelas fontes ou se eram interpretações.

### Prompt utilizado

> Analise as respostas anteriores deste notebook e identifique quais afirmações parecem ser conclusões diretamente sustentadas pelas fontes e quais parecem ser interpretações ou generalizações feitas a partir delas.
>
> Dê atenção especial aos seguintes pontos:
>
> 1. O critério de “mais de 30 minutos por ciclo”;
> 2. A ideia de que uma tarefa com baixo volume não justificaria automação;
> 3. A afirmação de que um processo sem padronização “não deve ser automatizado”;
> 4. A afirmação de que é necessário padronizar e documentar o processo antes de automatizá-lo.
>
> Para cada ponto, classifique como:
>
> * Diretamente sustentado pelas fontes;
> * Parcialmente sustentado pelas fontes;
> * Interpretação ou generalização.
>
> Explique brevemente o motivo e indique quais fontes sustentam a classificação.
>
> Não crie novos critérios, números ou regras. Utilize somente informações presentes nas fontes deste notebook.

### Resultado

O NotebookLM classificou os pontos analisados como diretamente sustentados pelas fontes.

Entretanto, esse teste trouxe outro aprendizado importante: o próprio NotebookLM estava sendo utilizado para validar respostas que ele mesmo havia produzido anteriormente.

Por isso, a validação feita pelo modelo não deve ser considerada uma comprovação independente. A análise das fontes originais continua sendo necessária.

---

## 5. Cicatrizes e aprendizados

Durante os testes foram identificados alguns pontos importantes sobre o uso de inteligência artificial para pesquisa.

| Teste    | O que funcionou                        | Cicatriz                                                   | Aprendizado                                              |
| -------- | -------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------- |
| Prompt 1 | Produziu uma visão geral organizada    | Resposta ampla e com muitos exemplos                       | Perguntas posteriores devem ser mais específicas         |
| Prompt 2 | Identificou critérios para automação   | Surgiu o critério de 30 minutos por ciclo                  | Critérios muito específicos precisam ser verificados     |
| Prompt 3 | Comparou processo e tecnologia         | Utilizou conclusões muito categóricas                      | A resposta pode exagerar uma conclusão das fontes        |
| Prompt 4 | Transformou critérios em checklist     | O critério de 30 minutos apareceu novamente                | É necessário controlar informações não solicitadas       |
| Prompt 5 | Tentou validar as respostas anteriores | O modelo validou respostas que ele próprio havia produzido | A validação da IA não substitui a conferência das fontes |

### Principal aprendizado

Durante os testes, percebeu-se que o NotebookLM pode transformar informações encontradas nas fontes em critérios ou regras aparentemente mais rígidos.

Por isso, foi necessário refinar os prompts e realizar uma etapa de validação das respostas.

Também foi possível perceber que uma resposta bem organizada e convincente não significa necessariamente que todas as suas conclusões estejam apresentadas exatamente da mesma forma nas fontes originais.

---

## 6. Miniguia final

## Automação de Tarefas Administrativas

### 6.1 O que é automação?

Automação de tarefas administrativas é o uso de tecnologias para executar, total ou parcialmente, atividades que anteriormente dependiam de execução manual.

Ela pode ser aplicada, por exemplo, para:

* organizar informações;
* preencher ou transferir dados;
* gerar documentos;
* enviar notificações;
* controlar prazos;
* organizar e classificar informações;
* realizar verificações repetitivas;
* gerar relatórios a partir de dados estruturados.

O objetivo não é simplesmente utilizar uma ferramenta, mas tornar o processo mais eficiente, reduzindo trabalho manual, retrabalho e possibilidade de erros.

---

## 6.2 Antes de automatizar: analise o processo

Uma das principais conclusões do estudo é que a automação não deve começar simplesmente pela escolha de uma ferramenta.

Antes disso, é importante compreender como o processo funciona atualmente.

### Fluxo recomendado

**Analisar → Mapear → Identificar problemas → Padronizar → Documentar → Automatizar → Monitorar**

É necessário observar:

* quais etapas existem;
* quais são repetitivas;
* onde acontecem erros;
* quais etapas geram atrasos;
* quais atividades não agregam valor;
* quais regras precisam ser seguidas;
* quais situações são exceções;
* quais etapas dependem de julgamento humano.

Automatizar um processo desorganizado pode fazer com que os problemas existentes sejam reproduzidos de maneira mais rápida.

---

## 6.3 Checklist para avaliar uma tarefa

Antes de automatizar uma tarefa, é possível fazer as seguintes perguntas:

* A tarefa acontece com frequência?
* Os passos são repetitivos?
* Existem regras claras para sua execução?
* O processo pode ser padronizado?
* A atividade pode ser executada sem julgamento subjetivo?
* Existe um volume significativo de trabalho?
* Os erros manuais podem causar problemas relevantes?
* Existem poucas exceções?
* As regras podem ser documentadas?

Quanto mais características estiverem presentes, maior pode ser o potencial da tarefa para automação.

Esse checklist não deve ser tratado como uma fórmula matemática. A decisão deve considerar o processo como um todo, seus objetivos e seus resultados esperados.

---

## 6.4 Exemplos de tarefas que podem ser automatizadas

Dependendo das características do processo, alguns exemplos são:

* envio de lembretes de prazos;
* geração de documentos recorrentes;
* organização e classificação de informações;
* transferência de dados entre sistemas;
* verificações repetitivas;
* controles de vencimentos;
* geração de relatórios a partir de dados estruturados.

Cada tarefa deve ser analisada individualmente antes da automação.

---

## 6.5 Quando é necessário ter mais cuidado

Nem toda atividade administrativa deve ser totalmente automatizada.

É necessário ter atenção especial quando a tarefa envolve:

* julgamento subjetivo;
* negociação;
* interpretação de situações específicas;
* tomada de decisão baseada em contexto;
* muitas exceções;
* informações que exigem análise humana.

Nesses casos, uma abordagem com participação humana pode ser mais adequada.

Esse modelo é conhecido como **human-in-the-loop**, no qual a tecnologia executa ou apoia parte do processo, mas uma pessoa permanece responsável por determinadas análises ou decisões.

---

## 6.6 Benefícios da automação

A automação pode contribuir para:

* reduzir trabalho manual;
* diminuir erros;
* reduzir retrabalho;
* aumentar a velocidade de execução;
* melhorar a padronização;
* organizar melhor as informações;
* aumentar a produtividade;
* melhorar a rastreabilidade;
* facilitar o acompanhamento dos processos;
* permitir que as pessoas dediquem mais tempo a atividades de maior valor.

O retorno de uma automação não deve ser avaliado apenas pela redução de custos.

Também podem ser considerados aspectos como qualidade, velocidade, controle, conformidade, experiência e redução de riscos.

---

## 6.7 Cuidados antes da implementação

Um processo de automação pode seguir algumas etapas básicas:

1. Entender o processo atual;
2. Identificar problemas e gargalos;
3. Eliminar etapas desnecessárias;
4. Padronizar o processo;
5. Documentar regras e procedimentos;
6. Definir o resultado esperado;
7. Escolher uma tecnologia compatível;
8. Realizar testes;
9. Acompanhar os resultados;
10. Fazer ajustes quando necessário.

Além disso, é importante considerar treinamento, segurança das informações, governança e acompanhamento humano quando necessário.

---

## 7. Glossário

**Automação:** utilização de tecnologia para executar tarefas ou etapas de um processo com menor necessidade de intervenção manual.

**RPA (Robotic Process Automation):** tecnologia utilizada para automatizar ações repetitivas e baseadas em regras, reproduzindo atividades realizadas por usuários em sistemas.

**BPM (Business Process Management):** abordagem voltada ao gerenciamento, organização, análise e melhoria dos processos de negócio.

**Padronização:** definição de uma forma organizada e consistente para realizar uma atividade.

**POP (Procedimento Operacional Padrão):** documento que descreve como determinada atividade deve ser realizada.

**Gargalo:** etapa de um processo que limita ou reduz o fluxo de trabalho.

**Human-in-the-loop:** modelo em que a tecnologia participa da execução do processo, mas determinadas decisões ou validações continuam sob responsabilidade humana.

**KPI (Key Performance Indicator):** indicador utilizado para acompanhar o desempenho e os resultados de um processo.

---

## 8. Prompts reutilizáveis

Os prompts abaixo podem ser utilizados em outros estudos sobre processos e automação.

### Prompt para entender um processo

> Com base exclusivamente nas fontes fornecidas, explique como funciona o processo [NOME DO PROCESSO]. Identifique suas principais etapas, possíveis dificuldades e atividades repetitivas. Indique quais fontes sustentam cada informação.

### Prompt para avaliar uma tarefa

> Com base exclusivamente nas fontes fornecidas, avalie se a tarefa [DESCREVER TAREFA] possui características de uma boa candidata à automação. Analise frequência, repetitividade, regras, padronização, volume, necessidade de julgamento humano, risco de erros e quantidade de exceções. Não crie critérios que não estejam presentes nas fontes.

### Prompt para identificar riscos

> Com base exclusivamente nas fontes fornecidas, identifique os principais riscos e cuidados relacionados à automação da tarefa [DESCREVER TAREFA]. Separe os riscos relacionados ao processo, às pessoas e à tecnologia e indique as fontes utilizadas.

### Prompt para validar uma afirmação

> Verifique nas fontes fornecidas se a afirmação “[INSERIR AFIRMAÇÃO]” está diretamente sustentada pelo conteúdo. Classifique como diretamente sustentada, parcialmente sustentada ou interpretação/generalização. Explique o motivo e indique as fontes relacionadas. Não crie novas informações.

---

## 9. Conclusão

A automação de tarefas administrativas pode contribuir para tornar processos mais rápidos, padronizados e eficientes, principalmente quando aplicada a atividades repetitivas, baseadas em regras e com volume significativo de trabalho.

Entretanto, o estudo mostrou que automatizar não significa simplesmente escolher uma ferramenta tecnológica.

Antes da automação, é necessário compreender o processo, identificar problemas, eliminar etapas desnecessárias, padronizar as atividades e definir o que se espera alcançar.

O uso do NotebookLM também demonstrou a importância de uma boa elaboração de prompts. Perguntas mais específicas ajudaram a transformar uma pesquisa ampla em critérios, comparações, checklists e validações.

Ao mesmo tempo, os testes mostraram que a inteligência artificial pode apresentar conclusões de maneira mais categórica do que as fontes originais. Por isso, a análise crítica e a conferência das informações continuam sendo importantes.

### Principal conclusão do projeto

**A tecnologia pode automatizar tarefas, mas a eficiência depende primeiro de compreender e organizar o processo que será automatizado.**

---

## 10. Ferramentas utilizadas

* **NotebookLM:** organização das fontes, pesquisa orientada por documentos e testes de prompts.
* **GitHub:** organização e publicação do projeto.
* **Markdown:** estruturação do README e documentação do projeto.

---

## 11. Estrutura do projeto

```text
automacao-tarefas-administrativas/
└── README.md
```

---

## 12. Sobre o projeto

Projeto desenvolvido como parte de um desafio da **DIO**, com foco em pesquisa, curadoria de fontes, prompt engineering e utilização de inteligência artificial como ferramenta de apoio ao estudo.

**Tema:** Automação de Tarefas Administrativas

**Questão central:** Como ferramentas de automação e inteligência artificial podem otimizar tarefas administrativas repetitivas, reduzindo o trabalho manual e aumentando a produtividade?



