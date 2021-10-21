<p align="center">
  <img width="460" height="300" src="https://miro.medium.com/max/1400/1*u7O7aRurf2VdORCanc55Fg.png">
</p>

<h1 align="center"><a href="https://aws.plainenglish.io/run-aws-dynamodb-locally-2788ad73c4db">Run AWS DynamoDB Locally</a></h1>

Commands to access Dynamo DB

1. Using DynamoDB image <br />
```aws  dynamodb scan --table-name customer-loc --endpoint-url=http://localhost:8000```

2. Using Localstack from within a container, or set up profile for aws cli of a PC using first shell script <br />
```aws  dynamodb scan --table-name customer-loc --endpoint-url=http://localhost:4566 --profile=localstack```

Access a container <br />
```docker container exec -it localstack sh```
