# AWS: Events

### Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

* Amazon API Gateway is an AWS service for creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs at any scale. API developers can create APIs that access AWS or other web services, as well as data stored in the AWS Cloud.

* Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.


***

### List the AWS Database offerings and talk about the pros and cons of each

![database](https://d1.awsstatic.com/Startups/StartupPageAssets/how-to-choose-a-database-1.12737182f86dcb29938f211ad303d63ab7bdf29a.png)

***
### What’s the difference between a FIFO and a standard queue?

**Message Order**

* Standard queues provide `best-effort ordering` which ensures that messages are generally delivered in the same order as they are sent. Occasionally (because of the highly-distributed architecture that allows high throughput), more than one copy of a message might be delivered out of order.

* FIFO queues offer `first-in-first-out` delivery and exactly-once processing: the order in which messages are sent and received is strictly preserved.

**Delivery** 
* Standard queues guarantee that a message is `delivered at least once` and duplicates can be introduced into the queue.
* FIFO queues ensure a message is `delivered exactly once` and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue.

**Transactions Per Second (TPS)**
* Standard queues allow `nearly-unlimited` number of transactions per second.
* FIFO queues allow to process `up to 3000` messages per second per API action.

**Regions**
* Standard queues are available in `all` the regions.

* FIFO queues are currently available in `limited` regions only.
***
### How can the server be assured a message was properly received?

using queue to mae sure that the clint will never miss it

***

# Document the following Vocabulary Terms

* **Serverless API**

“serverless” means the developer does not have to think about servers, even though they exist. AWS handles them. Plus, Lambda only charges you when your code is run, which is an attractive pricing model.

* **Triggers**

A trigger is a Lambda resource or a resource in another service that you configure to invoke your function in response to lifecycle events, external requests, or on a schedule.

* **Dynamo vs Mongo**

1. Dynamo :

DynamoDB is a fully managed AWS service and uses tables, items and attributes, but supports limited data types and smaller item sizes

note: its use Dynamoose 

2. Mongo :

MongoDB can be self installed or fully managed with MongoDB Atlas and uses JSON-like documents , supports more data types and has fewer size restrictions

note: its use Mongoose

***