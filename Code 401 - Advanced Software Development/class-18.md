# Reading

## [AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

1. What is Amazon API Gateway?
  - **Managed service** that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.
2. Why is Amazon API Gateway an important part of the Serverless ecosystem?
  - it enables a truly serverless architecture for web apps.
3. How does API Gateway integrate with other AWS services?
  AWS Lambda: run Lambda functions to generate HTTP API responses.
  AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
  Amazon Cognito: provide authentication and authorization for your HTTP APIs.

## [AWS API Gateway](https://aws.amazon.com/api-gateway/)

1. What are the some benefits of using Amazon API Gateway?
  - Easy Monitoring
  - Performance at any scale
2. What two API types might you choose from?
  - RESTful APIs
  - WEBSOCKET APIs

## [AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

1. What is DynamoDB? Is a hosted NoSQL database offered by Amazon Web Services (AWS). It offers:
    - reliable performance even as it scales;
    - a managed experience, so you won't be SSH-ing into servers to upgrade the crypto libraries;
    - a small, simple API allowing for simple key-value access as well as more advanced query patterns.
2. Under what circumstances would you recommend DynamoDB over MongoDB?
  - applications with large amounts of data and strict latency requirements
  - serverless applications using AWS Lambda

## [AWS DynamoDB](https://aws.amazon.com/dynamodb/)

1. Explain to a non-technical friend how DynamoDB works.
  - its a massive and scaling NoSQL or database. Thats also serverless feature offered by AWS, You don't have to ever monitor. 

## [Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

1. What is Dynamoose?
  - Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose.
2. What are some key features of Dynamoose?
  - Type safety
  - High level API
  - Easy to use syntax
  - DynamoDB Single Table Design Support
  - Ability to transform data before saving or retrieving items
  - Strict data modeling (validation, required attributes, and more)
  - Support for DynamoDB Transactions
  - Powerful Conditional/Filtering Support
 - Callback & Promise support
 - AWS Multi-region support