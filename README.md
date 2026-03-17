# Automating-S3-Storage-Management-using-Versioning-Lifecycle-and-Access-Logging

Step 1 :
Two Amazon S3 buckets were created — one **main storage** bucket and one dedicated **logging** bucket.

The main bucket is used to store **application data**, while the log bucket is used to store access **logs generated**by the main bucket.

![Project Screenshot](Screenshots/01-buckets-created.png)

Step 2 :
Bucket versioning was enabled to maintain multiple versions of the same object.

Multiple uploads of the same file were performed to generate different versions.

![Project Screenshot](Screenshots/01-buckets-created.png)
