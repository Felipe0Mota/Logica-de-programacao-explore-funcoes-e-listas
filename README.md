# Logica-de-programacao-explore-funcoes-e-listas

Minha resolução dos exercícios no curso "Lógica de programação: explore funções e listas"
--------------------
### Aula 2

**Desafio 1**
> Criar uma função que exibe "Olá, mundo!" no console.

```js
exibirOla();

function exibirOla() {
    console.log('Olá, mundo!');
}
```

**Desafio 2**
> Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.

```js
exibirOlaNome('Felipe');

function exibirOlaNome(nome) {
    console.log(`Olá, ${nome}!`);
}
```

**Desafio 3**
> Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.

```js
let resultadoDobro = calcularDobro(5);
console.log(resultadoDobro);

function calcularDobro(numero) {
    return numero * 2;
}
```

**Desafio 4**
> Criar uma função que recebe três números como parâmetros e retorna a média deles.

```js
let media = calcularMedia(4, 7, 10);
console.log(media);

function calcularMedia(a, b, c) {
    return (a + b + c) / 3;
}
```

**Desafio 5**
> Criar uma função que recebe dois números como parâmetros e retorna o maior deles.

```js
let maiorNumero = encontrarMaior(70, 47);
console.log(maiorNumero);

function encontrarMaior(a, b) {
    return a > b ? a : b;
}
```

**Desafio 6**
> Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo

```js
let resultado = quadrado(2);
console.log(resultado);

function quadrado(numero) {
    return Math.pow(numero, 2);
}
```
