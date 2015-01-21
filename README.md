# HW #1 Question

Create a simple program that will

Part I. Authenicate to AWS    
Part II. Demonstrate a simple API call.

After completing your program, write a simple description of what you did, and include a screenshot demonstrating your API call.

# Solution

Soltution File: SimpleQueueServiceSample.java

## Description Paragraph
This sample demonstrates how to make basic requests to Amazon SQS using the AWS SDK for Java.
<p>
<b>Prerequisites:</b> You must have a valid Amazon Web
Services developer account, and be signed up to use Amazon SQS. For more
information on Amazon SQS, see http://aws.amazon.com/sqs.
<p>
Fill in your AWS access credentials in the provided credentials file
template, and be sure to move the file to the default location
(~/.aws/credentials) [Linux system] where the sample code will load the credentials from.
<p>
<b>WANRNING:</b> To avoid accidental leakage of your credentials, DO NOT keep
the credentials file in your source directory.    
</p>

### Part I. Authentication to AWS
<p>The ProfileCredentialsProvider class will return your [default] credential profile by reading from the credentials file located at (~/.aws/credentials)
<p>The obtained credentials are then used to authenticate to AmazonSQS using AmazonSQSClient class. The authentication is done using AmazonSQSClient(credentials)
constructor.

### Part II. Demonstration of AmazonSQS (Amazon Simple Queue Service) API call
<p>To demonstrate the API call to AmazonSQS, I have implemented the following methods:
1.  Authenticate to AWS
2.  Create a new SQS queue called MyQueue
3.  Listing all queues in your account.
4.  Sending a message to MyQueue
5.  Receiving messages from MyQueue
6.  Deleting a message
7.  Deleting the test queue    

## Screenshots
<p>
<b> 1.  Program File </b>
![alt text](/content/programFile.jpg "ProgramFile")
<b> 2.  Program Output </b>
![alt text](/content/programOutput.jpg "ProgramOutput")
