# Desafio Controle de Fluxo em Java

Neste desafio, aplicamos os conceitos de controle de fluxo aprendidos no módulo de Java. O objetivo foi criar um programa que recebesse dois números inteiros como entrada pelo terminal e, com esses números, realizasse uma contagem e exibição dos números em um intervalo específico.

## Como Funciona

1. Primeiro, o programa solicita ao usuário que insira dois números inteiros através do terminal.

2. Em seguida, ele verifica se o primeiro número é menor do que o segundo número.

3. Se o primeiro número for menor que o segundo, o programa entra em ação. Ele inicia um loop `for` para imprimir os números incrementados, começando pelo primeiro número até o segundo número.

4. A cada número impresso, ele exibe uma mensagem no console, como "Imprimindo o número X," onde X é o número atual na sequência.

5. No entanto, se o primeiro número for maior ou igual ao segundo número, o programa toma uma ação diferente. Ele lança uma exceção personalizada que criamos, chamada `ParametrosInvalidosException`, com a mensagem "O segundo parâmetro deve ser maior que o primeiro."

## Estrutura do Projeto

Para organizar nosso código de forma eficiente, seguimos as diretrizes abaixo:

- Começamos criando um projeto chamado "DesafioControleFluxo" em nossa IDE.

- Dentro desse projeto, criamos duas classes:
    1. `Contador.java`: Esta classe foi responsável por receber os parâmetros, verificar as condições e realizar a contagem e exibição dos números.
    2. `ParametrosInvalidosException.java`: Esta classe representou uma exceção personalizada que lançamos quando os parâmetros fornecidos eram inválidos.

## Exemplo de Uso

Para ilustrar o funcionamento do programa, supomos que o usuário inseriu os números 12 e 30 como parâmetros. O programa executou um loop com 18 iterações, imprimindo os números de 12 a 30, como mostrado abaixo:

