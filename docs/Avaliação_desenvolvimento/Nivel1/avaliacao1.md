# Avaliação 1: Consultar média final do PAS

## Histórico de Versão

|    Data    | Versão |      Descrição       |      Autor       | Revisor |
| :--------: | :----: | :------------------: | :--------------: | :-----: |
| 26.03.2022 |  0.1   | Criação do documento |      Ricardo     | Erick   |

## 1. Introdução

<p align="justify">
Para auxiliar na avaliação de IHC e no design, utilizamos o modelo de análise de tarefas chamado árvores de tarefas concorrentes (CouncurTaskTrees - CTT). Com ele é possível representar relações entre tarefas utilizando gráficos, a partir dos seguintes tipos de tarefas:
</p>

<ul>

<li>Tarefas do usuário: em que o sistema não está incluído;
<li>Tarefas do sistema: em que o usuário não interage com o sistema para a realização de um processamento;</li>

<li>Tarefas interativas: em que ocorre interações entre o usuário e o sistema;</li>

<li>Tarefas abstratas: que não são exatamente tarefas em si, mas sim uma representação de um conjunto de tarefas que auxilie a decomposição.</li>

</ul>


## 2. Preparação 

### **Tarefa:** <a href "https://interacao-humano-computador.github.io/2021.2-Cebraspe/An%C3%A1lise_de_requisitos/An%C3%A1lise_de_tarefas/CTT/">Consultar média final do PAS</a>

### **Persona:**<a href "https://interacao-humano-computador.github.io/2021.2-Cebraspe/An%C3%A1lise_de_requisitos/Personas/personas/">Nezuko Kamado</a>

**Ações:**

1. Acessar o site do Cebraspe;
2. Escolher o boletim do subprograma inscrito;
3. Acessar "Acesso à universidade";
4. Acessar "PAS | UnB";
5. Acessar "Subprograma";
6. Escolher etapa do subprograma desejado;
7. Informar o CPF e senha;
8. Navegar pelo PDF do resultado.

## 3. Coleta de Dados

### 3.1 Acessar o site do Cebraspe
* **Essa ação está representada de alguma forma no diagrama CTT ?**<br>
Sim, está representado no topo do diagrama

* **A tarefa está descrita como Abstrata ?** <br>
Sim, está descrita como uma tarefa abstrata

* **As ligações com outras tarefas estão corretas ?** <br>
Parcialmente, a tarefa de coleta de dados está ligada com Navegar no pdf, porém não tem haver com esta tarefa em específico 

### 3.2 Escolher o boletim do subprograma inserido
* **Essa ação está representada de alguma forma no diagrama CTT ?**<br>
Sim, está representado no diagrama

* **A tarefa está descrita como Abstrata ?** <br>
Sim, está descrita como uma tarefa abstrata

* **As ligações com outras tarefas estão corretas ?** <br>
Sim está correta, tanto com as tarefas interativas e a tarefa abstrata que é retormada por ela

### 3.3 Acessar "Acesso à universidade";
* **Essa ação está representada de alguma forma no diagrama CTT ?**<br>
Sim, está representado no diagrama

* **A tarefa está descrita como Interativa ?** <br>
Sim, está descrita como uma tarefa interativa

* **As ligações com outras tarefas estão corretas ?** <br>
Sim, através de ativação com outras tarefas

### 3.4 Acessar "PAS | UnB";
* **Essa ação está representada de alguma forma no diagrama CTT ?**<br>
Sim, está representado no diagrama

* **A tarefa está descrita como Interativa ?** <br>
Sim, está descrita como uma tarefa interativa

* **As ligações com outras tarefas estão corretas ?** <br>
Sim, através de ativação com outras tarefas

### 3.5 Acessar "Subprograma";
* **Essa ação está representada de alguma forma no diagrama CTT ?**<br>
Sim, está representado no diagrama

* **A tarefa está descrita como Interativa ?** <br>
Sim, está descrita como uma tarefa interativa

* **As ligações com outras tarefas estão corretas ?** <br>
Sim, através de ativação com outras tarefas

### 3.6 Escolher etapa do subprograma desejado;
* **Essa ação está representada de alguma forma no diagrama CTT ?**<br>
Sim, está representado no diagrama

* **A tarefa está descrita como Interativa ?** <br>
Sim, está descrita como uma tarefa interativa

* **As ligações com outras tarefas estão corretas ?** <br>
Sim, através de ativação com outras tarefas

### 3.7 Informar o CPF e senha;
* **Essa ação está representada de alguma forma no diagrama CTT ?**<br>
Sim, está representado no diagrama

* **A tarefa está descrita como Interativa ?** <br>
Sim, está descrita como uma tarefa interativa

* **As ligações com outras tarefas estão corretas ?** <br>
Sim, através de tarefas concorrentes  

### 3.8 Navegar pelo PDF do resultado.
* **Essa ação está representada de alguma forma no diagrama CTT ?**<br>
Sim, está representado no diagrama

* **A tarefa está descrita como Usuário?** <br>
Sim, está descrita como uma tarefa do usuário

* **As ligações com outras tarefas estão corretas ?** <br>
Sim, através de ativação com outras tarefas

## 4. Interpretação e consolidação dos resultados

<p align = "justify">Com o percurso cognitivo feito, notamos que, no que diz a respeito do CTT, o documenta está de acordo como um todo, os passos necessários para a realização da tarefa foram demonstrados e estão descritos no CTT.
Notamos, que os fluxos demonstram sentido e clareza ao diagrama no sistema, a representação de tarefas estão bem descritos, tanto quanto as nomeclaturas de relacionamento.</p>

## 5. Conclusão

<p align = "justify">Concluimos que havendo como objetivo a checagem da coerência da análise de tarefas e a sua fidelidade com a utilização do sistema, essa presente avaliação tem como escopo todas as ações necessárias para a realização da tarefa denominda como sendo <strong>consultar a média final do PAS.</strong><br>
Esta tarefa aborda as ações dos usuários ao navegar a plataforma do Cebraspe e utilizar o sistema para conseguir visualizar a média de algum subprograma do PAS com sucesso.<br>
Esta avaliação foi executada por um avaliador membro da equipe do projeto, que, foi utilizado a persona <a href "https://interacao-humano-computador.github.io/2021.2-Cebraspe/An%C3%A1lise_de_requisitos/Personas/personas/">Nezuko Kamado</a>, se colocou no lugar do usuário para a realização da técnica de percurso cognitivo, na qual vusa a avaliação da facilidade de aprendizado do sistema por parte do usuário para responder as perguntas:</p>
* Essa ação está representada de alguma forma no diagrama CTT ?
* A tarefa está descrita como alguma relação de tarefa no CTT ?
* As ligações com outras tarefas estão corretas ?

<p align = "justify">Tendo em base tudo que foi levantado nesta avaliação, os seguintes pontos devem ser alterados na análise de tarefas:</p>
* Arrumar a ligação entre tarefas na ação 2.1.