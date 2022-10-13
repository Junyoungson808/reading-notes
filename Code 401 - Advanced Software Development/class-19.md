# Reading
## [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

1. What is the difference betweeen SQS and SNS?
  SNS is a distributed publish-subscribe service.
  SQS is distributed queuing service.

  SNS is a distributed publish-subscribe system. Messages are pushed to subscribers as and when they are sent by publishers to SNS.
  SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll SQS to receive messages. Messages can be stored in SQS for short duration of time (max 14 days).

  Entity Type
    SQS : Queue (similar to JMS, MSMQ).
    SNS : Topic-Subscriber (Pub/Sub system).

2. What are some use cases for both SNS and SQS?
  SNS can be like a email subsribers list, while a SQS is more of job orders that come with different priorities that can be pushed ahead of other messages.

## [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

1. Describe how to use SQS and SNS in a “fanout” pattern.
  how messages are sent to multiple end points.
2. Explain how “push notifications” work, using SNS.
  they register to a app, and they request an app specific token to use push notifications, the device passes the token to the aws provider to register for notifications.

## [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

1. How might a large scale, distributed application make use of a Queue system like SQS?
  businesses that need paperwork or documentation for the next message to leave or customer to recieve the message.

### Bookmark and Review
#### [SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)
#### [SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)