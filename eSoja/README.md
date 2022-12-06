### 1° Semestre de 2022

## eSoja

## Projeto e Parceiro Acadêmico
O nomeado Aprendizagem por Projeto Integrador oferecido pela Faculdade de Tecnologia de São José dos Campos, FATEC - Prof° Jessen vidal tem como objetivo fazer com que os alunos acompanhem a evolução e crescimento do mercado atual e aprendam a agir com profissionalidade nessas mudanças.

## Escopo da Solução
A empresa parceira (Visiona) solicitou um aplicativo colaborativo para produtores rurais e através desse aplicativo os usuários poderão incluir informações do dia a dia sobre sua plantação. Essas informações consistem em dados alfa-numéricos e fotos georreferenciadas pelo GPS do próprio celular. Com os dados de vários usuários, o aplicativo irá fornecer informações estatísticas sobre sua produção, podendo assim comparar com dados históricos de outros usuários.

A equipe Cluster8 colocou como objetivo o desenvolvimento de um aplicativo contendo todas essas funcionalidades, com um foco aos produtores rurais, fazendo com que o aplicativo possa ser usado para armazenar os dados cadastrados mesmo sem conexão com a internet.

eSoja é o nome do aplicativo proposto pela equipe para solucionar o desafio, esse aplicativo ele deve entregar as seguintes funcionalidades:

1. Cadastro de propriedade;
2. Cadastro da área de cultivo;
3. Cadastro de amostras;
4. Previsão do Tempo;
5. Estatísticas do Plantio do usuário;
6. Login normal ou através do google, apple ou facebook;
8. Informações sobre o mercado;
9. Comparação Estatística por Região.

Foi então desenvolvido um aplicativo onde a pessoa consegue cadastrar sua plantação e gerando informações estatísticas sobre sua plantação, podendo acompanhar até mesmo a previsão do tempo no mesmo aplicativo.


# Tela de Login
<h1 align="center"> <img src = "https://github.com/cluster-8/esoja-mobile/blob/main/Gifs/LoginScreen.gif"/></h1>

Nessa tela, o usuário pode acessar o sistema através de um Login com e-mail e senha e também através do Google ou Facebook.

# Tela Home
<h1 align="center"> <img src = "https://github.com/elias31072002/teste/blob/main/Imagens/home.JPG"/></h1>

Nesta tela, é possível visualizar como está o preço das sementes de soja, ver qual temperatura está fazendo nesse momento. Na mesma tela é possível acessar o cadastro de propriedades, visualização de estatísticas , e o cadastro de talhões.

# Tela de Propriedades
<h1 align="center"> <img src = "https://github.com/cluster-8/esoja-mobile/blob/main/Gifs/create-property.gif"/></h1>

Nesta tela, é onde o cliente vai cadastrar uma nova propriedade onde será feito a plantação. Nessa mesma tela, é possível visualizar as propriedades já existentes

# Tela de Talhões
<h1 align="center"> <img src = "https://github.com/cluster-8/esoja-mobile/blob/main/Gifs/amostras.gif"/></h1>

Nesta tela, é possível cadastrar um novo talhão, onde terá cada passo a seguir colocando informações sobre a plantação.

# Tela de Estatísticas
<h1 align="center"> <img src = "https://github.com/cluster-8/esoja-mobile/blob/main/Gifs/expectativa-producao.gif"/></h1>

Na tela de estatísticas é onde o cliente poderá ver a expectativa de produção, a expectativa de lucro bruto, a média de produtividade da regição, a produtividade e produtividade média do município, os níveis de precipitação e o balanço e deficiência hídrica da plantação.


<br>

Acesse o repositório do projeto desenvolvido:

[eSoja](https://github.com/cluster-8/esoja-mobile)
<br>
<br>


## Tecnologias Utilizadas
<br>

<img src = "https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" width="70" height="40"/> 

A ferramenta Figma foi utilizada para fazer o protótipo do projeto, criando exemplos de telas e aplicando as idéias seguindo os requisitos abordados pela empresa parceira.

Figma é um editor gráfico de vetor e prototipagem de projetos de design baseado principalmente no navegador web, com ferramentas offline adicionais para aplicações desktop para GNU/Linux, macOS e Windows.
<br>
<br>
<br>

<img src = "https://camo.githubusercontent.com/281c069a2703e948b536500b9fd808cb4fb2496b3b66741db4013a2c89e91986/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f506f737467726553514c2d3331363139323f7374796c653d666f722d7468652d6261646765266c6f676f3d706f737467726573716c266c6f676f436f6c6f723d7768697465" width="180" height="50" /> 

Para armazenar os dados das propriedades, dos talhões, assim como os usuarios e senhas cadastrados, foi utilizado o banco de dados PostgreSQL.

PostgreSQL é um sistema gerenciador de banco de dados objeto relacional, desenvolvido como projeto de código aberto.
<br>
<br>
<br>

<img src = "https://camo.githubusercontent.com/0b9bce580a369d91352cf37397f1e079ef104531fc0bc53a145deb8f43fca535/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f52656163745f4e61746976652d3230323332413f7374796c653d666f722d7468652d6261646765266c6f676f3d7265616374266c6f676f436f6c6f723d363144414642" width="180" height="50" /> 

Para o desenvolvimento da estrutura do aplicativo (front-end) assim como suas funcionalidades visuais foi usado a linguagem React Native.

O React Native é um framework baseado no já aclamado React, desenvolvido pela equipe do Facebook, que possibilita o desenvolvimento de aplicações mobile, tanto para Android, como para iOS, utilizando apenas Javascript.
<br>
<br>
<br>

<img src = "https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" width="70" height="40" /> 

Para o desenvolvimento do back-end foi utilizado o NestJS, com foco na configuração de rotas das páginas do aplicativo, a integração com o front-end e envio de dados para o banco de dados.

Nest.js é um framework node.js progressivo feito para criar aplicações de backend eficientes, escaláveis e confiáveis.
<br>
<br>
<br>


## Contribuições Pessoais
Nesse projeto eu trabalhei como o Scrum Master da equipe, fiquei responsável por juntamente com a equipe definir o que seria entregue em cada sprint, a partir disso, atribuindo as tarefas para cada integrante da equipe.
Fiquei responsável também por atribuir um tempo para cada tarefa, e a partir disso, usando a ferramenta Excel, criar um Burndown mostrando toda a trajetória da equipe durante a sprint.
Como Scrum Master eu também trabalhei, diretamente no github ou utilizando o software Visual Studio Code, na escrita do README de cada sprint.


## Hard Skills

Utilização da plataforma GitHub e o software Git: Sei fazer com autonomia.

Utilização do Figma: Sei fazer com autonomia.

Utilização do Visual Studio Code: Sei fazer com autonomia.


## Soft Skills
Comunicação - Importante para o compartilhamento de ideias e visões futuras referente ao projeto.

Exemplo: Durante as reuniões semanais, cada integrante da equipe teve sua chance de compartilhar suas ideias.

Foco- Ao ser atribuidas as tarefas para cada integrante foi importante cada um focar no que foi atribuido a ele.

Exemplo: A pessoa não se desviou em nenhum momento ao que lhe foi atribuido.

Organização- Após estudar com mais profissionalidade a metodologia Scrum, a organização foi fundamental para manter o foco da equipe em suas funções.

Exemplo: Estruturação das entregas com mais clareza e de fácil entendimento, não causando nenhum atraso desnecessário.



















