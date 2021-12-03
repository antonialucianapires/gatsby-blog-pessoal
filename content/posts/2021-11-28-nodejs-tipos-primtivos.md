---
template: post
title: "NodeJS: tipos primtivos"
slug: aprendendo-nodejs-tipos-primitivos
socialImage: /media/nodejs.jpg
draft: true
date: 2021-11-28T13:36:46.208Z
description: "Qualquer programa manipula valores, como textos e números. Em uma
  linguagem de programação, os tipos são valores que podem ser representados e
  processados, mas o suporte para estes tipos varia entre as linguagens. O
  NodeJS possui os tipos number, string e boolean. "
category: programacao, nodejs
tags:
  - nodejs
  - tipos-primtivos
  - programacao
---




Qualquer programa manipula valores, como textos e números. Em uma linguagem de programação, os tipos são valores que podem ser representados e processados, mas o suporte para estes tipos varia entre as linguagens. O NodeJS possui os tipos number, string e boolean. 

![texto olá mundo, número 55 e palavra em inglês true](/media/tipos-primitvos.png "tipos primitivos")

### Variáveis

Para processar um dado, durante a execução do programa, é necessário retê-lo e para isso existem as variáveis. A variável é uma forma de separar um espaço na memória do computador para guardar um valor e também é uma característica que varia entre as linguagens de programação. No Javascript, utilizamos a seguinte estrutura:

```javascript
const meuNumero = 10;
const meuNome = "Antonia";
const verdadeiro = true;
```

### Tipos numéricos

O tipo number armazena valores numéricos, seja ele um inteiro ou decimal (conhecido também como float ou número de ponto flutuante). Para representar um número, atribui-se um valor numérico a uma variável:

```
const idade = 12;
const preco = 7.55;
```

Para pontos flutuantes como 0.5, pode-se também utilizar a seguinte declaração:

```
const pontoFlutuante = .5;
```

#### Operações matemáticas com tipos numéricos

Além de armazenar números, é possível também realizar operações matemáticas com as variáveis que possuem esse tipo de valor, como soma, divisão, subtração e multiplicação. 

```
const valor1 = 5;
const valor2 = 5;

const resultadoSoma = valor1 + valor2;
const resultadoSubstracao = valor1 - valor2;
const resultadoMultiplicacao = valor1 * valor2;
const resultadoDivisao = valor1 / valor2;

console.log(resultadoSoma); //exibe 10
console.log(resultadoSubstracao); //exibe 0
console.log(resultadoresultadoMultiplicacaoSoma); //exibe 25
console.log(resultadoDivisao); //exibe 1
```



### Tipo String

String, em programação, é uma sequência de caracteres alfanuméricos (letras, números e/ou símbolos). Logo, o tipo String é utilizado para manipular textos e estes precisam estar sempre entre aspas, sejam elas duplas ou simples, ambas são aceitas.

```
const primeiroNome = "Maria";
const minhaSenha=  'senha1234@';
```

Para textos que precisam conter aspas, como uma citação, é possível combinar o uso dos dois tipos de aspas:

```
const citacao = 'Segundo Voltaire (1694-1778), filósofo francês, “Preconceito é opinião sem conhecimento.”';
```



#### Concatenação 

Concatenar strings é um recurso onde podemos juntar duas ou mais strings e formar uma nova. Veja no exemplo a seguir:

```
const nomeCliente = 'Lara';
const fraseBemVindo = 'Bem vindo(a) ';

const fraseCompleta = nomeCliente + fraseBemVindo;

console.log(fraseCompleta);
//exibe

Bem vindo(a) Lara!
```