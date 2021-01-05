# ut-aws-s3
Storing data in the cloud becomes an integral part of most modern IT landscapes. With Universal Automation Center you can securely automate your AWS, Azure, Google and MinIO File Transfers and integrate them into your existing scheduling flows.

<p>As security is one of the key concerns when moving to the cloud, the provided solution supports multi-level of security:</strong></p>
<ul>

<li> Credentials for AWS S3 (Access Key, Secret Access key and Region) are stored in an encrypted form in the database

<li> IAM Role-Based Access Control (RBAC) is supported

<li> Communication to AWS is done via the HTTPS protocol

<li> A Proxy Server connection to AWS with basic authentication is supported

<li> Secure access to AWS S3 buckets using AWS bucket policies can be configured in the AWS console

<li> Restrict sending files only to specific buckets using AWS End Points can be configured in the AWS console

This Universal Task focuses on the AMAZON AWS S3 file transfer, including support for MinIO. MinIO is an Open Source object storage server for private cloud environments based on Amazon’s S3 API. All file transfer scenarios supported for AMAZON AWS S3 are also support for MinIO. The scenarios described in this documentation are also valid for MinIO.

A similar solution as for AWS S3 is also available for Microsoft Azure Blob Storage and Google Cloud Storage.
