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

## Containers

A containerização é um assunto muito importante e um conhecimento mais que necessário pra quem deseja ingressar na carreira de DevOps, aqui irei recomendar alguns materiais para o aprendizado de Docker e Kubernetes que atualmente são as ferramentas mais utilizadas para se trabalhar com containers.

### Conteúdos para o aprendizado do Docker

Caso você não tenha nenhuma intimidade com o docker recomendo fortemente todas as leituras/tutoriais etc, que vou listar aqui, esse material foi selecionado com o intuito de facilitar o máximo o aprendizado desta ferramenta:

- [Docker Visão Geral](https://github.com/lorryaze/Guia-DevOps-Iniciante/blob/main/docker/docker.md)
- [Livro Descomplicando o Docker](https://livro.descomplicandodocker.com.br/chapters/chapter_01.html)

### Kubernetes

### Ferramentas de gerenciamento de configurações

Ansible, Chef, Salt, Puppet

### Provisionamento de Infra

Terraform

## Provedores de Nuvem

AWS

## Monitoramento e Gerenciamento de logs

## Conhecimentos fora do RoadMap DevOps para entrevistas de Emprego

Depois de aprender todos os conceitos acima é hora de se preparar para as entrevistas de emprego que são um ponto crucial para quem deseja ingressar no mercado de trabalho, geralmente as entrevistas de emprego para cargos de desenvolvimento costumam ter MUITOS pontos em comum estja você aplicando para uma vaga de Dev Frontend ou para uma vaga de DevOps. Conceitos como clean code e solid, arquitetura, desing system, estruturas de dados e questões de lógica de programação costumam cair em quase TODOS os processos seletivos de big techs.

Primeiramente já quero indicar a leitura do material disponivel neste repositório do git, ele foi criado com o intuito de preparar engenheiros de software a ingressarem em big techs como Amazon, Google etc, além de passar pelo principais tópicos que são abordados nestas entrevistas e anexa materiais muito interessantes sobre experiencias de pessoas que conseguiram passar nessas entrevistas e como elas fizeram isto. Eu realmente recomendo que queira você se tornar ou não um profissonal DevOps você faça a leitura e estude os conteúdos disponíveis neste repositório que é um achado muito completo e muito rico, neste repositório você encontra todas as informações sobre como se preparar para esse processo!:

- ### **Link do repositório:** [Coding Interview University](https://github.com/Guia-Devops-Iniciante/coding-interview-university#the-daily-plan)

Mas caso você não queira ler todo o conteúdo deste repositório eu vou deixar aqui um resumo do que acredito ser os principais conhecimentos esperados de uma pessoa Júnior para ingressar no mercado de trabalho, vou dar também algumas dicas que me ajudaram e ajudam já que também sou uma dev júnior que acabou de ingressar no mercado de trabalho, as recomendações que vou dar aqui são baseadas na minha experiência recente com processos seletivos de nível Júnior e com base nas leituras e pesquisas feitas para a realização do meu trabalho de conclusão de curso.

### Minha experiência com entrevistas e dicas

No fim do ano de 2021 até meados do inicio de 2022 eu estava aplicando para vagas de emprego como Dev Backend Júnior, fiz cerca de 5 processos seletivos e apliquei para cerca de 15 vagas, eu havia acabado de sair de um estágio e sentia a necessidade de ingressar no mercado de trabalho o mais depressa possível para melhorar a minha renda, como eu já estava no fim da faculdade decidi começar a aplicar, enviei currículos para diferentes empresas, recebi feedback da maioria, mesmo que fosse para dizer que meu perfil não se encaixava na vaga. 

Para os processos seletivos que passei a maioria tinha como primeira fase um pequeno teste com **questões de programação**, e conversando com amigos que são da área percebi que essa etapa costuma ser um gargalo onde poucas pessoas conseguem seguir mas que é um ponto muito importante para as empresas, já que estas querem profissionais que tenham uma boa lógica de programação e que saibam resolver problemas de forma eficiente, talvez por isso essa seja na maioria dos casos a primeira etapa das entrevistas, que elimina boa parte dos candidatos.

**E por quê isso acontece??**

Durante a minha graduação tive a sorte de ter amigos e professores que prezavam muito pelo ensino e aprendizado de conceitos relacionados a **Estrutura de Dados** e pela prática da resolução de problemas de programação competitiva que basicamente abordam problemas classicos da computação e utiliza algoritmos e as estruturas de dados conhecidas para resolve-los, entretanto mesmo dentro da minha faculdade nem todo mundo teve acesso a esses conteúdos, ou melhor, tiveram acesso a teoria, mas pouquissimas pessoas sabiam resolver bem esses problemas de programação, e as que sabiam, sabiam pois estavam de alguma forma envolvidas com a programação competitiva. E não coincidentemente essas pessoas quando saiam da faculdade para o mercado de trabalho eram as que conseguiam ingressar no mercado de trabalho em empresas como Amazon, Google, Facebook e por ai vai... 

Obviamente apenas isso não basta para que você consiga uma vaga como essas, mas esse é sem dúvidas um conhecimento que vai ser esperado de você, então sim é muito importante estudar esses conceitos e PRINCIPALMENTE PRÁTICAR! 

**E onde eu posso praticar??**

Se você não sabe nem por onde começar ou nunca teve contato com questões desse tipo, recomendo os exercícios do Beecrowd (antigo URI), nela você encontra exercícios iniciante que vão desde um "Hello Wolrd!" até problemas mais complexos de grafos, DP etc. (se você não ta entendendo esses termos recomendo voltar um pouco e ler o repo que recomendei ;))

O beecrowd tem uma plataforma bem intuitiva e que tem o formato de juiz online, isso quer dizer que você submete o código da sua solução para o problema e ele avalia se a solução é válida ou não, durante a submissão do seu problema você pode se deparar com alguns termos como TLE, runtime error etc, para entendelos basta clicar [aqui](https://www.beecrowd.com.br/judge/pt/answers) e ler ;)

- **Link Beecrowd**: [Beecrowd](https://www.beecrowd.com.br/). 

Outras ótimas opções são o LeetCode e o HackerRank que tem até as questões que mais costumam cair nas entrevistas (e cai mesmo pois em uma das entrevistas que fiz caiu um exercicio igual a uma que eu ja havia feito no leetcode), então recomendo fortemente que você resolva MUITAS questões e tente ir progredindo quando sentir que está ficando muito fácil. Lembre-se que a prática leva a perfeição e quanto mais prática mais rápido você irá responder as questões, vale lembrar que nessa etapa do processo seletivo costuma-se ter um tempo para a solução de um determinado número de questões.

**DICA: Os problemas dos processos seletivos costumam ter pesos, e esse peso aumenta de acordo com a dificuldade do problema, sendo assim tente resolver as questões masi faceis o mais rápido possível para que você possa ter mais tempo para fazer as questões mais dificeis, recomendo também começar pelas mais complicadas já que essas valem mais pontos, entretanto se você perceber que empacou numa questão vá para a próxima e retorne depois**

- **Link LeetCode**: [LeetCode](https://leetcode.com/problemset/all/). 
- **Link HackerRank**: [HackerRank](https://www.hackerrank.com/auth/signup). 






