# aws-notes

#Amazon API Gateway
-Here we have a lambda function performing CRUD operation from dynamo DB database.
-If we want an external client to be able to access our lambda funtion, but lambda funtion is not exposed as an API directely,
-We need to expose it through Amazon API Gateway,
-Amazon API Gateway provides the client with the REST API to connect direcly to our website,

- The API Gateway proxy the request to the Lambda funtion which will execute the transformation on our data.

  -Amazon API Gateway is a fully managed service to easily create, publish, maintain, monitor and secure APIs.
  -API Gateway supports RESTful APIs and WsbSocket APIs
