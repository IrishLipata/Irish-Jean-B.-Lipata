# Storage Types Research

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks and provides low-latency access to data. | Operating systems, databases, and applications that need direct disk-like storage. | AWS EBS |
| File Storage | Stores data as files organized in folders and directories. | Shared files and applications that need a traditional file system. | AWS EFS |
| Object Storage | Stores data as objects together with metadata and a unique identifier. | Large amounts of unstructured data such as images, videos, backups, and documents. | AWS S3 |

## Why Object Storage is Best for User-Uploaded Images

Object Storage is suitable for millions of user-uploaded images because it is designed to store large amounts of unstructured data. It can also scale as the number of images increases, making it appropriate for a photo-sharing application.
