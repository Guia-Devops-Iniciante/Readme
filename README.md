# Guia Devops Iniciante

Esta organização foi criada com o intuito de ser um guia para quem deseja iniciar os estudos na área de DevOps, aqui nós iremos agrupar repositórios e matériais necessários para quem deseja ingressar nesta área. 

O conteúdo aqui agrupado foi selecionado com base em um roadmap de devops iniciante realizado no Trabalho de Conclusão de Curso 1 Formação de Profissionais DevOps/SRE: processos seletivos e os desafios de ingresso no mercado de trabalho, aqui daremos continuidade ao trabalho previamente iniciado sendo esta organização parte do Trabalho de Conclusão de Curso 2.

## O que é DevOps?

A palavra DevOps surge basicamente da união de desenvolvimento + operações, a área de desenvolvimento cuida basicamente da criação de código, testes da aplicação etc, enquanto a parte de operações é responsável por fazer o deploy da aplicação, manter os servidores etc, com a união dessas áreas os desenvolvedores que antes se dividiam entre os dois gurpos citados, agora passam a trabalhar em todo o ciclo de desenvolvimento do software, desde a fase de desenvolvimento até a parte de implantação.

A prática de DevOps surge com o intuito de agilizar e automatizar a entrega de softwar, dentro de um pipeline DevOps temos práticas como a integração contínua, entrega contínua e testes contínuos que nos ajudam com o inutito inicial.

Para um melhor entendimento recomendo esta leitura: [O que é DevOps? - AWS](https://aws.amazon.com/pt/devops/what-is-devops/).

## RoadMap de Conhecimentos para DevOps Iniciante


Para se tornar um profissional devops você precisa aprender conceitos relacionados a ambas as áreas (Dev & Ops) e para facilitar o entendimento do que este profissional precisa saber, desenhamos um roadmap para DevOps iniciantes.

Baseado no [Roadmap DevOps](https://roadmap.sh/devops) e no perfil do profissional DevOps Júnior traçado nas pesquisas realizadas para o TCC1, elaboramos o seguinte roadmap de conhecimentos que são essenciais ou aconselhaveis para quem deseja iniciar na área.

<img width="1002" alt="image" src="https://user-images.githubusercontent.com/30262806/188697339-de793e52-2d08-445d-bff6-4c586baab38c.png">

## Por que utilizar este conteúdo?

# Plano de Estudo (tipo um sumário)

## Como Utilizar o Plano de estudo

## Linguagem de programação 

O primeiro passo para quem deseja ingressar na carreira de DevOps é aprender uma linguagem de programação, de preferência uma linguagem de script. Neste roadmap recomendei Python como principal liguagem a ser aprendida primeiro por que através da análise de vagas realizada na parte 1 deste trabalho é possível observar que Python é um pré-requisito obrigatório para a grande maioria das vagas de DevOps Júnior, de 14 vagas observadas 7 pediam Pyhton e as outras 7 não especificavam uma linguagem de programação. De acordo com a [Pesquisa de Desenvolvimento  2021](https://insights.stackoverflow.com/survey/2021#developer-profile-key-territoriesfeita) pelo StackOverflow temos Python (48.24%) como a segunda linguagem de programação mais popular entre os desenvolvedores.

Além de tudo isso a linguagem Python tem uma vasta documentação feita pela comunidade de Python que é muito engajada, isso facilita muito o aprendizado da linguagem, além disso Python tem uma sintaxe intuitiva e é uma linguagem muito robusta e completa.

## Gerenciamento e Versionamento de Código

Gerenciamento de código nada mais é do que monitorar e gerenciar mudanças feitas no código, fazer isso manualmente seria uma tarefa muito dificil já que para termo um bom controle é necessário que mantenhamos um histórico dessas alterações, que tivessemos um jeito seguro de agregar as novas alterações há um código que ja existe sem quebrar o seu comportamento etc. Para temos ferramentas de gerenciamento que nos permimtem manter esse histórico, mesclar o código, resolver conflitos existentes etc. A ferramente de gerenciamento de código mais robusta e mais utilizada que temos é o Git, sendo assim é de extrema importância que os desenvolvedores saibam usa-lá, na verdade saber git é um pré-requisito básico. 

Entretanto assim como em todas as outras tecnologias existem niveis de git e aqui traremos materiais para que você aprenda o básico e continue aprendendo o quanto desejar evouluir nesta ferramenta. 

### Introdução ao Git

Se você nunca viu nada sobre git antes recomendo a leitura e execução dos materiais e tutoriais abaixo:

- [O Básico do Git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-O-B%C3%A1sico-do-Git)
- [Git - O minímo que você precisa para saber trabalhar em equipe](https://blog.cedrotech.com/git-o-minimo-que-voce-precisa-saber-para-trabalhar-em-equipe)
- [Guia prático de git para iniciantes](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
- [Resolvendo conflitos de Git](https://medium.com/zeroeumas/resolvendo-conflitos-de-git-a90097b2c4d4)
- [Learning git Branching - Jogo Iterativo para aprender Git](https://learngitbranching.js.org/?locale=pt_BR)

Além disso temos também os seguintes repositórios que são bem completos quanto aos ensinamentos de git porém recomendo a leitura destes depois que você já tiver criado uma afinidade com os comando básicos de git. 

- [Git-flight-rules](https://github.com/Guia-Devops-Iniciante/git-flight-rules)

Pra dar uma facilitada vou deixar aqui uma lista com os principais comandos básicos do git: 

- $ git log -> leia até sobre git log --stat
- $ git status
- $ git diff
- $ git add path/to/file
- $ git add -p
- $ git add .
- $ git commit
- git commit -m "A mensagem de commit"
- git commit --amend
- git pull
- $ git pull --rebase
- $ git rebase --continue
- $ git push
- $ git merge


## Gerenciamento de Servidores

### Sistemas operacionais 

## Trabalhar utilizando o Terminal

## Redes e Protocolos

## Servidores Web

## Aprender ferramentas de CI/CD

## Infra como Código

### Containers

Docker e Kubernetes

### Ferramentas de gerenciamento de configurações

Ansible, Chef, Salt, Puppet

### Provisionamento de Infra

Terraform

## Provedores de Nuvem

AWS

## Monitoramento e Gerenciamento de logs

## Conhecimentos fora do RoadMap DevOps para entrevistas de Emprego


