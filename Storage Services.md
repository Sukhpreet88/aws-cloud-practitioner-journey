## Summary of AWS Storage Services

| Service | Description                     |
|---------|---------------------------------|
| Amazon S3  | Object storage with high durability and availability |
| Amazon EBS(Elastic Block Storage)  | Block storage for EC2 instances|
| Amazon EFS (Elastic File System) | Scalable file storage for Linux-based workloads |
| AWS Storage Gateway |Hybrid cloud storage; bridge on-premises apps with AWS storage |





## Amazon S3 Storage Classes

| Class   | Description                     |
|---------|---------------------------------|
| S3 Standard  | General-purpose, High availability (11 9s), Low latency |
| S3 Standard-IA | Lower cost for infrequent access, suitable for long-term backups|
| S3 Intelligent-Tiering | Auto-moves data across tiers. useful if data has unknown or changing access patterns.|
| S3 Glacier Instant Retrieval| Low cost Archival storage. retrieved in milliseconds |
| S3 Glacier Flexible Retrieval| Low cost storage. Access time is between 1-5 minutes |
| S3 Glacier Deep Archive | Lowest cost storage class. Default retrieval time is 12 hours. Best for compliance archives. |
| S3 One Zone-IA | Stores data in single Availability Zone. Lower availability and cost |
| S3 Express One Zone | Single Availability Zone. Faster, lower cost |
| S3 Outposts | On-Premises Object Storage. Useful for low latency, data residency, and data sovereignty requirements.|
