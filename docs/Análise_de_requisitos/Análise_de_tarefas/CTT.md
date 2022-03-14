# Árvore de Tarefas Concorrentes (CTT)

## Histórico de Versão

|    Data    | Versão |        Descrição         |  Autor  | Revisor |
| :--------: | :----: | :----------------------: | :-----: | :-----: |
| 25.02.2022 |  0.1   | Criação do Documento CTT |  Erick  | Ricardo |
| 25.02.2022 |  0.2   |   Revisando Documento    | Ricardo |    -    |

## 1. Introdução

<p align="justify">
Para auxiliar na avaliação de IHC e no design, utilizamos o modelo de análise de tarefas chamado árvores de tarefas concorrentes (CouncurTaskTrees - CTT). Com ele é possível representar relações entre tarefas utilizando gráficos, a partir dos seguintes tipos de tarefas (representadas na Figura 1):
</p>

<ul>

<li>Tarefas do usuário: em que o sistema não está incluído;
<li>Tarefas do sistema: em que o usuário não interage com o sistema para a realização de um processamento;</li>

<li>Tarefas interativas: em que ocorre interações entre o usuário e o sistema;</li>

<li>Tarefas abstratas: que não são exatamente tarefas em si, mas sim uma representação de um conjunto de tarefas que auxilie a decomposição.</li>

</ul>

<p align="center">
<img src="https://user-images.githubusercontent.com/48844857/155744853-7518f2a7-aaa4-4e35-b453-ebc26a044db5.jpg" width="400">
  <br><b>Figura 1: Legenda de uma CTT</b>
  <br><small><i>Fonte: Barbosa e Silva(2010)</i></small>
</p>

## 2. Nomenclatura de Relacionamento

No modelo CTT, existem 8 possíveis relações entre as tarefas, sendo elas:</li>

<ul>
  
<li>Ativação (T1 >> T2): a segunda tarefa (T2) só pode iniciar após a primeira tarefa (T1) terminar;</li>

<li>Ativação com passagem de informação (T1 []>> T2): além de T2 só poder ser iniciada após T1, a informação gerada em T1 é passada para T2;</li>

<li>Escolha (T1 [] T2): uma vez que uma das duas tarefas seja iniciada, a outra é desabilitada;</li>

<li>Tarefas concorrentes (T1 ||| T2): tarefas que podem ser realizadas em qualquer ordem ou ao mesmo tempo;</li>

<li>Tarefas concorrentes e comunicantes (T1 |[]| T2): além das duas tarefas poderem ser realizadas em qualquer ordem e ao mesmo tempo, elas podem trocar informações;</li>

<li>Tarefas independentes (T1 |=| T2): tarefas que podem ser realizadas em qualquer ordem, mas quando uma delas é iniciada, precisa terminar para que a outra possa ser iniciada;</li>

<li>Desativação (T1 [> T2): a tarefa T1 é completamente interrompida por T2;</li>

<li>Suspensão/retomada (T1 |> T2): a tarefa T1 pode ser interrompida por T2, mas é retomada do ponto em que parou assim que T2 terminar.</li>

</ul>
  
## 3. Resultados
<p align = "justify">Para criar a árvore de tarefas para o nosso projeto, escolhemos um cenário em que o usuário deseja saber sua nota final após já ter realizado as três etapas do PAS. Foi gerada, então, a árvore apresentada na Figura 2.</p>

### 3.1. CTT Consultar média final no PAS

<p align="center">
<img src="https://user-images.githubusercontent.com/48844857/155748522-db7f1d3b-3d68-4620-9c32-f35774929aca.jpg">
  <br><b>Figura 1: Árvore concorrente de consular média final</b>
  <br><small><i>Fonte: própria</i></small>
</p>

## 4. Bibliografia

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. Interação Humano-Computador e Experiência do usuário. Autopublicação. 2021.
