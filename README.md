# temporal-workflow-golang-example

<h1>Running temporal service</h1>
cd /var/www/temporal-workflow-golang-example/engine<br />
docker-compose up<br />
check in <a href="http://localhost:8088/">http://localhost:8088/</a> address at browser<br />

<h1>Running worker</h1>
cd /var/www/temporal-workflow-golang-example<br />
go run worker/main.go<br />

<h1>Running client</h1>
cd /var/www/temporal-workflow-golang-example<br />
go run client/main.go<br />

<h1>Postman collection</h1>
And after these steps; run requests in postman collection <br />
Step1 : http://127.0.0.1:3310/start-workflow <br />
Step2 : http://127.0.0.1:3310/send-signal/{workflow-id}
