# Análise Hierárquica de Tarefas (HTA)

## Histórico de Versão

|    Data    | Versão |        Descrição         |  Autor  | Revisor |
| :--------: | :----: | :----------------------: | :-----: | :-----: |
| 25.02.2022 |  0.1   | Criação do Documento CTT | Gustave |  Erick  |

## 1. Introdução:

<p align = "justify"> 
O presente documento tem por objetivo realizar o levantamento e análise hierárquica das tarefas relacionada ao site elegido pelo grupo "Cebraspe". A análise de tarefas é uma atividade importante a ser analisada e pode ser feita em variados momentos durante o desenvolvimento. Uma das formas que o grupo entendeu que seria uma boa forma para fazer essa análise seria usando a Análise Hierárquica de Tarefas (HTA)
</p>

## 2. Sobre o HTA:

<p align = "justify"> 
A metodologia do HTA consiste em uma análise a partir dos objetivos principais do usuário que busca identificar as tarefas que serão realizadas a fim de atingir algum objetivo. Existem, atualmente, duas formas primordiais que são usadas para esse tipo de representação: as notaoções textuais e as gráficas. Antes de introduzi-las, deve-se entender primeiramente os conceitos de tarefa, objetivo, plano e operação, que serão explicados a seguir.

Segundo Barbosa e Silva (2010, p.193; 194):

> "Uma tarefa é qualquer parte do trabalho que precisa ser realizada. Toda tarefa pode ser definida em termo de seu(s) objetivo(s). Tarefas complexas são definidas em termos de objetivos e sub objetivos, num desdobramento hierárquico. Esse desdobramento é chamado de decomposição de tarefas ou redescrição (Diaper, 2003).Uma tarefa é um meio para se atingir um objetivo (Cooper et al., 2007). Em HTA, tarefa se aproxima do conceito de atividade."

> "Um objetivo é um estado específico de coisas, um estado final. Esse estado pode ser definido por um ou mais eventos ou por valores fi sicamente observáveis de uma ou mais variáveis, que atuam como critério de alcance do objetivo e, em última instância, do desempenho do sistema. Em vez de identificar uma lista de ações, a HTA inicia com uma defi nição dos objetivos das pessoas. "

> "Um plano define os subobjetivos necessários para alcançar um outro objetivo maior, e a ordem em que esses subobjetivos devem ser alcançados. Os planos podem definir diversas relações entre os subobjetivos: sequência fixa (um objetivo deve ser atingido antes do próximo); regra de seleção ou decisão (quais objetivos que deverão ser atingidos dependem das circunstâncias); ou em paralelo (mais de um objetivo deve ser atingido ao mesmo tempo)."

> "Um plano define os subobjetivos necessários para alcançar um outro objetivo maior, e a ordem em que esses subobjetivos devem ser alcançados. Os planos podem definir diversas relações entre os subobjetivos: sequência fixa (um objetivo deve ser atingido antes do próximo); regra de seleção ou decisão (quais objetivos que deverão ser atingidos dependem das circunstâncias); ou em paralelo (mais de um objetivo deve ser atingido ao mesmo tempo)."

</p>

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
      2.1. Encontre um subprograma
      2.2. Vá em Mais Informações
   3. Identifique a sessão "GABARITOS E PROVAS"
      3.1. Escolha a parte da prova que você quer
      3.2*. Verifique o status do gabarito (oficial ou prelimitar)
      3.3*. Identifique a hora da divulgação
      3.4 Escolha qual tipo de gabarito você está procurando
   4. Clique para acessar o documento no formato .pdf

<p align = "justify"> 
Plano A: Faça 1-2-3-4 para atingir o objetivo independente de estar logado ou não
Plano B: Faça 1-2-3.1*-3.2*-3.3*-3.4-4 para uma melhor rastreabilidade do documento
</p>

#### 4.2 Objetivo de Realizar Inscrição em um Concurso

0. Concursos
   1. Inscrições Abertas
      1.1. Escolha qual o Concurso você quer se inscrever
      1.2. Vá em Mais informações
      1.3. Clique em Fazer Inscrição
   2. Faça o login
      2.1. Digite seu CPF e senha
      2.2\*. Clique em "Não tenho cadastro" caso não possua
      2.2. Entre na plataforma

## 5. Representação Gráfica

#### 5.1 Objetivo de Verificar Gabarito de uma prova do PAS

<a href="https://ibb.co/cyb3Skb"><img src="https://i.ibb.co/K5NhpbN/Diagrama-HTA1.jpg" alt="Diagrama-HTA1" border="0"></a>

| Objetivos e Operaçoes      | Problemas e Recomendações                                                                                                                                       |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Entrar no site do Cebraspe | Input: barra de pesquisa </br> Action: inserir link do site </br> Feedback: aparecerá o site do cebraspe </br> Problema: caso esteja sem conexão, nao carregará |
| -                          | -                                                                                                                                                               |

#### 5.2 Objetivo de Realizar Inscrição em um Concurso

[IMAGE DO DIAGRAMA]

| Objetivos e Operaçoes      | Problemas e Recomendações                                                                                                                     |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Entrar no site do Cebraspe | Input: barra de pesquisa Action: inserir link do site Feedback: aparecerá o site do cebraspe Problema: caso esteja sem conexão, nao carregará |
| -                          | -                                                                                                                                             |

## Bibliografia:

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. Interação Humano-Computador e Experiência do usuário. Autopublicação. 2021.
