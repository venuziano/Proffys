<img alt="Banner" src="./assets/banner.png">

<h1 align="center">Proffy</h1>
<p align="center">Aplicativo <i>web</i> e <i>mobile</I> para conectar professores e estudantes.</p>

<h4 align="center"> 
  :heavy_check_mark:  Proffy 🚀 Finalizado  :heavy_check_mark:
</h4>

<p align="center">
  <img alt="used languages" src="https://img.shields.io/badge/languages-4-green">  
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/venuziano/Proffys">
  <img alt="used license" src="https://img.shields.io/github/license/venuziano/Proffys">
</p>

<img class="emoji" alt="computer" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f4bb.png"> Sobre o projeto
=================

<p> Proffys é um aplicativo que busca conectar professores de diversas áreas e estudantes dos mais variados campos em uma só plataforma. Os estudantes podem procurar a aula do interesse e após, realizar o contato com o professor. </p>

<h2><a fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2699.png"><img class="emoji" alt="gear" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2699.png"></g-emoji> Funcionalidades</h2>

<ul>
  <li>
  <p> Os professores podem se cadastrar informando:</p>
    <ul class="contains-task-list">
      <li> Seu nome completo; </li>
      <li> Avatar para o perfil; </li>
      <li> Whatsapp;</li>
      <li> Quais aulas lesionam; </li>
      <li> Custo da aula por hora; </li>
      <li> Horários disponíveis. </li>
    </ul>
  </li>
</ul>

<ul>
  <li>Os alunos podem procurar os professores por filtro de nome da aula e horário "De" e "Até".</li>
</ul>

<ul>
<li> Os usuários tem acesso ao aplicativo móvel, onde podem:
  <ul>
    <li> Procurar professores para as aulas; </li>
    <li> Favoritar e "desfavoritar" professores. </li>
  </ul>
</li>
</ul>



<img class="emoji" alt="art" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f3a8.png"> Demonstração da aplicação
=================
Mobile:
<p align="center">
  <img alt="Procurar aulas" src="./assets/proffys.gif">
</p>

Web:
<p align="center" >
  <img alt="Procurar aulas" src="./assets/study.png">
</p>

<h2><a fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f680.png"><img class="emoji" alt="rocket" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f680.png"></g-emoji> Como executar o projeto</h2>
<p>Este projeto é divido em três partes:</p>
<ol>
  <li>Backend (pasta server)</li>
  <li>Frontend (pasta web)</li>
  <li>Mobile (pasta mobile)</li>
</ol>
<p><g-emoji class="g-emoji" alias="bulb" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4a1.png"><img class="emoji" alt="bulb" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f4a1.png"></g-emoji>Tanto o Frontend quanto o Mobile precisam que o Backend esteja sendo executado para funcionar.</p>

<h3><a></path></svg></a>Pré-requisitos</h3>

<p>Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
<a href="https://git-scm.com" rel="nofollow">Git</a>, <a href="https://nodejs.org/en/" rel="nofollow">Node.js</a>.
Além disto é bom ter um editor para trabalhar com o código como <a href="https://code.visualstudio.com/" rel="nofollow">VSCode</a></p>

<h4><a fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3b2.png"><img class="emoji" alt="game_die" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f3b2.png"></g-emoji> Rodando o Backend (servidor)</h4>

<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> Clone este repositório</span>
$ git clone https://github.com/venuziano/Proffys

<span class="pl-c"><span class="pl-c">#</span> Acesse a pasta do projeto no terminal/cmd</span>
$ <span class="pl-c1">cd</span> README.md

<span class="pl-c"><span class="pl-c">#</span> Vá para a pasta server</span>
$ <span class="pl-c1">cd</span> server

<span class="pl-c"><span class="pl-c">#</span> Instale as dependências</span>
$ yarn install

<span class="pl-c"><span class="pl-c">#</span> Execute a aplicação em modo de desenvolvimento</span>
$ yarn start

<span class="pl-c"><span class="pl-c">#</span> O servidor inciará na porta:3333 - acesse http://localhost:3333 </span>
</pre></div>

<h4><a fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f9ed.png"><img class="emoji" alt="compass" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f9ed.png"></g-emoji> Rodando a aplicação web (Frontend)</h4>

<pre><span class="pl-c"><span class="pl-c">#</span> Clone este repositório</span>
$ git clone https://github.com/venuziano/Proffys

<span class="pl-c"><span class="pl-c">#</span> Acesse a pasta do projeto no seu terminal/cmd</span>
$ <span class="pl-c1">cd</span> README.md

<span class="pl-c"><span class="pl-c">#</span> Vá para a pasta da aplicação Front End</span>
$ <span class="pl-c1">cd</span> web

<span class="pl-c"><span class="pl-c">#</span> Instale as dependências</span>
$ yarn install

<span class="pl-c"><span class="pl-c">#</span> Execute a aplicação em modo de desenvolvimento</span>
$ yarn start

<span class="pl-c"><span class="pl-c">#</span> A aplicação será aberta na porta:3000 - acesse http://localhost:3000</span>
</pre>

<h2><g-emoji class="g-emoji" alias="hammer_and_wrench" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6e0.png">🛠</g-emoji> Tecnologias </h2>

<h4><a href="https://github.com/tgmarinho/Ecoleta#server-nodejs--typescript"></a><strong>Server</strong> (<a href="https://nodejs.org/en/" rel="nofollow">NodeJS</a> + <a href="https://www.typescriptlang.org/" rel="nofollow">TypeScript</a>)</h4>

<ul>
  <li><strong><a href="https://expressjs.com/" rel="nofollow">Express</a></strong></li>
  <li><strong><a href="https://expressjs.com/en/resources/middleware/cors.html" rel="nofollow">CORS</a></strong></li>
  <li><strong><a href="http://knexjs.org/" rel="nofollow">KnexJS</a></strong></li>
  <li><strong><a href="https://github.com/mapbox/node-sqlite3">SQLite</a></strong></li>
  <li><strong><a href="https://github.com/TypeStrong/ts-node">ts-node</a></strong></li>
</ul>

<h4><strong>Website</strong> (<a href="https://reactjs.org/" rel="nofollow">React</a> + <a href="https://www.typescriptlang.org/" rel="nofollow">TypeScript</a>)</h4>

<ul>
  <li><strong><a href="https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom">React Router Dom</a></strong></li>
  <li><strong><a href="https://github.com/axios/axios">Axios</a></strong></li>
</ul>

<h4><a href="https://github.com/tgmarinho/Ecoleta#mobile-react-native--typescript"></a><strong>Mobile</strong> (<a href="http://www.reactnative.com/" rel="nofollow">React Native</a> + <a href="https://www.typescriptlang.org/" rel="nofollow">TypeScript</a>)</h4>

<ul>
  <li><strong><a href="https://expo.io/" rel="nofollow">Expo</a></strong></li>
  <li><strong><a href="https://github.com/expo/google-fonts">Expo Google Fonts</a></strong></li>
  <li><strong><a href="https://reactnavigation.org/" rel="nofollow">React Navigation</a></strong></li>
  <li><strong><a href="https://github.com/axios/axios">Axios</a></strong></li>
  <li><strong><a href="https://github.com/react-native-community/async-storage" rel="nofollow">AsyncStorage</a></strong></li>
  <li><strong><a href="https://github.com/software-mansion/react-native-reanimated" rel="nofollow">React Native Reanimated</a></strong></li>
</ul>

<h2><a fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f9b8.png"><img class="emoji" alt="superhero" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f9b8.png"></g-emoji> Autor</h2>

<img style="border-radius: 50%;" src="https://avatars3.githubusercontent.com/u/15386984?s=460&u=a927908b5d7306d6d5eb234da4094b4a9c7dbdb4&v=4" width="100px;" alt="" style="max-width:100%;">

<sub><b>Rafael Rodrigues</b></sub>
<img class="emoji" alt="rocket" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f680.png">

[![Linkedin Badge](https://img.shields.io/badge/-Rafael-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rafaelRodr1gues/)](https://www.linkedin.com/in/rafaelRodr1gues/) 
[![Gmail Badge](https://img.shields.io/badge/-rafael.silva@universo.univates.br-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:rafael.silva@universo.univates.br)](mailto:rafael.silva@universo.univates.br)

<h2><a fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4dd.png"><img class="emoji" alt="memo" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/1f4dd.png"></g-emoji> Licença</h2>

<p>Este projeto está sobe a licença <a href="https://github.com/venuziano/Proffys/blob/master/LICENSE">MIT</a>.</p>
