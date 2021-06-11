---
template: post
title: Modelos de Processo de Software na perspectiva de Roger Pressman
slug: modelos-de-processo-de-software-na-perspectiva-de-roger-pressman
socialImage: /media/1_5y6cjamdzzbwg-uah3dxjg.png
draft: false
date: 2021-06-11T02:52:34.793Z
description: A Engenharia de Software reúne processos, métodos e desenvolvimento
  de software apoiada por ferramentas que automatizam o processo em si, tornando
  a realização do objetivo mais prática e ágil. Antes de abordar o tema
  principal, é importante destacar as definições de métodos, ferramentas e
  processo.
category: engenharia de software
tags:
  - processos
  - engenharia
  - software
---
A *Engenharia de Software* reúne processos, métodos e desenvolvimento de software apoiada por **ferramentas que automatizam o processo** em si, tornando a realização do objetivo mais prática e ágil. Antes de abordar o tema principal, é importante destacar as definições de métodos, ferramentas e processo.

![Imagem com quatro camadas da engenharia de software: ferramentas, métodos, processo e foco na qualidade.](/media/1_5y6cjamdzzbwg-uah3dxjg.png "Camadas da engenharia de software")

(PRESSMAN, 2016. p. 16)

De acordo com Pressman, a engenharia de software é composta por camadas onde **a base principal deve ser a qualidade**. Logo, torna-se necessário que todos os envolvidos estejam comprometidos e promovam uma cultura de aperfeiçoamento contínuo do processo de desenvolvimento de software.

O **processo pode ser definido como um roteiro** que possui etapas, atividades e artefatos que garantem uma entrega de qualidade e dentro do prazo estabelecido.

As etapas de um processo podem ser realizadas através de métodos. Os **métodos de engenharia de software podem ser traduzidos como técnicas**, ou formas de ser fazer algo baseadas em princípios básicos,para desenvolver software onde cada uma delas é composta por diferentes tarefas, a saber: comunicação, requisitos, modelagem, etc.

**Para apoiar o processo e a execução dos métodos, existem as ferramentas**. Portanto, esses três conceitos conduzem um desenvolvimento de qualidade guiado por fundamentos da engenharia.

**Processo de Software**

O processo de software é considerado um dos fatores essenciais na definição de sucesso de empresas que desenvolvem software. Em diferentes literaturas, podemos enxergar o conceito de processo como uma sequência de passos que apontam para um objetivo e, no contexto de desenvolvimento, temos que a integração de pessoas, ferramentas e metodologias podem gerar produtos de qualidade e de grande valor para os clientes.

Para esse conceito, Pressman também oferece uma descrição e cabe aqui reforçar. Segundo ele, processo é

> *…um conjunto de atividades, ações e tarefas realizadas na criação de algum artefato.*

Em sua obra, o autor também referencia à definição dada por Ivar Jacobson, Grady Booch e James Rumbaugh, onde

> *Um processo define quem está fazendo o quê, quando e como para atingir determinado objetivo.*

Em síntese, *processo é o que você faz* e a forma de fazer impacta diretamente no resultado. Neste contexto, a engenharia de software propõe diferentes modelos de processos que definem a sequência em que as atividades serão realizadas.

**Modelo de Processo Genérico**

Segundo Roger Pressman, engenheiro de software e autor, **existem atividades comuns entre os modelos de processos** e elas podem ser divididas em dois grupos: atividades metodológicas e atividades de apoio.

![Imagem com o processo de software detalhado.](/media/processo-software-pressman.png "Atividades comuns nos modelos de processos")

(PRESSMAN, 2016. p. 32)

* **Atividades metodológicas:** comunicação, planejamento, modelagem, construção e entrega.
* **Atividades de apoio:** controle e acompanhamento do projeto, administração de riscos, garantia de qualidade, revisões técnicas, medição, gerenciamento de configuração de software, gerenciamento da reusabilidade, reparo e produção de artefatos.

Todos os modelos podem incluir essas atividades básicas, porém, cada um deles terá suas atividades especificas de acordo com variáveis como tamanho da equipe, complexidade do projeto que será desenvolvido e entre outros fatores que definem o contexto do desenvolvimento.

**Principais modelos de processos de software**

Modelos de processos de software são utilizados para demonstrar diferentes formas do desenvolvimento de software e, dessa maneira, definem a sequência em que as atividades serão executadas. Serão abordados, de maneira simplificada, os modelos Cascata (ou Clássico), Incremental, Evolucionário.

1. **Modelo em Cascata ou Clássico**

O modelo em Cascata, também conhecido como modelo clássico, possui uma abordagem **sequencial e sistemática.**

![](https://miro.medium.com/max/30/1*dcfjA5rdRDw8HQPCwlnGhQ.png?q=20)

![Imagem com as atividades básicas do modelo em cascata](/media/modelo-cascata.png "Modelo em cascata")

(PRESSMAN, 2016. p. 42)

Dessa maneira, a etapa seguinte não deve iniciar até que a fase anterior tenha sido concluída, como exemplifica a imagem acima. A seguir serão descritas as vantagens e as desvantagens:

**Vantagens**

* Quando bem utilizado, não permite pular fases
* Todas as fases são igualmente importantes
* Foco no planejamento
* Garantia de que não haverá falhas em cada fase

**Desvantagens**

* Projetos reais raramente são sequenciais
* Exige que os requisitos estejam bem definidos à priori
* Torna caro corrigir erros cometidos em fases iniciais
* Adia a identificação de riscos
* Atrasa e agrupa testes de sistema, o que dificulta a integração
* Não realiza entrega parciais do produto
* Não se adapta facilmente às mudanças de requisitos

De acordo com essas características, o modelo em Cascata é indicado para produções onde os requisitos são bem compreendidos e possuem pouca probabilidade de mudanças.

**2. Modelo incrementa**l

> *O modelo incremental libera uma série de versões, denominadas incrementos, que oferecem, progressivamente, maior funcionalidade ao cliente à medida que cada incremento é entregue.* — PRESSMAN, 2016.p.44

Para casos em que seja necessário entregas parciais de software, pode-se utilizar o modelo incremental. Ele propõe a **entrega do produto essencial** no primeiro momento, onde funcionalidade básicas são entregues para o cliente e a cada entrega feita em diante serão entregues funcionalidades mais avançadas, novas funcionalidades ou melhorias nas funcionalidades entregues.

![Imagem com o fluxo de atividades do modelo incremental](/media/modelo-incremental.png "Modelo incremental")

> (PRESSMAN, 2016. p. 44)

Na imagem acima, é possível verificar que esse modelo aplica sequências lineares a medida em que vai avançando. Cada sequência gera um incremento que é uma entrega de software funcional

Vantagens

* Os usuários poderão utilizar o software antes do mesmo estar 100% finalizado
* É possível retornar em etapas, reduzindo o risco de uma entrega fracassada
* Pode ser utilizado por um time reduzido
* Antecipação de problemas

Desvantagens

Não há desvantagens em sua utilização, mas alguns pontos que devem ser considerados na escolha desse modelo.

**3. Modelo Evolucionário**

> *Os modelos de processo evolucionário produzem uma versão cada vez mais completa do software a cada iteração.*

Modelos evolucionários são iterativos ou incrementais e atendem a cenários em que o software irá sofrer constantes mudanças. Serão apresentados dois modelos evolucionários: prototipação e espiral.

**3.1 Prototipação**

> *Quando seu cliente tiver uma necessidade legítima, mas sem a mínima ideia em relação aos detalhes, faça um protótipo como uma primeira etapa.*

A abordagem da prototipação pode ser utilizada quando o cliente ainda não possui clareza e detalhe da sua necessidade, pois ela auxilia na identificação dos requisitos do software.

![](/media/prototipacao.png "Prototipação")

![](<>)

(PRESSMAN, 2016. p. 45)

Logo, as iterações ocorrem à medida em que o protótipo se regula às necessidades do usuário e, apesar de ser independente, esse modelo pode ser utilizado com outros processos apresentados anteriormente.

**3.2 Espiral**

> A iteração vai ocorrendo conforme vamos ajustando o protótipo às necessidades dos usuários.

![](/media/espeiral.png)

![](<>)

(PRESSMAN, 2016. p. 48)

O modelo espiral, proposto por Boehm, é dividio em atividades metodológicas onde cada atividade representa um ponto do caminho na espiral. Sempre iniciamos pelo centro da espiral e continuamos no sentido horário. Segundo Pressman,

> *O primeiro circuito em volta da espiral pode resultar no desenvolvimento de uma especificação de produto; passagens subsequentes em torno da espiral podem ser usadas para desenvolver um protótipo e, então, progressivamente, versões cada vez mais sofisticadas do software.*

**Conclusão**

Neste artigo, vimos o que é um processo de softwares e alguns modelos mais conhecidos na engenharia. Porém, existem outros como modelo concorrente, modelo orientado à componentes e entre outros.

Não existe um processo certo ou errado, bem como não existe um modelo de desenvolvimento que seja universal para resolver todos os problemas do desenvolvimento de software.

A escolha de um modelo ou processo depende do software que se pretende desenvolver, do contexto inserido, da equipe e entre outros n fatores onde a utilização desses modelos pode ser vantajosa ou não.

**Referências bibliográficas**

PRESSMAN, Roger S.; MAXIM, Bruce R. **Engenharia de software**: uma abordagem profissional. 8. ed. Porto Alegre: AMGH, 2016.

MEDEIROS, HIGOR. **Introdução aos Processos de Software e o Modelo Incremental e Evolucionário**. 1. DevMedia, 2013. Disponível em: <https://www.devmedia.com.br/introducao-aos-processos-de-software-e-o-modelo-incremental-e-evolucionario/29839.> Acesso em: 5 maio 2021.