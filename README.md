# GT Launcher
This is the Launcher of Globex Trading System developed using Docker Compose.

<h1>How to run in Local?</h1>
<ol>
<li>Clone the repository.</li>
<li>Please make sure you have installed both Docker and Docker Compose</li>
<li>Now login to the GitHub Container Registry using the command <code>docker login ghcr.io</code>. 
Then it will ask for username and password. Enter the credentials provided.</li>
<li>Go to the root of the project where <code>compose.yml</code> file is located.</li>
<li>Now run the command <code>docker compose up -d</code>. Wait until the application starts.</li>
<li>Now head to <code>http://localhost:80</code> on your browser to access the website.</li>
</ol>

<h1>How to stop the servers?</h1>
<ul>
<li>Enter the command <code>docker compose down</code>.</li>
<li>This will stop and delete all the containers.</li>
<li>If you want to restart, use the command <code>docker compose up -d</code>.</li>
</ul>