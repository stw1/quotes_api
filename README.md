# Quote API

Based on the serverless api CRUD Example.  This examples uses serverless framework that uses several services on AWS to create a RESTful API support CRUD for authors and quotes.


## Create a quote
  - curl -X POST https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/todos --data '{ "author": "John Smith", "quote": "Trees are nice" }'
  
  
## List all quotes
  - curl https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/todos
  
## Locating AWS URL
Log into the AWS account, check the endpoint by visiting Lambda -> API Gateway
  
## Deploy
serverless deploy --aws-profile serverless (note this depends on the name of your aws profile)
