# Using DynamoDB with javascript ([source](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStarted.JavaScript.html))

1. Download DynamoDB ([guide](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html))
2. Run DynamoDB on local computer
  - Run `java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb` inside the folder where dynamoDB files are saved. In my case, I saved mine on `~/dynamodb_local_latest`.
  - I would cd to `~/dynamodb_local_latest` and then run the `java` command line above. Keep it running throughout the process (as long as your endpoint is `localhost:8000`, you will need dynamodb to be running locally)
3. Follow instructions [here](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStarted.JavaScript.html)
4. Happy coding!
