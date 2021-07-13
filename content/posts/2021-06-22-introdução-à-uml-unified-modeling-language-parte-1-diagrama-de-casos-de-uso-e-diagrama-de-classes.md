---
template: post
title: "UML: Diagrama de Casos de Uso e Diagrama de Classes"
slug: introducao-a-uml
socialImage: /media/uml-unified-modeling-language-logo.png
draft: false
date: 2021-06-21T23:55:47.013Z
description: A UML (Unified Modeling Language) é uma linguagem de notação
  gráfica baseada na Orientação a Objeto utilizada para representar os
  requisitos de um projeto de software por meio de diagramas, facilitando a
  comunicação entre a equipe. Este artigo tem por objetivo abordar uma visão
  geral dos principais diagramas, bem como seus contextos de utilização.
category: engenharia de software
tags:
  - uml
  - engenharia-de-software
  - orientacao-a-objetos
---
A UML  (do inglês *Unified Modeling Language*, em português *Linguagem de Modelagem Unificada*) é uma linguagem de notação gráfica baseada na Orientação a Objeto utilizada para representar os requisitos de um projeto(design) de software por meio de diagramas. Existem dois tipos macros de diagramas, estruturais e comportamentais. 

Os diagramas estruturais permitem a visualização das partes que formam o sistema, como suas classes, e associações. Temos como exemplo os diagramas de classes ou componentes. Aqui o tempo não é considerado. 

Os diagramas comportamentais  definem a lógica, incluindo comportamento do código ou corpo do método. Neles o tempo importa, pois tratam-se de diagramas que envolve fluxos de mensagens e ciclo de vida do software ou interação. 

Neste artigo, serão apresentados os diagramas de casos de uso que pode auxiliar na confirmação e representação dos requisitos mapeados na análise e modelagem de requisitos do software e o diagrama de classes que é bastante utilizado para definir os domínios e associações entre os mesmo.

**1) Diagrama de casos de uso:** uma visão geral das interações entre o sistema, o usuário e os casos de uso.

![diagrama de caso de uso](/media/diagrama-em-branco.png "diagrama de caso de uso")

Considerando o diagrama acima, temos que:

* O leiloeiro e o usuário são considerados  **Atores**
* Leilão pode ser considerado o contexto, o **Sistema** em si
* As ações ou funcionalidades que o ator executa, como "Pagar um leilão", "Criar um leilão", entre outras, são consideradas os **casos de uso**

Observação: o ator não necessariamente representará um usuário, mas também pode representar  sistemas externos ou dispositivos de hardware.

Para Cockburn(2001), *um caso de uso captura o acordo entre o conhecedor do negócio do sistema e o comportamento dele*. Logo, esse diagrama tem por objetivo esclarecer entre os envolvidos/stakeholders quais são as funcionalidades do sistema e quem irá fazer uso delas, principalmente após a fase de levantamento de requisitos. 

**2) Diagrama de classes:** representa os objetos, ou domínios, e a relação entre eles. Ele oferece três formas de visualização, cada uma para um tipo de observador diferente. São elas: conceitual, especificação e implementação. Para saber mais detalhes sobre cada perspectiva, [clique aqui](http://www.dsc.ufcg.edu.br/~jacques/cursos/map/html/uml/diagramas/classes/classes1.htm).

![](/media/diagrama-em-branco-1-.png)



Acima temos uma representação simples, conceitual, onde podemos concluir que o usuário é dono de um leilão e também pode fazer lances. A classe Lance representa o relacionamento entre leilão e usuário. Por fim, temos o Job que tem a ação de fechar um leilão.

Portanto, com os exemplos anteriores, abordamos dois diagramas que podem ser utilizados para facilitar o mapeamento de ações em níveis estruturais, onde diversas partes compõem o sistema. Eles podem ser utilizados de maneira separada ou conjunta e cabe aos envolvidos personalizarem conforme suas necessidades, pois para garantir agilidade e manter a qualidade na comunicação não é necessário segui-los rigidamente.

**Referências**

PEREIRA, L. **Análise e Modelagem de Sistemas com a UML**. Edição: 1. Rio de Janeiro: , 2011.

VENTURA, P. **O que é UML (Unified Modeling Language)**. Edição: 1. Rio de Janeiro: Até o momento, 2019. Acesso disponível em: <https://www.ateomomento.com.br/diagramas-uml/>

VENTURA, P. **Entendendo o Diagrama de Classes da UML**. Edição: . Rio de Janeiro: Até o momento, 2021. Acesso disponível em: <https://www.ateomomento.com.br/uml-diagrama-de-classes/>

LARMAN, Graig. **Utilizando UML e Padrões: Uma introdução a análise e ao projeto orientados a objetos.** Porto Alegre: Bookman, 3a Edição, 2005

ONLINE, Alura Cursos. **UML Introdução: Modelagem de soluções**.  Rio de Janeiro/São Paulo: Alura, 2019.

LUCIDART, plataforma. **Tudo sobre diagrams de interação UML**. Acesso disponível em: <https://www.lucidchart.com/pages/pt/diagrama-de-interacao-uml>

COCKBURN , Alistair, **Escrevendo casos de uso eficazes**. São Paulo: Bookman, 2001.