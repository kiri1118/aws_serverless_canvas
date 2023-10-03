This is a yaml file for deploying a serverless AWS service using AWS ApiGateway.
There is no dedicated frontend page designed for this.
For a simple front end, use index.html and update the URL at line 20 to match the WebSocket URL created for the corresponding ApiGateway.

Run deployScript with the desired stack-name as param.
ie. ./deployScript AWSCanvas