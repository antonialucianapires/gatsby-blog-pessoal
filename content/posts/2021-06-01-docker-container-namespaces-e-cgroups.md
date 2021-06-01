---
template: post
title: "Docker: Container, Namespaces e Cgroups"
slug: docker-container-namespaces-cgroups
socialImage: /media/arquitetura-docker.png
draft: false
date: 2021-06-01T02:59:27.518Z
description: Docker é uma ferramenta aberta (open source) que permite gerenciar
  os famosos containers Linux. No presente texto,que não pretende esgotar o
  assunto, reuni três conceitos que considero importante para entendimento
  inicial sobre a utilização desse recurso na área de tecnologia, sobretudo para
  o dia a dia de desenvolvedores.
category: infraestrutura, devops
tags:
  - docker
  - infraestrutura
  - docker
  - linux
---
Docker é uma ferramenta aberta (open source) que permite gerenciar os famosos containers Linux. No presente texto,que não pretende esgotar o assunto, reuni três conceitos que considero importante para entendimento inicial sobre a utilização desse recurso na área de tecnologia, sobretudo para o dia a dia de desenvolvedores.

# Para começar, isolamento

Entende-se por isolamento uma forma de empacotar uma aplicação com todos os recursos necessários para sua execução e, desse modo, o software sempre irá se comportar da mesma maneira, independente do ambiente (desenvolvimento, homologação e produção).

![pacote em desenvolvimento, produção e homologação](https://miro.medium.com/max/880/0*cQ8QuGaFZPeA7Ggv.png "pacote")

# O que é Docker?

Nesse contexto, o Docker é responsável por gerenciar vários processos, ou serviços, de maneira isolada do host, como banco de dados e uma aplicação, por exemplo, sendo executados em containers diferentes.

# Container, Namespaces e Cgroups

Seguindo uma definição básica,fornecida pelo blog [Escotilha Livre](https://escotilhalivre.wordpress.com/2015/06/22/usando-o-lxc-introducao/), containers são:

> *\[…] abstrações virtuais de uma técnica de virtualização conhecida como virtualização a nível de sistema operacional.*

Ele é uma forma de segregar processos e sua virtualização é considerada menos isolada pelo fato de existir o compartilhamento de partes do Kernel entre o host e o container. Isso torna a inicialização do processo uma execução rápida que pode levar segundos.

Essa separação, ou isolamento, é possível porque o Docker utiliza de dois recursos do Linux Kernel: Namespaces e Cgroups.

* Os [Namespaces](https://escotilhalivre.wordpress.com/2015/08/12/namespaces/) são responsáveis por gerar o isolamento de grupos de processos em seu nível lógico, como o gerenciamento de usuários, rede, etc., garantido que o container não enxergue os processos do host e vice-versa. Logo, ao criar um container, são criados namespaces como pid(Process ID) para isolar processos, net(Network) para controlar e isolar as redes de cada container,ipc(Inter Process Communication) que permite a comunicação entre processos, etc.
* Para gerenciar os recursos físicos que são compartilhados entre esses processos existe o [Cgroups](https://access.redhat.com/documentation/pt-br/red_hat_enterprise_linux/6/html/resource_management_guide/ch01). Ele fornece ao Docker o poder de compartilhar CPU, memória, I/O, etc., entre o host e o container. Além disso, é possível limitar ou restringir esses recursos para containers específicos.

![representação de namespaces e cgroups](https://miro.medium.com/max/880/0*SenPz_rdrQXd7nxL.png "namespaces e cgroups")

# Conclusão

Portanto, com base nesses conceitos iniciais é possível verificar benefícios na utilização dessa ferramenta como, velocidade, praticidade, agilidade, disponibilidade e economia de recursos. Nos próximos resumos pretende-se abordar conceitos mais focados na ferramenta, como imagem, volumes e muito mais.

## Referências

[Container docker: o que é e quais são as vantagens de usar?](https://www.meupositivo.com.br/panoramapositivo/container-docker/)\
[No final das contas: o que é o Docker e como ele funciona?](https://www.treinaweb.com.br/blog/no-final-das-contas-o-que-e-o-docker-e-como-ele-funciona/)\
[Linux namespaces](https://en.wikipedia.org/wiki/Linux_namespaces)\
[Namespace, o que é?](https://medium.com/@lets00/namespace-14c4e64d0559)\
[Capítulo 1. Introdução ao Grupos de Controle (Cgroups)](https://access.redhat.com/documentation/pt-br/red_hat_enterprise_linux/6/html/resource_management_guide/ch01)\
[Containers com Docker — Do desenvolvimento à produção](https://www.casadocodigo.com.br/products/livro-docker)