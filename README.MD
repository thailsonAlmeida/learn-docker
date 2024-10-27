# Objetivo
- Aprender como criar, administrar ambientes isolados através de containers com o Docker.

# Conceitos
## O que é preciso saber sobre containers?
- É um padrão de unidade de software que empacota código.
- É um padrão de unidade de software que empacota todas as dependencies de uma aplicação fazendo que a mesma seja executada rapidamente.
- É um padrão de unidade que permite a execução confiável de um ambiente computacional para outro.
- Quando falamos de containers falamos de processos e **namespace** que isala os processos.
- Quando falamos de containers, também falamos de **groups** que permite o isalamento dos recursos.
- Quando falamos de containers, também falamos de **file system** que permite executar somente o que precisa.
- A ideia da **imagem** quando trabalhamos com o container é trabalhar em camadas de dependencias.

## O que é preciso saber sobre o Docker
- A imagem é imutavel. Contém um estado imutável.
- Contém uma camada leitura e escrita.
- É executado por meio de um dockerfile que gera uma imagem.
- As imagens ficam num image registry.