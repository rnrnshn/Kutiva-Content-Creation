# CSS  Box Model

Ola friends, Olimpio aqui.

Neste videos iremos falar sobre CSS Box Model que é um dos conceitos fundamentais de se compreender ao aprender e trabalhar com CSS. 

O video sera divido da seguinte forma:

[TOC]

## 1. CSS Flow Layout

**Normal Flow** ou **Flow Layout** é a forma como os elementos HTML são renderizados no navegador antes que se faça qualquer tipo de alteração. Em **Normal Flow ** os elementos HTML podem ser:

### 1.1 Inline Elements

São elementos HTML que ocupam apenas o espaço do seu conteúdo (o menor espaço possível), em vez de quebrar o fluxo do conteúdo. Exemplos: a, span, strong, em e etc.

- é possivel alterar o comportamento padrão usando a propriedade display do CSS
- Geralmente, inline-elements podem conter apenas dados e outros inline-elements. Não se pode colocar block-elements dentro de inline-elements.

Pode achar a lista de todos elementos HTML que caem na categoria de [inline-elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements)

### 1.2 Block Elements

São elementos que ocupam todo o espaço horizontal disponivel, isto é, toda a largura do navegador, quebrando o fluxo do conteudo. Ex: div, h1, p e etc

- é possivel alterar o comportamento padrão usando a propriedade display do CSS
- Geralmente, block-elements podem conter inline-elements e por vezes outros block-elements. 
- por padrão, block-elements começam em novas linhas enquanto que inline-elements podem ocupar qualquer posição da linha. 

Pode achar a lista de todos elementos HTML que caem na categoria de [block-elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements)

### 1.3 Inline-Block Elements

São inline-elements mas com a unica diferença de podemos ajustar a altura e largura do elemento, o que não se pode fazer nos elementos **inline**.

Tendo isso em mente, vamos agora ver como é que o Box Model funciona.

![block_vs_inline_diagram.png (1920×1081)](https://media.gcflearnfree.org/content/5e82363212da9215e057b928_03_30_2020/block_vs_inline_diagram.png)



## 2. CSS Box Model

**Porquê?** Entender o box model é fundamental para a criação de layouts consistentes.

O que é? **Box Model** é o padrão que o motor de renderização do navegador usa para representar cada elemento HTML como uma caixa rectangular. E esta caixa é composta por quatro propriedades. Compreender como funcionam essas quatro propriedades é fundamental para a compreensão do Box Model, ja que Box Model tem origem nessas propriedades. 

![Box model picture](https://res.cloudinary.com/practicaldev/image/fetch/s--D2j8alvN--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/j4twop44zgnjxd7451zp.PNG)

- Content box
- Padding box
- Border box e
- Margin box

Nesta caixa, o espaço entre o Content e o border é chamado de Padding e o espaço fora de Border é chamado de Margin. 

**Content** - é o conteúdo que escrevemos entre as tags e alguns atributos HTML. O conteúdo depende do tipo de elementos como vimos acima, pode inline-element ou block-element.

![image-20220208231043581](/home/rnrnshn/.config/Typora/typora-user-images/image-20220208231043581.png)



**Padding** - o padding é o espaçamento localizado entre o conteúdo e a borda. O padding cria um espaço extra dentro do elemento. Podemos aplicar o padding em todos os lados do elementos: top, right, bottom e left.

![image-20220208231220684](/home/rnrnshn/.config/Typora/typora-user-images/image-20220208231220684.png)



**Border** - define o estilo da borda de um elemento. Que é a fronteira entre o margin e o padding.

![image-20220208231443883](/home/rnrnshn/.config/Typora/typora-user-images/image-20220208231443883.png)

**Margin** - o margin é o espaçamento localizado do lado de fora da borda. O margin é o espaçamento ao redor do elemento. Tal como o padding, o margin tambem pode ser aplicado em todos os lados do elemento: top, right, bottom e left. O margin influencia no espaçamento entre um elemento e demais elementos ao seu redor. 

![image-20220208231303214](/home/rnrnshn/.config/Typora/typora-user-images/image-20220208231303214.png)

# [Demostração no codepen]