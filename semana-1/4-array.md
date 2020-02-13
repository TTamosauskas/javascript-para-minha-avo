Array
======

Array é um tipo especial variavel que trazem dentro de si outras variáveis. 

👵🏻 Agora fudeu
-----------------

Pense neles como se fossem bolsas que carregam outros itens.

```javascript
var bolsa = ["battom", "carteira", "espelho", "chaves"];
```
Note que o valor do array sempre vem entre duas chaves []

### Chamado um Array

Um array pode ser chamado de duas formas. A primeira é como uma lista:

```javascript
var bolsa = ["batom", "carteira", "espelho", "chaves"];
document.write(bolsa)
```
A segunda é apenas um dos itens da lista:

```javascript
var bolsa = ["batom", "carteira", "espelho", "chaves"];
document.write(bolsa[1])
```
Note que o número da última linha é referente a ordem com que o item está na lista do array. Faça o teste.

👵🏻 Mas o 1 não deveria ser batom? Apareceu carteira
------------------------------------------------------

Isso ocorre porque a contagem começa com zero. Veja o exercicio abaixo

Exercicio
==========

Mudando o conteúdo abaixo no seu script faça aparecer o resultado **espelho**

```javascript
var bolsa = ["baton", "carteira", "espelho", "chaves"];
document.write(bolsa[1])
```







