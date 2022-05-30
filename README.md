# temporal-workflow-golang-example

<p>Medium Link : https://alameddinc.medium.com/nedir-bu-temporal-io-680f3b242136 </p>
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
And after these steps; import postman collection where in the postman-collection directory and then run requests in postman collection <br />
Step1 : http://127.0.0.1:3310/start-workflow <br />
Step2 : http://127.0.0.1:3310/send-signal/{workflow-id}
