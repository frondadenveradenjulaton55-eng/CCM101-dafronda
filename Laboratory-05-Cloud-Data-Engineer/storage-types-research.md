# Storage Types Research

## Comparison of Cloud Storage Types

| Storage Type   | Description                                                                                                                              | Primary Use Case                                                                             | Cloud Provider Example |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ---------------------- |
| Block Storage  | Stores data as fixed-size blocks that can be attached to a virtual machine and managed like a traditional hard drive.                    | Operating systems, databases, and applications that require fast and consistent disk access. | AWS EBS                |
| File Storage   | Stores data in files organized within folders and directories. Multiple users or systems can access the same file system over a network. | Shared files, documents, media files, and applications that need a shared file system.       | AWS EFS                |
| Object Storage | Stores data as individual objects together with metadata and a unique identifier inside a storage container called a bucket.             | Large amounts of unstructured data such as images, videos, backups, and documents.           | Amazon S3              |

## Why Object Storage Is Best for the Client

Object Storage is a suitable choice for the photo-sharing application because it is designed to store large amounts of unstructured data such as user-uploaded images. It can scale to handle millions of objects while allowing applications to access files through APIs and web-based services.

