# CSS Custom Properties

Hey guys. Aqui Olimpio. Neste video iremos desvendar um pooco sobre os segredos das Variaveis CSS, oficialmente chamadas de **CSS Custom Properties**. Nesse video entenderemos o que essa feature é, como funciona e tambem veremos 4 casos de uso em projectos reais para as CSS Custom Properties. 



[TOC]



## O que são CSS Custom Properties?

De forma sinples, **Custom Properties** permitem-nos armazenar valores de propriedades CSS para re-utilização nas nossas folhas de estilo. E de uma forma mais simples ainda, tornam possivel escrever variaveis de forma nativa no CSS sem a necessidade de usar um pre-processador CSS. Mas o que é pre-processador CSS? Bom, isso é topico para um futuro video. KKK



**Sintaxe**

Como podemos ver a sintaxe é simples, para criarmos uma custom property so temos que iniciar a nossa variável dentro de um selector CSS com -- seguido do nome da variável e por fim o valor que queremos armazenar. E para utilizarmos a variável so precisamos escrever a função var() e o nome da variavel que queremos re-utilizar como argumento da função var(--nomeDaVariavel).

![image-20220209173638202](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209173638202.png)



### Características das Custom Properties

1. **Case Sensitive** 

   ![image-20220209111506164](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209111506164.png)

   

2. **Escopo**

   ![image-20220209172646403](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209172646403.png)

   

3. **Herança**

   ![image-20220209173159943](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209173159943.png)



### Vantagens de usar Custom Properties

1. Não precisamos de nenhuma ferramenta para usar
2. Dinâmicas, tem o princípio de cascata e herança
3. Podemos manipular usando JavaScript
4. Podemos usar em estilos inline
5. Sintaxe fácil embora um pouco verbosa
6. Só funcionam nos valores das propriedades

## Quatro Use cases

Agora vamos ver 4 formas de aplicarmos as variáveis css nos nossos projectos. Lembrar que há varias outras formas de aplicar as custom properties em seus projectos. E mesmo as use cases aqui apresentadas não são soluções únicas para resolver problemas específicos em seus projectos.



### Color Pallete

Essa talvez seja uma das aplicações mais comuns de ver as custom properties serem usadas. Organizar a paleta de cores do projecto num único lugar e poder reutilizar essas cores ao longo do projecto.

![image-20220209180446834](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209180446834.png)



### Responsive Grid

Custom properties podem nos ajudar a criar Grid layouts complexos, responsivos e fáceis de manter. Imagine que quiséssemos criar uma grid de 8 colunas e num certo breakpoint quiséssemos transformar essa 8 column-grid em 12-column-grid.

![image-20220209180705373](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209180705373.png)

### Repeated Values

Suponhamos que temos um elemento que 100px de padding-top e todos os outros valores são os mesmo, o padding-top é consistente em todos os breakpoints mas os outros valores carecem de mudança. Uma das formas de resolver esse problema seria modificar os outros valores em cada breakpoint. Isso seria muito trabalhoso. 

![image-20220209182923331](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209182923331.png)

Ao invés de modificarmos os valores em todos os breakpoints poderíamos criar uma variável que armazenasse esses valores e so modificaríamos o valor em uma linha de código

![image-20220209183511534](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209183511534.png)

![image-20220209183536304](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209183536304.png)



### Shorthand Properties

Se usarmos propriedades shorthands como border ou qualquer outra, e queremos mudar um valor dentro dessa propriedade shorthand em um outro elemento, ter que reescrever a propriedade de novo é muito tedioso. Usando Custom Properties, podemos alterar valores de shorthand properties sem ter que reescrever toda a proprieade. 

![image-20220209213547559](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209213547559.png)



### Color Functions

Como vimos no exemplo acima, custom properties não representam somente todos os valores de uma propriedade mas tambem podemos usar para armazenar valores parcialmente. Tendo isso em mente podemos criar Funções para manipular cores em CSS. Uma das formas mais comuns de criar esse tipo de funções é usando a função HSLA para manipular cores em CSS. 

![image-20220209215535415](/home/rnrnshn/.config/Typora/typora-user-images/image-20220209215535415.png)





