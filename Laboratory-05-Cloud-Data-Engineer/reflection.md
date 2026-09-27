# Mission 5 Reflection

Object storage is better suited for storing millions of photos because it is designed for large amounts of unstructured data such as images, videos, and backups. Instead of storing files like a traditional hard drive, object storage organizes data as objects inside buckets. This makes it useful for applications that need to store and access many user-uploaded photos.

Using Docker made it easier to deploy the MinIO storage server because I did not need to manually install and configure all of the required components on the Ubuntu system. I could deploy MinIO using one Docker command, map the required ports, and configure the administrator credentials using environment variables. Docker also made it easier to verify and manage the MinIO server as a container.

A bucket is a logical storage location used to organize and store objects in cloud object storage. In this activity, I created a bucket named `client-photos`. I then uploaded a test file to the bucket through the MinIO Web Console, which demonstrated that the object storage server was working correctly.

Large enterprise companies can help prevent object storage data from being lost when a physical server crashes by keeping multiple copies of data and using redundant storage across servers or locations. This allows data to remain available even if one physical machine fails.

My confidence in navigating the Linux command line is growing because I used Docker commands to deploy and verify the MinIO server. I also learned how to troubleshoot a problem by checking the container logs when the initial storage permission error occurred. This experience made me more comfortable using Linux commands and managing a cloud storage service.
