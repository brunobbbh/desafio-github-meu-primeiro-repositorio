# Estilizando Elementos 



Agora que entendemos o box-model podemos focar em deixar nosso site mais bonito, então vamos repassar pelas propriedades já citadas:

## Padding e Margin

Anteriormente usamos o padding e o margin para a forma mais básica, com apenas um valor, mas ele são mais poderosos que isso. Se quisermos atribuir tamanho diferentes para cada lado do box nós podemos, e vamos ver três formas de fazer isso.

A primeira é colocando um valor para as partes superior e inferior e depois para os lados esquerdo e direito.

o valor de 10 pixels se refere ao eixo Y, ou partes superior e inferior, e os 5 pixels se referem aos lados esquerdo e direito.

A segunda  forma é dando valores para cada lado do box.

Então começamos no top com 15 pixels, passamos o lado  direito com 10 pixels, depois para parte inferior com 5 pixels e por último o lado esquerdo com 0, e sempre nessa ordem.

Uma boa dica é quando o valor for 0 não precisamos colocar a  unidade.

A terceira forma é com as propriedades especificas de cada lado, até agora tínhamos visto atalhos para essas propriedades.

Essa opção é mais usada quando temos o mesmo valor para 3 lados, e o quarto precisa ter um valor diferente, então usamos o padding com apenas um valor e uma dessas opções para representar o lado diferente.



## Background

A propriedade background também é um atalho para varias propriedades, mas isso vocês podem absorver aos poucos, e uma boa opção de leitura é a documentação do MDN.

Por enquanto veremos apenas como mudar a cor de fundo.

E aqui temos 3 formas de colocar a cor de fundo, e ainda existem outras.

A primeira é pelo nome da cor em inglês, a segunda é pelo código hexadecimal e a terceira é apenas usando o atalho background.



## Border

Vimos que a propriedade Border pode ter 3 valores: a largura, a cor e o estilo, mas existem algumas particularidades nisso.

A largura pode ser usadas com várias unidades, como px e em mm. A cor pode ser atribuída pelo nome ou código hexadecimal, assim como fizemos como o background, e o estilo  é representada por palavras chaves, vamos ver algumas delas:

- solid: mostra uma borda simples e reta;
- dotted: são bolinhas com espaçamento entre elas;
- dashed: forma uma linha tracejada.

E aproveitando que mostrei esse código temos que falar sobre como separar a estilização dos lados de uma borda.

E se você não quiser usar a propriedade border existem as propriedades especificas para cada aspecto de uma borda, são elas border-width para a largura, border-color para a cor e border-style para o estilo.

Aqui temos o mesmo código anterior para duas formas diferentes, a primeira com o atalho border e a segunda com cada propriedade específica.

Depois disso podemos juntar os lados com os aspectos de uma borda e criar uma regra mais específica ainda.



## Border-radius

E a última propriedade é  border-radius, ele permite arredondar os cantos de um elemento. Podemos usar varias unidades, mas  as mais usadas comuns são os pixels e a porcentagem.

Colocamos apenas um valor mudamos todos os cantos de um elemento, mas seguindo aquela mesma ordem que vimos no padding e margin - topo, direta, inferior e esquerda - conseguimos alterar cada canto separadamente.

