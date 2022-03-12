# Introdução ao CSS - Kutiva

[TOC]



Hey guys bem-vindo ao Kutiva. Olímpio aqui. Neste vídeo iremos dar uma pequena introdução ao CSS. Iremos aprender sobre a sua origem, conceito e função na web.

Antes de estudar o CSS, deve-se ter pelo menos um conhecimento básico de HTML. CSS é utilizado para especificar a aparência geral das páginas web escritas em HTML. Para utilizar o CSS para este fim, devemos primeiro ter pelo menos uma compreensão básica da construção de páginas web. 

Mas antes, um pouco de estória só para nos situar. 

## Historia do CSS

Não uma linguagem em si, o CSS é uma parte do HTML. 

O CSS foi adicionado ao HTML para resolver um problema especifico - separar o conteúdo HTML do layout da pagina. Este problema surgiu quando os dois navegadores web mais populares (Netscape e Internet Explorer) na altura adicionavam continuamente novas tags e atributos à especificação HTML. O navegador tinha a função de criar o layout para pagina web. O objetivo original das tags HTML era especificar o conteúdo que iria aparecer nas páginas web, e não o seu layout. Mas já não era este o caso, com o Netscape e o Internet Explorer acrescentando tags como se estivessem jogando um jogo de lego.

Podemos seguir as origens do CSS até ao ano de 1994, quando Håkon Wium Lie o propôs enquanto trabalhava com Tim Berners-Lee no CERN.



## O que é CSS?

Ao longo dos anos, o CSS evoluiu trazendo funcionalidades adicionais que o elevam de uma linguagem de estilo simples para uma mais robusta e poderosa. Alguns efeitos como Animações, Transições, Transformações que só eram possíveis com JavaScript são agora possíveis apenas com CSS.

**CSS** significa ***Cascading Style Sheets*** (folhas de estilo em cascata). É uma linguagem concebida para especificar a aparência geral das páginas web, bem como a aparência e estrutura do texto e elementos tais como imagens e botões nas páginas web e a seu layout. Os estilos podem ser especificados com CSS utilizando definições de folhas de estilo internas que são colocadas directamente em código HTML ou em ficheiros externos.

E o que podemos fazer com o CSS?

- especificar a cor do fundo de uma pagina

- especificar a estilização comum para uma ou mais tags

- especificar distancia entre elementos HTML

- especificar a aparência de links

- especificar varios estilos para varias paginas web

  **Tudo isto e muito mais pode ser feito com o CSS!**



## Anatomia do CSS

De que forma o CSS define estilizações para elementos e tags HTML? Well, as propriedades do CSS são utilizadas para aplicar o efeito desejado nos Elementos HTML.

Estas propriedades são nomeadas de modo a que se saiba o que vai acontecer ao Elemento HTML em que se está a aplicar a estilização.

Quando se deparar com termos como `background-color`, deverá ter a sensação de que esta propriedade irá mudar a cor de fundo do elemento desejado.

Outra propriedade é o `font-size` que pode ser utilizada para aumentar ou diminuir o tamanho da fonte de elementos HTML como Cabeçalhos ( h1 a h6 ) e Parágrafos ( p ).

CSS contém muitas propriedades que podem ser usadas para alcançar o efeito desejado no Elemento HTML, falar sobre cada uma delas tornará este video demasiado longo e é provável que se aborreça antes de aprender alguma coisa.

Há diversas formas de aplicar estilos a elementos HTML usando o CSS. Por ora vamos nos focar somente na sintaxe mais usual de um regra CSS. 

Uma regra CSS é composta pela nome do elemento HTML que queremos estilizar seguido da abertura e fechamento de colchetes. De entre as colchetes adicionamos as propriedades e os valores das propriedades que queremos aplicar ao elemento. 

```css
p {
    color: red;
    font-size: 16px;
}
```



Para Introdução ao CSS terminamos por aqui, vemo-nos nos próximos vídeos para falar sobre JavaScript. Se quiser ver uma breve Introdução ao HTML, pode acessa-lo aqui mesmo no canal da Kutiva.