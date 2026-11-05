## Types of Cloud Storage

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Data is divided into fixed-size blocks and presented as a storage volume to a computer. | Operating systems, databases, and applications that need fast disk-like storage. | AWS EBS |
| File Storage | Data is organized into files and directories and can be shared across multiple systems through a network. | Shared folders, content repositories, and applications that need a traditional file system. | AWS EFS |
| Object Storage | Data is stored as objects together with metadata and a unique identifier inside a bucket. | Large amounts of unstructured data such as images, videos, backups, and logs. | AWS S3 |

Object Storage is a good choice for the client's photo-sharing app because it can store many types of files, such as user-uploaded photos. Apps can access these files through an API, while the files are stored separately from the web server.
