# Reading Task Submission

## Introduction to Amazon S3

### What is Amazon S3?
Amazon S3 (Simple Storage Service) is a scalable object storage service provided by Amazon Web Services (AWS). It allows users to store and retrieve any amount of data from anywhere on the web.

### List at least 3 features that it offers to its users:
1. **Scalability:** Amazon S3 can handle virtually unlimited amounts of data, making it suitable for a wide range of use cases.
2. **Durability:** Data stored in S3 is redundantly stored across multiple locations, ensuring high durability.
3. **Security:** S3 provides features like access control lists (ACLs) and bucket policies to control access to your data.

### What is an object key?
An object key is a unique identifier assigned to each object (file) stored in an S3 bucket. It is used to retrieve and manage the objects within a bucket.

## S3 with Amplify

### Which dependencies are needed to install Amplify AWS S3 to your Android application?
To use Amplify AWS S3 in an Android application, you need to include the following dependencies:

```gradle
implementation 'com.amplifyframework:aws-storage-s3:1.0.0'
implementation 'com.amplifyframework:aws-auth-cognito:1.0.0'
