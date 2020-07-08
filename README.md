## Service Purpose:
This service creates Hello Lambda function that has the API Gateway setup using API Keys and usage plan (Maximum is 4 calls per DAY). Lambda also has reservedConcurrency set to 5, meaning maximum of 5 instances running concurrently are allowed.

Use Postman test example for the call.

#### Note that in Postman test, Key value 'x-api-key' = 'api-test-key-key-key' in Headers section.