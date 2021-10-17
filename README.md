# aws-dynamodb-local-setup-tutorial

Commands to access Dynamo DB

1. Using DynamoDB image <br />
```aws  dynamodb scan --table-name customer-loc --endpoint-url=http://localhost:8000```

2. Using Localstack from within a container, or set up profile for aws cli of a PC using first shell script <br />
```aws  dynamodb scan --table-name customer-loc --endpoint-url=http://localhost:4566 --profile=localstack```

Access a container <br />
```docker container exec -it localstack sh```
