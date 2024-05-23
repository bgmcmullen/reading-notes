# Class 19 Reading Notes:


## AWS SQS vs SNS
### What is the difference between SQS and SNS? 
SQS is a distributed queuing system, while SNS is a distributed publish-subscribe system. SQS lets consumers poll messages, while SNS pushes messages to consumers.
### What are some use cases for both SNS and SQS?
SQS is great for task queuing for background processing, and SNS is great for event notifications and mobile push notifications.
## AWS SNS and SQS
### Describe how to use SQS and SNS in a “fanout” pattern.
One message is published to an SNS topic, and it then fans out into multiple SQS queues.
### Explain how “push notifications” work, using SNS.
When a notification needs to be sent, the backend sends a message to the SNS topic. Then, SNS sends the message to all subscribed endpoints.
## SQS and SNS Basics
### How might a large-scale, distributed application make use of a queue system like SQS?
A large-scale application may use SQS for event-driven processing to set up a real-time responsive network.




