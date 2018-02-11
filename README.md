# T9Hack Project

Serverless website using AWS Lambda to convert text to speech using Amazon Polly.
Alexa Skill to deliver physics facts, functioning as a tutor.

AWS Services Used:
Lambda: Serverless Webpage creation. No data centers, creation and maintenance of EC2 Instances, completely server-less hassle-free website creation for the dynamic new world!
S3: Storage Service. File-Based. Used to deploy the website. Automatically stores converted audio files in mp3 format in a bucket.
SNS: Notification Service to let DynamoDB know that a file has been uploaded.
DynamoDB: Object-based storage. 
Polly: Machine Learning algorithm that converts text into speech. Various voices and translation into different languages supported. Making life simpler by the day!
IAM: Security, Policy.
API Gateway: To trigger Lambda Functions.
Alexa Skill: Customizing Alexa's services to learn Physics.
