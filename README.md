# Using DynamoDB with Node JS ([source](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStarted.NodeJs.html))

### A repository created from Amazon's DynamoDB + NodeJS tutorial.

To run it:

1. Make sure you have `npm` installed
2. Make sure AWS DynamoDB is running locally. For guide how to run DynamoDB on local environment, check out [this page](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html).
3. Once you have DynamoDB currently running locally, run the code. For example, to create table, run `node MoviesCreateTable.js`.

### Connecting DynamoDB table to AWS

To connect it to your own actual AWS account, modify the `endpoint`:

```
AWS.config.update({endpoint: "https://dynamodb.aws-region.amazonaws.com"});
```

Also, make sure that your AWS has proper Access Key ID and Secret Access Key. For instruction, check out [this guide](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html).
