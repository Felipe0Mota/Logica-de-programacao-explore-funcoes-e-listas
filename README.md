# Logica-de-programacao-explore-funcoes-e-listas

Minha resolução dos exercícios no curso "Lógica de programação: explore funções e listas"
--------------------
### Aula 3

**Desafio 1**
> Crie uma função que calcule o índice de massa corporal (IMC) de uma pessoa, a partir de sua altura, em metros, e peso, em quilogramas, que serão recebidos como parâmetro.

```js
function calculoIMC(altura, peso) {
  let imc = peso / (altura ** 2);
}
```

**Desafio 2**
> Crie uma função que calcule o índice de massa corporal (IMC) de uma pessoa, a partir de sua altura, em metros, e peso, em quilogramas, que serão recebidos como parâmetro.

```js
let num = 7;
calculoFatorial(num);

function calculoFatorial(num) {
  let n = num;
  let fatorial = n;
  if (n == 0 || n == 1) {
    return 1;
  }

  while(n >= 2) {
    fatorial *= (n - 1);
    n--;
  }
  return fatorial;
}
```

**Desafio 2 - versão Instrutor**
> Crie uma função que calcule o índice de massa corporal (IMC) de uma pessoa, a partir de sua altura, em metros, e peso, em quilogramas, que serão recebidos como parâmetro.

```js
let numero = 5;
let resultado = calcularFatorial(numero);
console.log(`O fatorial de ${numero} é ${resultado}`);

function calcularFatorial(numero) {
  if (numero === 0 || numero === 1) {
    return 1;
  }

  let fatorial = 1;
  for (let i = 2; i <= numero; i++) {
    fatorial *= i;
  }

  return fatorial;
}
```

**Desafio 3**
> Crie uma função que converte um valor em dólar, passado como parâmetro, e retorna o valor equivalente em reais. Para isso, considere a cotação do dólar igual a R$4,80.

```js
let dolares = 50;
let reais = converterDolarParaReal(dolares);
console.log(`US$${dolares.toFixed(2)} se converte em R$${reais}`);

function converterDolarParaReal(valorEmDolar) {
  let cotacaoDolar = 4.8; // US$ 1,00 = R$ 4,80
  let valorEmReais = valorEmDolar * cotacaoDolar; 
  return valorEmReais.toFixed(2);
}
```

**Desafio 4**
> Crie uma função que mostre na tela a área e o perímetro de uma sala retangular, utilizando altura e largura que serão dadas como parâmetro.

```js
let alturaSala = 4;
let larguraSala = 6;

perimetroEAreaSalaRetangular(alturaSala, larguraSala);

function perimetroAreaSalaRetangular(altura, largura) {
  let perimetro = 2 * (altura + largura);
  let area = altura * largura;
  
  console.log(`A área da sala é ${area}m²`);
  console.log(`O perímetro da sala é ${perimetro}m`);
}
```

**Desafio 5**
> Crie uma função que mostre na tela a área e o perímetro de uma sala circular, utilizando seu raio que será fornecido como parâmetro. Considere Pi = 3,14.

```js
let raioSala = 4;
perimetroAreaSalaCircular(raioSala);

function perimetroAreaSalaCircular(raio) {
  let pi = 3.14;
  let area = pi * raio ** 2;
  let perimetro = 2 * pi * raio;

  console.log(`A área do círculo é ${area}m²`);
  console.log(`O perímetro do círculo é ${perimetro}m`);
}

```

**Desafio 6**
> Crie uma função que mostre na tela a tabuada de um número dado como parâmetro.

```js
let numero = 3;
tabuada(numero);

function tabuada(num) {
  let resultado;
  for(let i = 1; i <= 10; i++) {
    resultado = num * i;
    console.log(`${num} × ${i} = ${resultado}`);
  }
}
```
