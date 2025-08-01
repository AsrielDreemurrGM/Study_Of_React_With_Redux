<h1>Estudo de React com Redux</h1>
<p>
  This README is also available in <a href="./README.md">English</a>.
</p>
<h2>📌 Descrição</h2>
<p>
  Estudo prático utilizando <strong>React</strong>, <strong>Redux</strong> e <strong>Redux Toolkit Query</strong>.
  O projeto simula o carregamento de produtos a partir de um banco de dados falso utilizando o <code>json-server</code> e gerencia o estado com Redux.
</p>
<p>
  <strong>Importante:</strong> Para rodar o projeto corretamente, é necessário iniciar dois servidores:
</p>
<pre><code>npx json-server db.json --port 4000 --delay 1000</code></pre>
<pre><code>npm start</code></pre>
<h2>🚀 Tecnologias Utilizadas</h2>
<ul>
  <li>React</li>
  <li>Redux</li>
  <li>Redux Toolkit</li>
  <li>Redux Toolkit Query (RTK Query)</li>
  <li>TypeScript</li>
  <li>JSON Server</li>
  <li>React Hooks (useState, useEffect, useDispatch, useSelector)</li>
  <li>HTML5</li>
  <li>SPA (Single Page Application)</li>
</ul>
<h2>📦 Instalação</h2>
<pre><code>npm install</code></pre>
<h2>▶️ Executando o Projeto</h2>
<ol>
  <li>Instale as dependências:</li>
  <pre><code>npm install</code></pre>
  <li>Execute o mock da API (em um terminal separado):</li>
  <pre><code>npx json-server db.json --port 4000 --delay 1000</code></pre>
  <li>Inicie a aplicação React:</li>
  <pre><code>npm start</code></pre>
</ol>
<h2>📁 Estrutura de Pastas</h2>
<ul>
  <li><code>services/api.ts</code> – Configuração do serviço RTK Query</li>
  <li><code>store/</code> – Store e slices do Redux</li>
  <li><code>components/</code> – Componentes de interface</li>
  <li><code>db.json</code> – Banco de dados local usado pelo JSON Server</li>
</ul>
<h2>🎯 Objetivos</h2>
<ul>
  <li>Converter lógica de fetch para utilizar Redux e RTK Query;</li>
  <li>Compreender o carregamento assíncrono de dados com RTK Query e seu cache;</li>
  <li>Praticar a integração entre Redux Toolkit e APIs externas (simuladas);</li>
</ul>
