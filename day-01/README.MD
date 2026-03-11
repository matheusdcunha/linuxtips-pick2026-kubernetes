# Resumo Day 01

Neste dia começamos nossa jornada no **Kubernetes**.

## Containers

Nós começamos estudando sobre containers e entendemos mais a fundo sobre container engine e container runtime. Vimos que o **Kubernetes** deixou de utilizar o Docker Engine, porém continua usando o mesmo runtime do Docker, o **containerd**.

Também falamos sobre uma visão mais romântica da criação do k8s e da **OCI**.

## Kubernetes

Agora que já vimos o background, vamos para o **Kubernetes** em si.

Ele é um orquestrador de containers, responsável por organizar e gerenciar os containers. O **k8s** automatiza o trabalho de gerenciar múltiplos containers, garantindo que a aplicação funcione sem parar, de forma eficiente e sem dor de cabeça.

## Componentes

O **k8s** é dividido em **nodes**, que são máquinas virtuais ou físicas que atuam como o ambiente de execução dentro do **cluster**. O **cluster** é um conjunto unificado e coordenado de **nodes** configurados para trabalhar em conjunto na execução de aplicações.

Os nodes são divididos em: **Control Plane** e **Workers**.

* O **Control Plane** é responsável por controlar, garantir a saúde, a disponibilidade, a capacidade e armazenar o estado do cluster.
* Os **Workers** são os nodes onde as aplicações vão rodar.

Também vimos uma introdução simples a: **Pods**, **ReplicaSets**, **Deployments** e **Services**.

## Kind e kubectl

Em seguida, vimos sobre o **kind**, uma maneira de criar um cluster **k8s** local para testes e aprendizado. Ele utiliza o Docker, fazendo cada **node** ser um **container**.

Para finalizar, vimos o `kubectl`, a maneira de se comunicar e executar comandos dentro de um cluster. Ele é bem tranquilo, seus comandos seguem um padrão fácil de se acostumar e sua documentação é ótima.