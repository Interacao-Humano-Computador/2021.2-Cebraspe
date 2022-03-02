# Análise Hierárquica de Tarefas (HTA)

## Histórico de Versão

|    Data    | Versão |              Descrição               |          Autor          |   Revisor    |
| :--------: | :----: | :----------------------------------: | :---------------------: | :----------: |
| 25.02.2022 |  0.1   |         Criação do Documento         |         Gustave         |    Erick     |
| 25.02.2022 |  0.2   |         Ajustando Documento          |     Erick e Daniel      |   Ricardo    |
| 25.02.2022 |  0.3   | Ajustando Pages e legenda de imagens | Erick, Daniel e Gustave | Ana Carolina |
| 25.02.2022 |  0.4   |           Ajustando Tabela           |     Erick e Daniel      |   Gustave    |

## 1. Introdução

<p align = "justify"> 
O presente documento tem por objetivo realizar o levantamento e análise hierárquica das tarefas relacionada ao site elegido pelo grupo "Cebraspe". A análise de tarefas é uma atividade importante a ser analisada e pode ser feita em variados momentos durante o desenvolvimento. Uma das formas que o grupo entendeu que seria uma boa forma para fazer essa análise seria usando a Análise Hierárquica de Tarefas (HTA)
</p>

## 2. Metodologia


A metodologia do HTA consiste em uma análise a partir dos objetivos principais do usuário que busca identificar as tarefas que serão realizadas a fim de atingir algum objetivo. Existem, atualmente, duas formas primordiais que são usadas para esse tipo de representação: as notações textuais e as gráficas. Antes de introduzi-las, deve-se entender primeiramente os conceitos de tarefa, objetivo, plano e operação, que serão explicados a seguir.

Segundo Barbosa e Silva (2010, p.193; 194):


> <p align = "justify"> "Uma tarefa é qualquer parte do trabalho que precisa ser realizada. Toda tarefa pode ser definida em termo de seu(s) objetivo(s). Tarefas complexas são definidas em termos de objetivos e sub objetivos, num desdobramento hierárquico. Esse desdobramento é chamado de decomposição de tarefas ou redescrição (Diaper, 2003).Uma tarefa é um meio para se atingir um objetivo (Cooper et al., 2007). Em HTA, tarefa se aproxima do conceito de atividade."</p>


> <p align = "justify"> "Um objetivo é um estado específico de coisas, um estado final. Esse estado pode ser definido por um ou mais eventos ou por valores fisicamente observáveis de uma ou mais variáveis, que atuam como critério de alcance do objetivo e, em última instância, do desempenho do sistema. Em vez de identificar uma lista de ações, a HTA inicia com uma definição dos objetivos das pessoas. " </p>


> <p align = "justify"> "Um plano define os subobjetivos necessários para alcançar um outro objetivo maior, e a ordem em que esses subobjetivos devem ser alcançados. Os planos podem definir diversas relações entre os subobjetivos: sequência fixa (um objetivo deve ser atingido antes do próximo); regra de seleção ou decisão (quais objetivos que deverão ser atingidos dependem das circunstâncias); ou em paralelo (mais de um objetivo deve ser atingido ao mesmo tempo)." </p>


> <p align = "justify"> "Um plano define os subobjetivos necessários para alcançar um outro objetivo maior, e a ordem em que esses subobjetivos devem ser alcançados. Os planos podem definir diversas relações entre os subobjetivos: sequência fixa (um objetivo deve ser atingido antes do próximo); regra de seleção ou decisão (quais objetivos que deverão ser atingidos dependem das circunstâncias); ou em paralelo (mais de um objetivo deve ser atingido ao mesmo tempo)." </p>



## 3. Objetivos


| Id  | Descricao                                          |
| :-: | -------------------------------------------------- |
| O1  | Objetivo de Verificar Gabarito de uma prova do PAS |
| O2  | Objetivo de Realizar Inscrição em um Concurso      |



## 4. Representação Textual

#### 4.1 Objetivo de Verificar Gabarito de uma prova do PAS

0. Acesso à Universidade
   1. Entre em PAS | UNB
   2. Entre em Subprogramas
      <br> 2.1. Encontre um subprograma
      <br> 2.2. Vá em Mais Informações
   3. Identifique a sessão "GABARITOS E PROVAS"
      <br> 3.1. Escolha a parte da prova que você quer
      <br> 3.2. Escolha qual tipo de gabarito você está procurando
   4. Acessar o documento no formato .pdf

#### 4.2 Objetivo de Realizar Inscrição em um Concurso

0. Concursos
   1. Entre em Inscrições Abertas
      <br> 1.1. Escolha qual o Concurso você quer se inscrever
      <br> 1.2. Vá em Mais informações
      <br> 1.3. Fazer Inscrição
   2. Faça o login
      <br> 2.1. Informe seu CPF e senha
      <br> 2.2. Clique em "Não tenho cadastro" caso não possua
   3. Acessar na plataforma
      <br> 3.1. Confirme os dados pessoais
      <br> 3.2. Se cadastrar em um concurso
      <br> 3.3. Selecionar localização para realizar prova
      <br> 3.4. Selecionar uma das atividades apresentadas
      <br> 3.5. Selecionar o sistema de concorrência (ampla concorrência ou cotas)
      <br> 3.6. Indicar se tem alguma deficiência ou precisa de atendimento especial
      <br> 3.7. Selecionar um meio de pagamento
      <br> 3.8. Informar como ficou sabendo do evento que está se inscrevendo
      <br> 3.9. Concordar com os termos e condições

## 5. Representação Gráfica

### 5.1 Objetivo de Verificar Gabarito de uma prova do PAS

<center>
   <img src="https://i.ibb.co/K5NhpbN/Diagrama-HTA1.jpg" alt="Diagrama-HTA1" border="0" width="500">
   <br><b>Figura 1: Imagem de diagrama HTA</b>
   <br><small><i>Fonte: Própria</i></small>
</center>

| Objetivos/ operações | Problemas e recomendações |
|:--------------------|:-------------------------|
| 0. Acesso à Universidade | **Input**: página principal da Cebraspe aberta; <br> **Action**: mouse encima da opção;<br> **Feedback**: aparecerá as opções de Acesso à Universidade; |
| 1. Entre em PAS | UNB |  **Action**: mouse encima da opção; <br> **Feedback**: aparecerá as opções relacionadas ao PAS|
| 2. Entre em Subprogramas | **Action**: clicar na opção de subprogramas; <br> **Feedback**: aparecerá as opções de subprograma.|
| 2.1. Encontre um subprograma |  **Input**: Opções de subprograma; <br> **Action**: Procurar subprograma desejado.|
| 2.2. Vá em Mais Informações |  **Input**: Opções de subprograma encontradas; <br> **Action**: clicar no botão de Mais Informações; <br> **FeedBack**: aparecerá mais informações do subprograma selecionado em uma nova tela na mesma aba.|
| 3. Identifique a sessão "GABARITOS E PROVAS" |  **Input**: lista de provas e gabaritos. |
| 3.1. Escolha a parte da prova que você quer | **Action**: procurar parte da prova desejada. |
| 3.2. Escolha qual tipo de gabarito você está procurando |  **Action**: verificar se o gabarito é da prova objetiva ou de questões do tipo D; <br> **Problema**: se for um gabarito preliminar é possível que a resposta mude. |
| 4. Acessar o documento no formato .pdf | **Action**: clique no gabarito escolhido; <br> **Feedback**: um gabarito em .pdf será gerado em uma nova aba. |

### 5.2 Objetivo de Realizar Inscrição em um Concurso

<center>
   <br>
   <img src="https://user-images.githubusercontent.com/48844857/155822520-7228019b-9676-474d-9b23-8da080f593c6.jpg" alt="Diagrama-HTA1" border="0" width="900">
   <br><b>Figura 2: Imagem de diagrama HTA parte 1</b>
   <br><small><i>Fonte: Própria</i></small>
   <br>
   <img src="https://user-images.githubusercontent.com/48844857/155822521-cebfa41d-e70c-4fe9-a7fd-d166dce64270.jpg" alt="Diagrama-HTA1" border="0" width="600">
   <br><b>Figura 3: Imagem de diagrama HTA parte 2</b>
   <br><small><i>Fonte: Própria</i></small>
   <br>
   <img src="https://user-images.githubusercontent.com/48844857/155822523-ccf8db38-9647-4c20-a15f-cf91f80f26f2.jpg" alt="Diagrama-HTA1" border="0" width="600">
   <br><b>Figura 4: Imagem de diagrama HTA parte 3</b>
   <br><small><i>Fonte: Própria</i></small>
   <br>
   <img src="https://user-images.githubusercontent.com/48844857/155822519-a428e704-c72f-452f-ad32-28d49049f857.jpg
" alt="Diagrama-HTA1" border="0" width="600">
   <br><b>Figura 5: Imagem de diagrama HTA parte 4</b>
   <br><small><i>Fonte: Própria</i></small>
</center>

| Objetivos/ operações | Problemas e recomendações |
|:--------------------|:-------------------------|
| 0. Concursos | **Input**: página principal da Cebraspe aberta; <br> **Action**: mouse encima da opção; <br>**Feedback**: aparecerá as opções de Concursos; |
| 1. Entre em Inscrições Abertas |  **Action**: clicar na opção; <br> **FeedBack**: aparecerá as opções de concurso com inscrições abertas em uma nova tela mesma guia.|
| 1.1. Escolha qual o Concurso você quer se inscrever | **Input**: Opções de concurso; <br> **Action**: Procurar concurso desejado dentro do período.|
| 1.2. Vá em Mais Informações |  **Input**: Opções de concurso encontradas;<br> **Action**: clicar no botão de Mais Informações;<br> **FeedBack**: aparecerá mais informações do concurso selecionado em uma nova tela na mesma aba. |
| 1.3. Fazer Inscrição |  **Action**: clicar no botão de fazer inscrição. <br> **Problema**: caso esteja fora do período de inscrição não será possível se inscrever; <br> **Recomendação**: exibir data de inscrição |
| 2. Faça o login | **Action**: preencher dados do login.|
| 2.1. Informe seu CPF e senha |  **Action**: digite seu CPF e sua senha. |
| 3. Acessar na plataforma | **Action**: clique no botão entrar;<br> **Feedback**: aparecerá os dados pessoais em uma nova tela na mesma aba. |
| 3.1. Confirme os dados pessoais | **Action**: clique em "sim" no final da página caso estejam corretos ou em "Não. Desejo alterar meus dados" caso contrário;<br> **Feedback**: aparecerá uma lista de concursos disponíveis em uma nova tela na mesma aba; **Recomendação**: o concurso já deveria estar selecionado. |
| 3.2. Se cadastrar em um concurso | **Input**: lista de concursos; **Action**: clique em "inscrever" no concurso desejado;<br> **Feedback**: aparecerá fotografia e local de realização da prova em uma nova tela na mesma aba; <br> **Problema**: caso não tenha uma foto adicionar uma. |
| 3.3. Selecionar localização para realizar prova| **Action**: escolher localização para realizar provar e clicar em "Prosseguir";<br> **Feedback**: aparecerá as atividades disponíveis do nível superior em uma nova tela na mesma aba. |
| 3.4. Selecionar uma das atividades apresentadas | **Action**: escolher atividade e clicar em "Prosseguir";<br> **Feedback**: aparecerá os sistema de concorrência em uma nova tela na mesma aba. |
| 3.5. Selecionar o sistema de concorrência (ampla concorrência ou cotas) | **Action**: escolher sistema de concorrência. |
| 3.6. Indicar se tem alguma deficiência ou precisa de atendimento especial | **Action**: clique em "Prosseguir" ou em "Atendimento Especial" se for o caso; <br>**Feedback**: aparecerá a forma de pagamento em uma nova tela na mesma aba. |
| 3.7. Selecionar um meio de pagamento | **Action**: escolher um meio de pagamento e clicar em "Prosseguir"; <br>**Feedback**: aparecerá os termos e condições em uma nova tela na mesma aba. |
| 3.8. Informar como ficou sabendo do evento que está se inscrevendo | **Input**: lista com os meios de comunicação;<br> **Action**: escolher um meio pelo qual ficou sabendo do concurso. |
| 3.9. Concordar com os termos e condições | **Action**: marcar a opção "De acordo" e clicar em "Concluir"; <br> **Feedback**: um gabarito em .pdf será gerado em uma nova aba. |

## Bibliografia

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. Interação Humano-Computador e Experiência do usuário. Autopublicação. 2021.
