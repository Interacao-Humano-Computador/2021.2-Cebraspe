## Guia de Estilo

### 1. Introdução

### 1.1 Objetivo do guia de estilo

<p align=justify>Trata-se de um registro das principais decisões de design tomadas, de forma que elas não se percam, isto é, sejam efetivamente incorporadas no produto final. Guias de estilo servem de ferramenta de comunicação entre os membros da equipe de design e também com a equipe de desenvolvimento. É importante que as decisões de design possam ser facilmente consultadas e reutilizadas nas discussões sobre extensões ou versões futuras do produto</p>

### 1.2 Organização e conteúdo do guia de estilo

<p align=justify>Para organização do guia de estilo, teremos como base o ciclo de vida de Mayhew, o que sugere que o guia de estilo seja refinado a cada ciclo.</p>

### 1.3 Público alvo do guia de estilo

<p align=justify>O público alvo desta guia de estilo são os membros deste grupo e possíveis desenvolvedores que desejarem realizar correções nos elementos identificados</p>

### 1.4 Como utilizar o guia

<p align=justify>Este guia deve ser utilizado para a elaboração do protótipo e a melhoria do site, a cada etapa dentro do ciclo de Mayhew deve-se aplicar este guia de estilo ao projeto.</p>

### 1.5 Como manter o guia

<p align=justify>Como determina o cilco de Meyhew, o guia vai sendo atualizado ao final de cada etapa, tornando-se assim possível a sua evolução no decorrer do projeto</p>

## 2. Resultado da análise

### 2.1 Descrição do ambiente de trabalho

<p align=justify>Após o levantamento e análise do guia de estilo, por ser um site baseado em avaliações, ele contém informações de acompanhamento de certames ja iniciados ou se pretender se inscrever em algum que esteja aberto, logo abaixo temos várias informações a cerca do institucional do cebraspe, concursos, certificações e acesso a universidade, sendo a página de acompanhamento carece de informações, tela muito vaga e algumas melhorias para a plataforma mobile, assim infringindo diversas metas de usabilidade e características essenciais.</p>

## 3. Elementos de interface

### 3.1. Disposição espacial e grid
<p align=justify>O site utiliza grids no html para a disposição do layout das páginas, porém existem modelos diferentes de grids, o que leva a padrões de páginas diferentes e, portanto, faz-se necessário a análise de todos esses modelos. Desse modo foram separados dois modelos de grids principais no site:</p>

#### 3.1.1. Homepage
<p align=justify>A homepage é bem simples, apresentando as principais opções e notícias em destaque primeiramente, e em seguida algumas outras opções e notícias que podem ser de interesse do usuário. Esta página é bem agradável e confortável e por isso mantivemos o mesmo layout do site.</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/48844857/157974501-959f9bcb-9073-461f-aad2-a27901ddf7f0.jpg" width="600">
  <br><b>Figura 1: Layout da Homepage</b>
  <br><small><i>Fonte: Autores</i></small>
</p>

#### 3.1.2. Área de uma opção principal
<p align=justify>Esta página também é bem simples, conservando alguns elementos do layout da homepage. Contém apenas as informações da opção selecionada previamente no lugar das notícias e sub-opções, o que a torna mais simples e agradável ao usuário.</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/48844857/157974598-794adefb-0e3b-46df-9116-1847fb7b38fa.jpg" width="600">
  <br><b>Figura 2: Layout de uma Opção</b>
  <br><small><i>Fonte: Autores</i></small>
</p>

### 3.2. Janelas
<p align=justify>Os protótipos possuirão as mesmas janelas do site original, com exceção da janela da página de acompanhamento, por possuir muito espaço livre sem necessidade, o que pode causar uma frustração no usuário.</p>

### 3.3. Tipografia
<p align=justify>A tipografia do site utiliza três fontes principais e são elas:
<ul>
    <li><a href="https://fonts.adobe.com/fonts/proxima-nova">Proxima Nova</a></li>
    <li><a href="https://www.cufonfonts.com/font/proxima-nova-condensed">Proxima Nova Condensed</a></li>
    <li><a href="https://fonts.google.com/specimen/Fira+Sans">Fira Sans</a></li>
</ul>
</p>

### 3.4. Símbolos não tipográficos
<table>
    <tr>
        <td colspan=3>Ícones</td>
    </tr>
    <tr>
        <td><img src="https://user-images.githubusercontent.com/48844857/157966489-aa9afe0e-9f41-4b46-a292-7d297ea66292.png" width=20></td>
        <td><img style="filter: brightness(0) saturate(100%);" src="https://images-ext-1.discordapp.net/external/nsy3Pk8GHjXQArkJ4gpDCITgxlXCr3Ju8MiFEct_Oj8/https/cdn.cebraspe.org.br/wp-content/uploads/2022/02/icone_pg_acompanhamento-1.png" width=20></td>
        <td><img src="https://user-images.githubusercontent.com/48844857/157966841-63586076-ce66-4403-a93a-b8f2271d9fc2.png" width=20></td>
    </tr>
    <tr>
        <td><img style="filter: brightness(0) saturate(100%);" src="https://images-ext-1.discordapp.net/external/zjcc5NhCtapIzwq2zBaIwUvdk6uvY9_1trEoYttFMiI/https/cdn.cebraspe.org.br/wp-content/uploads/2022/02/highlight-concursos-1.png" width=20></td>
        <td><img style="filter: brightness(0) saturate(100%);" src="https://cdn.cebraspe.org.br/wp-content/uploads/2022/02/highlight-avaliacoes-1.png" width=20></td>
        <td><img style="filter: brightness(0) saturate(100%);" src="https://cdn.cebraspe.org.br/wp-content/uploads/2022/02/highlight-certificacoes-1.png" width=20></td>
    </tr>
    <tr>
        <td><img style="filter: grayscale(1) invert(1);" src="https://cdn.cebraspe.org.br/wp-content/uploads/2018/12/icon-map-marker.png" width=20></td>
        <td><img style="filter: grayscale(1) invert(1);" src="https://cdn.cebraspe.org.br/wp-content/uploads/2018/12/icon-phone.png" width=20></td>
        <td><img style="filter: grayscale(1) invert(1);" src="https://cdn.cebraspe.org.br/wp-content/uploads/2018/12/icon-envelope.png" width=20></td>
    </tr>
</table>

### 3.5. Cores
#### 3.5.1 Principais cores
<p align=justify>As cores utilizadas em todo o site seguem o padrão de cores do símbolo do cebraspe e algumas variações delas, como mostra as figuras 3 e 4.</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/48844857/157974806-e9861053-e8b3-4e3e-a1f9-b7359bfd3699.png" width="600">
  <br><b>Figura 3: Cores na Logo</b>
  <br><small><i>Fonte: Autores</i></small>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/48844857/157974876-d648a7d7-a908-4abe-b9ff-c53a7436bda3.png" width="600">
  <br><b>Figura 4: Cores nas Páginas</b>
  <br><small><i>Fonte: Autores</i></small>
</p>

### 3.6. Animações
<p align=justify>Para manter o site mais simples e objetivo para o usuário, não há necessidade de animações no site, portanto, nossos protótipos não terão animações.</p>

## 4. Elementos de interação

### 4.1. Estilos de interação

<p align=justify>
No site são utilizados os seguintes tipos de interação
<ul>
    <li>Menus: que facilitam a utilização e navegação do usuário pelo site;</li>
    <li>Linguagem natural: dando orientações ao usuário e indicando o que deve ser feito;</li>
    <li>WIMP: mostrando janelas para acompanhar seleções, e menus e icons por todo o site facilitando a interação;</li>
    <li>Preenchimento de formulário: permitindo o usuário a opção de preencher dados, com o intuito de se inscrever em uma prova de seleção;</li>
</ul>
</p>

### 4.2. Seleção de um estilo

<p style="text-indent: 20px;" align=justify>
O estilo que se encontra predominante por todo o site é o de menu.
</p>

### 4.3. Aceleradores (teclas de atalho)

<p style="text-indent: 20px;" align=justify>
O site não possui nenhuma tecla de atalho.
</p>

## 5 Elementos de ação

### 5.1. Preenchimento de campos

<p style="text-indent: 20px;" align=justify>
Os campos de preenchimento que aparecem por todo o site, e devem ser preenchido manualmente, não existe a opção de preenchimento automático.
</p>

### 5.2. Seleção

<p style="text-indent: 20px;" align=justify>
Algumas seleções são bloqueadas no site, tanto por questões de creedenciais necessitando estar logado para fazer o uso, quanto por questões de disponibilidade, como por exemplo se a inscrição de um curso está aberta.
</p>

### 5.3. Ativação

<p style="text-indent: 20px;" align=justify>
O usuário tem uma série de limitações pelo site necessitando estar logado para ter acesso completo as funcionalidades disponíveis.
</p>

## 6. Vocabulário e padrões

### 6.1. Terminologia

<p style="text-indent: 20px;" align=justify>
Apesar de possuir uma liguagem de grande maioria bem simplificada, possui alguns termos técnicos. Porém, na páginal inicial do site, todos os termos são bem simples e de fácil entendimento para quem novos usuários que não possuem tanta capacidade técnica.
</p>

### 6.2. Tipos de tela

<p style="text-indent: 20px;" align=justify>
É utilizado a tela padrão na maioria de suas páginas dando ao usuário mais conforto e facilidade na interação. Porém isso não é verdade na página de acompanhamento de seleções e na página inicial. Na página de acompanhamento todo o layout da seção muda fazendo com que o usuário tenha dificuldade para se adaptar ao site, tendo que aprender como funciona e na página inicial apesar da navbar se manter todas os locais que as informações deveriam se manter, segundo a tela padrão são trocados.
</p>

### 6.3. Sequências de diálogos

<p style="text-indent: 20px;" align=justify>
Existe uma sequência de diálogos apenas na opção de se cadastrar em um curso, em que é necessário responder uma sequência de diálogos que vão sendo apresentados para conseguir se cadastrar.
</p>

## Referências bibliográficas

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação.

## Versionamento

| Versão | Data       | Modificação                       | Autor                     | Revisor                     |
| ------ | ---------- | ----------------------------------| ------------------------- | ----------------------------| 
| 0.1    | 10/03/2022 | Criação do documento              | Daniel, Erick e Ricardo   | Gustave                     |
| 0.2    | 11/03/2022 | Atualização do documento          | Daniel, Erick e Ricardo   | Gustave                     |
| 0.3    | 12/03/2022 | Arrumando cores                   | Daniel, Erick e Ricardo   | Gustave                     |

