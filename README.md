<h1>Study of React with Redux</h1>
<p>
  Este README também está disponível em <a href="./README.pt-br.md">Português</a>.
</p>
<h2>📌 Description</h2>
<p>
  Practical study using <strong>React</strong>, <strong>Redux</strong>, and <strong>Redux Toolkit Query</strong>.
  The project simulates loading products from a mock database using <code>json-server</code> and manages state using Redux.
</p>
<p>
  <strong>Important:</strong> To run the project correctly, you must start both servers:
</p>
<pre><code>npx json-server db.json --port 4000 --delay 1000</code></pre>
<pre><code>npm start</code></pre>
<h2>🚀 Technologies Used</h2>
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
<h2>📦 Installation</h2>
<pre><code>npm install</code></pre>
<h2>▶️ Running the Project</h2>
<ol>
  <li>Install dependencies:</li>
  <pre><code>npm install</code></pre>
  <li>Run the mock API (in a separate terminal):</li>
  <pre><code>npx json-server db.json --port 4000 --delay 1000</code></pre>
  <li>Start the React application:</li>
  <pre><code>npm start</code></pre>
</ol>
<h2>📁 Folder Structure</h2>
<ul>
  <li><code>services/api.ts</code> – RTK Query service config</li>
  <li><code>store/</code> – Redux store and slices</li>
  <li><code>components/</code> – UI components</li>
  <li><code>db.json</code> – Local mock database for JSON Server</li>
</ul>
<h2>🎯 Objectives</h2>
<ul>
  <li>Convert fetch logic to use Redux and RTK Query;</li>
  <li>Understand async data fetching using RTK Query and caching mechanisms;</li>
  <li>Practice integration between Redux Toolkit and external APIs (mocked);</li>
</ul>
