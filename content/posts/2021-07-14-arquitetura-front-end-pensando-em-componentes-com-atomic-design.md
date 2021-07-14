---
template: post
title: "Arquitetura Front-end: Pensando em componentes com Atomic Design"
slug: pensando-em-componentes-com-atomic-design
socialImage: /media/html-periodic-table.png
draft: false
date: 2021-07-14T02:07:41.512Z
description: "O Atomic Design é um método desenvolvido por Brad Frost para a
  criação de design systems. Trata-se de uma analogia para demonstrar como os
  diferentes elementos de uma página podem interagir. Dessa maneira, temos as
  seguintes estruturas: átomo, molécula, organismo, página e template."
category: Arquitetura Front-end
tags:
  - front-end
  - arquitetura-de-software
  - design
---
No cenário atual, mergulhar no mundo de software engloba estar preparado para pensar, arquitetar e desenvolver sistemas cada vez mais complexos. Por esse motivo, precisamos modularizar, quebrar em partes menores, para manter, reutilizar e escalar estes sistemas e aplicações de uma maneira saudável. Pensar em partes menores vai de encontro com o conceito de componentes. Na documentação da biblioteca ReactJS, temos a seguinte definição: 

> "Componentes permitem você dividir a UI em partes independentes, reutilizáveis e pensar em cada parte isoladamente.". 

A partir deste conceito você seria capaz de desenvolver uma aplicação orientada a componentes? Para adaptar o mindset e pensar nessa forma de desenvolver interfaces webs, facilitando a compreensão e a identificação de componentes, podemos começar pelo Atomic Design.

O [Atomic Design](https://atomicdesign.bradfrost.com/chapter-2/) é um método desenvolvido por [Brad Frost ](https://bradfrost.com/)para a criação de design systems. Trata-se de uma analogia para demonstrar como os diferentes elementos de uma página podem interagir. Dessa maneira, temos as seguintes estruturas: átomo, molécula, organismo, página e template.

**Átomo**
Na química, o átomo é a unidade básica da matéria. Logo, podemos pensar em elementos simples que não precisam de nenhum outro elemento para existirem. Exemplo: input, button, label, cor, tipografia, etc.

![](/media/3.png)

**Molécula**
A molécula é formada por dois ou mais átomos. Sendo assim, temos dois ou mais elementos(átomos) que interagem entre si e possuem uma relação de interdepedência, pois a molécula depende dessas relações para existir. Exemplo: se unirmos label, input e button, formamos um formulário. 

![](/media/2.png)

**Organismos**
Um organismo é um grupo de moléculas e átomos, um módulo mais estruturado, que juntos possuem um objetivo. Eles não precisam estar diretamente interligados, mas existem no mesmo contexto. Exemplo: um cabeçalho é um organismo porque reúne átomos (cor, tipografia - se pensarmos em nível mais abstrato) e moléculas (formulário e navegação) e tem o objetivo de melhorar e facilitar a experiência do usuário.

![](/media/1.png)

**Templates**
Saindo do campo da química, os templates reúnem e organizam os organismos, isso inclui definir a localização dos componentes. O template pode ser entendido como a padronização que será utilizada em diferentes paǵinas que participam do mesmo escopo.

**Páginas**
A página pode ser entendida como o produto final, que não precisa ser originada de um template, mas contém os componentes e provém o conteúdo base, como por exemplo, os dados do usuário. Todos envolvidos para antigir o objetivo final.

Estes são os principais conceitos e analogias propostos por Frost nos quais é possível verificar que o método Atomic Design é um modelo mental que nos fornece clareza para a construção de interfaces em sistemas modulares, navegando do abstrato ao concreto. Desta forma, podemos criar sistemas a partir de componentes reutilizáveis e organizados que promovam consistência, escalabilidade, entre outros benefícios que podem contribuir para a exibição do produto final.

**Para se aprofundar mais**

FROST, B. **Atomic Design Methodology**. [https://atomicdesign.bradfrost.com/](https://atomicdesign.bradfrost.com/table-of-contents/) , 2016.

STRACK, E. **Atomic Design**. Edição: .[ https://evertonstrack.com.br/atomic-design/](https://evertonstrack.com.br/atomic-design/) , 2020.

NANO, . **A inteligência por trás do Atomic Design**. Edição: . <https://medium.com/dex01/inteligenciaportrasatomicdesign-1e405464ff5d> , 2017.

COSTA, . **Componentização no Front-end IV**. Edição: . <https://inside.contabilizei.com.br/componentiza%C3%A7%C3%A3o-no-front-end-f40b0b85143f> , 2019.

CARICATI, T. **Reactjs e Atomic Design na prática**. Edição: . <https://blog.novatics.com.br/reactjs-e-atomic-design-na-pr%C3%A1tica-5a6e23b8b25> , 2017.

CURSOS, A. **Arquitetura CSS: Descomplicando os problemas**. Edição: . <https://cursos.alura.com.br/course/arquitetura-css>: , 2020.

FROST, B. **Atomic Design Methodology**. Edição: . https://atomicdesign.bradfrost.com/chapter-2/ , 2016.