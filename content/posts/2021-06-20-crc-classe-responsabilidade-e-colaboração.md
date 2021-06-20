---
template: post
title: "CRC: Classe, Responsabilidade  e Colaboração"
slug: crc-classe-acoplamento-colaboracao
socialImage: /media/crc-.png
draft: false
date: 2021-06-20T04:03:30.515Z
description: "CRC (Classe, Responsabilidade e Colaboração) é uma técnica de
  modelagem, inicialmente utilizada para aprendizado, baseada no paradigma de
  programação orientado a objetos. "
category: Orientação a Objetos, Design de Software, Extreme Programming
tags:
  - OO
  - engenharia
  - software
  - crc
  - modelagem
---
CRC (Classe, Responsabilidade e Colaboração) é uma técnica de modelagem proposta por Kent Back e Ward Cunningghan, em 1989. A princípio, esta técnica era vista como uma ferramenta de auxílio na aprendizagem do paradigma orientado a objetos, mas, devido a sua simplicidade e rapidez na identificação de classes, se popularizou entre estudantes e praticantes de Orientação a Objetos e UML. 

A identificação das classes e suas responsabilidades é feita através de sessões onde estarão reunidos desenvolvedores, projetistas, analistas de domínio, entre outros. Com o auxílio de um cartão CRC, os envolvidos mapeiam os membros da classe.

![Cartão CRC](/media/crc-.png "Exemplo de cartão CRC")

No contexto do aprendizado, a informalidade garante um caminho simples na consolidação de conceitos bases na orientação a objetos. A seguir, iremos entender o que é cada conceito do acrônimo CRC:

* **Classe:** estrutura, ou abstração, na qual podemos reunir membros e comportamentos. Elas servem de "modelo" para criar objetos, que são únicos.
* **Responsabilidade:** representa as obrigações esperadas da classe para o sistema em questão, ou seja, é aquilo que a classe conhece ou faz. Logo, existem dois tipos de responsabilidades:

  * que fornece informações (conhece)
  * que realiza alguma ação (faz)
* **Colaboração:** responsabilidade de uma classe colaboradora

Portanto, objetos possuem responsabilidades que podem ser de conhecimento ou realizações. Às vezes, para realizar estas responsabilidades, um objeto necessita colaborar com outros objetos do sistema. A colaboração pode ser entendida como a associação entre as classes e as responsabilidades estão contidas na ideia de atributos e métodos.

**Referências**

Bezerra, E. *Princípios de Análise e Projeto Orientados a Objetos com UML*. Ed. Campus, Cap 5.

FUNDAMENTOS de projeto e especificação de software - Cartões CRC. Produção: Douglas G. Macharet. Minas Gerais: PDS2-DCC-UFMG, 2020. Disponível em: <https://www.youtube.com/watch?v=biwkCaftRG8>.