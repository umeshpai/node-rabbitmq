# Using RabbitMq using node

## Running RabbitMq server locally
On MAC use following command to isntall rabbitMq
http://www.rabbitmq.com/install-homebrew.html

```shell
brew install rabbitmq
export PATH=$PATH:/usr/local/sbin
rabbitmq-server
```
At this point rabbitMq should be running locally
Access the server using - http://localhost:15672/
username - guest and passwd - guest

## Running App code

```shell
npm install ejs
npm install nodemailer
npm install express
node worker.js
```
In another shell run following command to start the index
```shell
node index.js
```
Now you can access local wepage under http://localhost:3000
Enter any email and click subscribe button

## Ranning rabbitMq in docker