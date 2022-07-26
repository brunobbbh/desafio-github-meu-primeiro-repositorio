# Conceitos Básicos 



## Box Model  



Quando estamos criando o layout de um site o navegador representa cada elemento HTML como uma caixa retangular, isso é o box-model. E com CSS nós alteramos a aparência dessa caixa (largura, altura, cor de fundo, etc). Essa caixa é composta por 4 áreas: o conteúdo, o padding, a borda e a margem.

- As margens (margin) são espaçamentos entre elementos;
- As Bordas (border);
- O padding é um espaçamento entre as bordas e o conteúdo, a diferença para a margens é que declarações de imagem de fundo funcionam nele;
- o conteúdo (content) é o que seu bloco representa, um texto, uma imagem, um vídeo;;



### Exercício

Para enxergarmos o box-model vamos adicionar cores e bordas a alguns elementos.

Primeiro adicionaremos uma cor de fundo para a visualização ficar mais fácil, usaremos a propriedade background com o valor #fff no elemento body.

Depois vamos adicionar uma classe ao <article>, poder ser .post, e então vamos colocar a cor branca de fundo com a propriedade background e o valor de  #FFF. Agora conseguimos enxergar o contente do box-model.

Vamos adicionar um padding de 10 pixels neste mesmo article. Perceberam o espaçamento que surgiu em volta do nosso conteúdo ?

Agora adicionamos uma borda mais escura a ele com a propriedade border. Vou falar mais detalhadamente sobre border mais a frente, mas por enquanto vamos deixar essa bora com 3 pixels de largura, o contorno sólido e a cor azul.

E por último vamos adicionar uma margem de lado de fora do post com a propriedade margin e o valor de 10 pixels.

E agora inspecionando o nosso elemento conseguimos todas aquelas camadas citadas antes: o conteúdo em azul, o padding em verde, as bordas marrom, e as margens em laranja.

E já que começamos a falar sobre bordas e cor de  fundo, no próximo vídeo vamos aprofundar nessas propriedades.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     