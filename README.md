# Engenharia de Prompts com NotebookLM

Projeto desenvolvido como parte do desafio da DIO utilizando o NotebookLM para estudar Engenharia de Prompts por meio de aprendizagem ativa, curadoria de fontes e experimentação de prompts.

## 📖 Contexto

Engenharia de Prompts se tornou uma habilidade essencial para profissionais, principalmente aos que utilizam modelos de linguagem de grande porte (Large Language Models – LLMs). Com a evolução da IA, não basta apenas usar essas ferramentas de qualquer maneira. É necessário saber formular instruções claras, fornecer contexto adequado e estruturar solicitações capazes de produzir respostas mais precisas e úteis. Portanto, foi utilizado o NotebookLM como ferramenta de aprendizagem ativa, organizando materiais de estudo e explorando técnicas de criação de prompts.

## 🎯 Objetivos

Este projeto teve o objetivo de:

* compreender os fundamentos da Engenharia de Prompts
* estudar as diversas técnicas utilizadas na criação de prompts
* utilizar o NotebookLM como ferramenta de aprendizagem
* criar um miniguia para futuras revisões

## 📚 Curadoria de fontes

A escolha das fontes foi fundamentada na qualidade e na confiabilidade. Foram utilizados livros amplamente consolidados na comunidade acadêmica e frequentemente empregados como base para o treinamento de IA, desde conceitos básicos até avançados, com fundamentos bem estabelecidos. Também foram selecionados vídeos de profissionais experientes e reconhecidos no mercado, tanto em português quanto em inglês, todos voltados à engenharia de IA e de prompts. A escolha dos livros como base teórica complementa os vídeos, que apresentam uma abordagem mais prática.

### 📘 Livros

1. **AI Engineering — Chip Huyen:** utilizado como base teórica para construção e funcionamento de sistemas de IA, com foco em aplicação moderna de LLMs.
2. **Prompt Engineering for LLMs — John Berryman & Albert Ziegler:** utilizado pela sua abordagem sobre técnicas de engenharia de prompt e interação com os modelos de linguagem.

### 🎥 Vídeos

1. **AI Prompt Engineering: A Deep Dive:** utilizado pelo conteúdo aprofundado sobre técnicas e estratégias de criação de prompts eficazes.
2. **Engenharia de Prompt: O Guia Definitivo:** apresenta uma visão moderna e prática sobre fundamentos e aplicações da Engenharia de Prompt.
3. **Prompt Engineering Full Course (2026) — Master ChatGPT, Gemini...:** utilizado por ser um curso completo com usos práticos e aplicações com diferentes modelos de IA.

## 🚀 Processo de aprendizagem

O estudo foi estruturado em três níveis progressivos, permitindo comparar a profundidade das respostas da IA conforme a complexidade das perguntas aumentava.

Iniciando pelos fundamentos da Engenharia de Prompts, os estudos evoluíram para técnicas específicas (Zero-shot, Few-shot, frameworks, organização com XML, mitigação de alucinações e avaliação de eficiência). Essa progressão permitiu compreender não apenas como escrever prompts melhores, mas também suas limitações e aplicações em cenários reais.

### 🟢 Perguntas Fundamentais

* O que é Engenharia de Prompts?
* Por que ela é importante?
* Quais conceitos preciso aprender?

---

### 🟡 Perguntas de Aprofundamento

* O que é Zero-shot e quando usar?
* O que é Few-shot e quando usar?
* Como funciona o Role Prompting?
* O que é Chain of Thought?
* Como usar Tags XML em prompts?
* O que são variáveis e templates em prompts?

---

### 🔴 Perguntas Avançadas

* Como evitar alucinações?
* Como avaliar a qualidade de um prompt?
* Quais são as limitações da Engenharia de Prompts?
* O que é o Desafio da Última Milha?
* Qual a diferença entre o Framework CRAFT e PROMPT?
* Como combinar múltiplas técnicas?

---

## 🩹 Cicatrizes

Essa seção apresenta as dificuldades reais encontradas durante o processo e como elas foram superadas.

No primeiro momento, foram feitas perguntas genéricas, o que resultava em respostas longas e com diversos termos que eu ainda não conhecia. Ao longo dos estudos, percebi que era mais eficiente solicitar que a IA definisse esses conceitos antes de prosseguir para assuntos mais avançados.

Após a aprendizagem desses termos, passei a perguntar aplicações práticas da Engenharia de Prompts, pedindo comparações entre prompts bons e prompts ruins. Esse processo me permitiu compreender como pequenas mudanças na formulação de um prompt podem influenciar a qualidade das respostas.

Outro aprendizado importante foram as técnicas de prompts que são comuns em todas as fontes, como Few-shot Prompting, Chain of Thought, Role Prompting e o uso de tags XML. A recorrência desses conceitos me fez perceber a sua importância na elaboração de prompts mais claros e eficientes.

Também compreendi a necessidade de impor limitações quando a pergunta envolve assuntos incertos. Em um dos testes, por exemplo, perguntei como seria o mercado de programação no futuro. Com esse prompt, percebi a importância de orientar o modelo a informar quando não possui informações suficientes para responder, assim reduzindo os riscos de alucinações (características pertencentes aos modelos probabilísticos).

Portanto, o uso do NotebookLM se mostrou como ferramenta de alto rendimento, pois, além de organizar e consultar rapidamente as fontes selecionadas, me permitiu sanar grandes e pequenas dúvidas, reduzindo o tempo necessário para localizar informações em materiais extensos, como livros e artigos.

# 📖 Miniguia de Estudo

## 📑 Resumo Estruturado

Engenharia de Prompt é a ciência de elaborar prompts e contextos para orientar o comportamento de modelos de linguagem (LLMs) com o intuito de obter melhores respostas sem alterar os pesos internos do modelo. Define-se pelos estudiosos como uma "meta-habilidade", porque serve como base para desbloquear e potencializar as ferramentas de IA. A regra de ouro dessa área do conhecimento é: se uma instrução não for clara o suficiente para um humano inteligente realizar a tarefa, provavelmente também não será para o modelo de IA. Ela é baseada em princípios críticos, como Garbage In, Garbage Out; baseada em técnicas essenciais de prompt, como Zero-shot, Few-shot e Chain of Thought; baseada em modos de organização (frameworks), como CRAFT, PROMPT, Markdown e tags XML; e baseada em pilares como as limitações pelo banco de dados do modelo e as alucinações, que são inevitáveis em modelos probabilísticos.

## 📚 Glossário

| Termo | Definição |
|--------|-----------|
| Engenharia de Prompts | Área dedicada ao desenvolvimento, teste e aperfeiçoamento de instruções para obter respostas mais precisas, úteis e confiáveis de modelos de IA. |
| Prompt | Instrução ou conjunto de instruções fornecidas a um modelo de IA para executar uma tarefa específica. |
| LLM (Large Language Model) | Modelo de linguagem treinado com grandes volumes de dados textuais, capaz de compreender e gerar linguagem natural. |
| Zero-shot Prompting| Técnica em que a IA recebe apenas a tarefa, sem exemplos prévios. |
| One-shot Prompting | Técnica que apresenta um único exemplo antes da tarefa para orientar a resposta esperada. |
| Few-shot Prompting | Técnica que utiliza alguns exemplos para ensinar ao modelo o padrão de resposta desejado. |
| Role Prompting | Estratégia que atribui um papel específico à IA (como professor, programador ou especialista) para influenciar seu comportamento e estilo de resposta. |
| Chain of Thought (CoT) | Técnica que incentiva o modelo a desenvolver o raciocínio passo a passo antes de fornecer a resposta final. |
| Tags XML | Estrutura utilizada para organizar prompts em blocos, separando contexto, instruções, exemplos e restrições, facilitando a interpretação pelo modelo. |
| Framework CRAFT | Framework para construção de prompts baseado nos elementos: Context, Role, Action, Format e Target Audience, ajudando a produzir instruções mais completas e organizadas. |
| Framework PROMPT | Framework que organiza a elaboração de prompts em etapas, auxiliando na definição clara do problema, do contexto, das restrições e do resultado esperado. |
| Alucinação (Hallucination) | Fenômeno em que o modelo gera informações incorretas, inventadas ou sem suporte nas fontes disponíveis. |
| Modelo Probabilístico | Modelo que produz respostas com base em probabilidades aprendidas durante o treinamento, e não por conhecimento absoluto ou verificação em tempo real. |
| Restrições | Limitações ou regras definidas no prompt para controlar o comportamento e o formato da resposta da IA. |
| Garbage In, Garbage Out (GIGO) | Princípio que afirma que a qualidade da resposta da IA depende diretamente da qualidade da entrada (prompt). Instruções vagas, incompletas ou incorretas tendem a gerar respostas de baixa qualidade, enquanto prompts claros, contextualizados e bem estruturados produzem resultados mais precisos. |

---

## 📝 Prompts Reutilizáveis


```text
Você é o Professor Algoritmo, um especialista sênior em Inteligência Artificial
  com 15 anos de experiência em ensinar engenharia de prompts para iniciantes.
  Seu estilo é didático, direto e usa analogias do mundo real para explicar
  conceitos técnicos. Você nunca usa jargões sem antes explicá-los.



  O estudante está iniciando seus estudos em engenharia de prompts e precisa
  compreender os fundamentos da disciplina e suas principais técnicas de forma
  clara e progressiva, do básico ao avançado.



 Explique o que é engenharia de prompts e suas principais técnicas seguindo
  rigorosamente a estrutura abaixo. Pense passo a passo antes de responder.
  Apresente os conceitos em ordem crescente de complexidade.



  ## O que é engenharia de prompts
  [Definição em até 3 parágrafos com analogia do mundo real]

  ## Por que ela é importante
  [3 razões objetivas, cada uma em 2 linhas]

  ## Principais técnicas

  ### 1. Zero-shot prompting
  [Definição + exemplo prático]

  ### 2. Few-shot prompting
  [Definição + exemplo prático]

  ### 3. Role prompting
  [Definição + exemplo prático]

  ### 4. Chain of Thought (CoT)
  [Definição + exemplo prático]

  ### 5. Uso de tags XML
  [Definição + exemplo prático]

  ## Resumo visual
  [Tabela comparativa com: Técnica | Quando usar | Nível de complexidade]



  - Não use termos técnicos sem explicá-los antes
  - Não ultrapasse 600 palavras no total
  - Não sugira perguntas ao final da resposta
  - Se não tiver certeza sobre alguma informação, diga explicitamente
  - Não use introduções como "Claro!" ou "Ótima pergunta!"

```

```text
Você é a Dra. Avalia, uma engenheira de prompts sênior especializada em
  auditoria e otimização de instruções para modelos de linguagem (LLMs).
  Você é analítica, precisa e sempre justifica cada ponto da sua avaliação
  com base em critérios técnicos reconhecidos da área.



  O usuário vai fornecer um prompt que deseja avaliar. Sua tarefa é analisá-lo
  de forma estruturada, identificando pontos fortes, falhas críticas e
  sugerindo uma versão melhorada com base nas boas práticas de engenharia
  de prompts.



  {{COLE_O_PROMPT_AQUI}}



  Avalie o prompt nos seguintes critérios, atribuindo uma nota de 0 a 10
  para cada um:

  1. Clareza — as instruções são compreensíveis para um humano?
  2. Contexto — há informações suficientes para a IA executar a tarefa?
  3. Persona — há um papel definido para o modelo?
  4. Formato — o formato de saída está especificado?
  5. Restrições — há guardrails definindo o que o modelo não deve fazer?
  6. Robustez — o prompt resistiria a entradas inesperadas ou ruidosas?



  Pense passo a passo antes de avaliar. Para cada critério, analise
  individualmente e só então calcule a nota final. Siga rigorosamente
  o formato de saída abaixo.



  ## Avaliação do prompt

  ### Pontos fortes
  [Liste até 3 pontos positivos identificados]

  ### Falhas críticas
  [Liste até 3 problemas que comprometem a qualidade]

  ### Notas por critério
  | Critério     | Nota (0-10) | Justificativa resumida       |
  |--------------|-------------|------------------------------|
  | Clareza      |             |                              |
  | Contexto     |             |                              |
  | Persona      |             |                              |
  | Formato      |             |                              |
  | Restrições   |             |                              |
  | Robustez     |             |                              |
  | **Média**    |             |                              |

  ### Versão otimizada
  [Reescreva o prompt aplicando as melhorias identificadas,
  usando tags XML e estrutura Markdown]

  ### O que foi corrigido
  [Liste as mudanças feitas e por que cada uma melhora o prompt]



  - Não invente problemas que não existem no prompt original
  - Se o prompt for muito curto para avaliar algum critério, atribua 0
    e explique o motivo
  - Não use introduções como "Claro!" ou "Com prazer!"
  - Não sugira perguntas ao final da resposta
  - Se não tiver certeza sobre algum critério, diga explicitamente

```

## ✅ Conclusão

Este projeto proporcionou aprendizados importantes para a minha formação profissional. Com a evolução da Inteligência Artificial, compreender os fundamentos e as técnicas da Engenharia de Prompts se tornou uma habilidade cada vez mais relevante. Ao longo dos estudos, aprofundei meus conhecimentos sobre conceitos fundamentais, técnicas de prompting, limitações dos modelos de IA, aspectos de segurança e ética, além de diferentes formas de estruturar prompts para obter respostas mais precisas e úteis.

O NotebookLM se mostrou uma ferramenta eficiente para a aprendizagem ativa. A possibilidade de consultar diferentes fontes em um único ambiente, receber respostas fundamentadas nessas referências e identificar a origem das informações aumentou minha confiança no processo de estudo. Além disso, recursos como resumos, apresentações e outros materiais de apoio tornaram o aprendizado mais dinâmico e organizado.

Pretendo aplicar e aprofundar esse conhecimento nos próximos projetos, especialmente nas áreas de Inteligência Artificial Generativa, automação de processos e desenvolvimento de soluções que utilizem modelos de linguagem. Este projeto representa o início de uma jornada de aprendizado contínuo, na qual pretendo evoluir minhas habilidades em Engenharia de Prompts e utilizá-las para desenvolver aplicações cada vez mais eficientes e bem estruturadas.
