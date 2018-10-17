# Persistence Adapter Demo

This is a demo showing how to use the DynamoDBPersistenceAdapter to override the default DynamoDB settings so from V2 you can use a DynamoDB table created with the V1 SDK without any modifications to the table.

## What You Will Need
*  [Amazon Developer Account](http://developer.amazon.com/alexa)
*  [Amazon Web Services Account](http://aws.amazon.com/)
*  The sample code on [GitHub](). (Update with final link)

## Troubleshooting

If you are encountering issues with your skill, double check that you have completed the following:

1. Ensure that the policy attached to your lambda role has **DynamoDB** access.