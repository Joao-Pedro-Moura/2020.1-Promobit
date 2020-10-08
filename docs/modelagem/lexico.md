# Léxico

## Introdução

<p style="text-indent: 20px; text-align: justify">
Léxico trata-se de uma técnica que procura descrever os símbolos de uma linguagem, o
principal objetivo a ser perseguido pelos Engenheiros de Requisitos é a identificação de palavras ou
frases peculiares ao meio social da aplicação sob estudo. Cada simbolo é descrito com noção e
impacto.
</p>

<p style="text-indent: 20px; text-align: justify">
No contexto de léxico há o tipo que pode ser um verbo, objeto, ou estado. Há a noção que no
caso de ser verbo se torna quem realiza quando acontece e quais os procedimentos envolvido, no
caso de objeto é definir o objeto e identificar outros objetos com os quais se relaciona e no caso de
estado se torna o que significa e quais ações levaram a esse estado. Há também o impacto que no
caso verbo se tona os reflexos da ação no ambiente (outras ações que devem ocorrer) e quais os
novos estados decorrentes, no caso do objeto se torna as ações que podem ser aplicadas ao objeto, e
por final no caso do estado se torna o ato de identificar outros estados e ações que podem ocorrer a
partir do estado que se descreve.
</p>

## Metodologia

Utilizaremos como base o modelo de tabela abaixo:

### **Símbolo**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Objeto/Estado/Verbo | Denotação | Conotação | Opcional |

## Léxicos

#### L1 - **Oferta**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Objeto | Oferta de uma loja, sugerida por um usuário e validada pelo sistema | Usuário visualiza rapidamente diversas ofertas | Promoção |

#### L2 - **Cupom**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Objeto | Cupom promocional disponibilizado por uma das lojas parceiras, validado pelo sistema | O ator pode pegar o cupom e utiliza-lo nas compras que são inclusas pelo cupom | - |

#### L3 - **Curtir**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | Forma de o usuário enaltecer uma oferta ou algum tópico | O usuário tem a liberdade de curtir algo que gostou e isso pode gerar uma maior visibilidade para algum fator | Gostar, Adorar, Dar *like* |

#### L4 - **Lista de desejos**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Objeto | Uma lista de categorias de produtos que interessam ao usuário | O ator adiciona as categorias, que deseja receber notificações de cupons e ofertas, à sua lista de desejos  | - |

#### L5 - **Compartilhar**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | Opção de escolha para que algo seja partilhado com alguém | Permite ao usuário partilhar um cupom, oferta ou tópico de sua preferência  | Partilhar |

#### L6 - **Sugerir**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | Forma em que o usuário propor alguma oferta ou cupom para o sistema | A sua sugestão pode ser futuramente publicada | Propor e sugestionar |

#### L7 - **Medalha**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Objeto | Recompensa dada aos usuários por cumprirem determinados objetivos dentro do sistema | São utilizadas para quantificar a interação dos usuários com o aplicativo e também tornar o ambiente mais engajador | - |

#### L8 - **Tópico**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Objeto | Post publicado no fórum expressando dúvidas, *reviews*, sugestões de usuários | Pode ser compartilhado, lido e comentado | Post |

#### L9 - **Confiável**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Estado | Determina se um cupom ou oferta é verdadeiro | Maior uso e confiança do usuário em relação ao sistema | Verdadeiro e honesto |

#### L10 - **Categoria**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Objeto | Serve para classificar produtos em grupos maiores referentes | Usuário obtém maior organização no contexto dos produtos no sistema | Classe |

#### L11 - **Avaliação**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Objeto | Avaliação de uma oferta ou cupom | O sujeito que foi avaliado poderá ter uma maior visibilidade podendo essa ser positiva ou negativa | Crítica e *review* |

#### L12 - **Reportar**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | Possibilidade do usuário denunciar uma oferta, cupom ou usuário | O(a) sujeito, oferta, ou cupom será reportado(a) para o sistema, o que pode trazer consequências negativas | Acusar, culpar e denunciar |

#### L13 - **Comentar**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | Ação de deixar um comentário em um tópico, oferta ou cupom | Maior expressão do usuário em relação a ofertas, produtos, cupons e tópicos | - |

#### L14 - **Bloquear**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | Um usuário bloquea outro usuário quando não deseja visualizar as atividades dele | Não receber as ofertas e cupons, não ver as discussões adicionadas no fórum e no blog pelo usuário bloqueado | - |

#### L15 - **Barra de busca**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Objeto | Local destinado à pesquisa de usuários, ofertas, tópicos, cupons e categorias  | Permite localizar ofertas, cupons, usuários e tópicos dentro do sistema | Barra de pesquisa |

#### L16 - **Seguir**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | Habilidade de acompanhar outro usuário | Receber ofertas e cupons enviados pelo usuário seguido | Acompanhar |

#### L17 - **Filtrar**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | Ajustar o que aparece para o usuário por meio de algum tópico ou categoria específica | Visualizar coisas referente apenas à filtragem aplicada | Separar |

#### L18 - **Personalizar**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | Deixar do modo do usuário, transformar em algo do agrado do usuário | Visualizar apenas coisas de seu interesse | Customizar |

#### L19 - **Indicar**

| Classificação | Noção | Impacto | Sinônimos |
| ------------- | ----- | ------- | --------- |
| Verbo | O usuário sugere o aplicativo por meio de uma mensagem pré determinada pelo sistema através de uma rede social ou email | O ator é redirecionado para o meio que escolheu para indicar o aplicativo com a mensagem já escrita, bastando apenas confirmar a ação | Apontar e sugerir |

## Referências Bibliográficas

>SAMPAIO, Julio; FRANCO, Ana. "A strategy for Conceptual Model Acquisition". Departamento de informática, Pontíficia Universidade Católica, Rio de Janeiro.

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 07/10/2020 | Criação do documento de léxicos| Todos os integrantes |
