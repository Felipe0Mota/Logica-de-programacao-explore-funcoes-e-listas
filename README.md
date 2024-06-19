# Logica-de-programacao-explore-funcoes-e-listas
Minha resolução dos exercícios no curso "Lógica de programação: explore funções e listas"
--------------------
### Aula 1
> Faça o download de outro projeto e abra no Visual Studio Code.
>
>Altere o conteúdo da tag h1 com document.querySelector e atribua o seguinte texto: Hora do Desafio.
>
>Crie uma função que exiba no console a mensagem O botão foi clicado sempre que o botão Console for pressionado.
>
>Crie uma função que exiba um alerta com a mensagem: Eu amo JS, sempre que o botão Alerta for pressionado.
>
>Crie uma função que é executada quando o botão prompt é clicado, perguntando o nome de uma cidade do Brasil. Em seguida, exiba um alerta com a mensagem concatenando a resposta com o texto: Estive em {cidade} e lembrei de você.
>
>Ao clicar no botão soma, peça 2 números inteiros e exiba o resultado da soma em um alerta.


```js
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora do Desafio';

function botaoConsole() {
    console.log('O botão foi clicado!');
}

function botaoAlerta() {
    alert('Eu amo JS');
}

function botaoPrompt() {
    let cidade = prompt('Qual a última cidade que você visitou?');
    alert(`Estive em ${cidade} e lembrei de você`);
}

function botaoSoma() {
    let num1 = parseInt(prompt('Digite o primeiro número para somar:'));
    let num2 = parseInt(prompt('Digite o segundo número para somar'));
    let soma = num1 + num2

    alert(`${num1} + ${num2} = ${soma}`);
}
```
