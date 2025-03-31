Introduction to Storage

Benefits of Cloud Storage
Cost efficient- you pay only for what you use.
Secure-data is saved across multiple servers.
Accessible- to multiple user in an account.
Scalable- it can grow and shrink as your work load change.
Managed- you don't have to worry about servers and focus on your data and applications.
Backed up- copies of data are stored in different physical locations in case of failure.

Types of cloud Storage.

Block Storage

use cases:
-Hosting database instances.
-Big data analytics.
-Enterprise application.
![Amazon Storage](./diagrams/Block%20Storage.png)

File Storage
![Amazon Storage](./diagrams/File%20Storage.png)

Object Storage

use cases:
-Disaster recovery.
-Data lakes.
-Cloud-native applications

![Amazon Storage](./diagrams/object%20storage.png)

Amazon S3.
S3- Simple Storage Service.
Amazon S3 is an object storage service that you can use to collect, store, and analyze data in any amount from amywhere in the world.
Common use case:.

- Data lakes- for large amount of data.
- file storage for static website hosting.
- Backups of data for use in disaster recovery.
- Archive for data that isn't actively used but should be saved for future.

Amazon S3 offeres.
-Scalability- you don't have to predict the right-size capacity upfront.
-Durability - durability is the measure of the average annual expected loss of objects. 99.999999999% durable.

- Avalability - the amount of time that an object stored in amazon S3 is available for retrival. 99.9% available.
  -Performance.
  -Security.

Object Identifiers.
A combination of object name, key and version ID uniquely identifies an object.

![Amazon Storage](./diagrams/creating%20a%20bucket.png)

Amazon S3 Storage Classes

![Amazon Storage](https://github.com/Assekops/aws-notes/blob/main/diagrams/Amzon%20S3%20Storage%20Classes.jpg)

Amazon S3 storage classes use cases.

Amazon S3 Standard.
-Website that only include static content.
-Storage for log file that are frequently accessed, reviewed, or have analytics run against them.

- Storage for application installers, configuration files, and provisioning and deploymnet tools.

Amazon S3 Standard IA

-Backups of your systems.
-Files that are rarely accessed but must be quickly accessed if needed.

Amazon S3 One Zone IA

-Storage for cross-Region replication backups from othen S3 buckets.
-Off-site storage of coppies of on-premises backups, which gives you extra protection for your backups.
-Easily replaceable files.

Amazon S3 Glacier Flexible Retrival.
-Storage of long term backups or archives for compliance purposes, or for backups that need to be retained for a long period of time.
-Replacement for magnetic tapes stored on-premises or offf site.
-Digital media asset archive for large media files.

Amazon S3 Glacier Deep Archive.

- Archives or dataseta that must be retained for compliance purposes.
  -Long-term data libraries.

Amazon S3 Intelligent Tiering.
-Unpredictable workloads.
-Unknown workloads.
-Rapidly changing workloads.

Choosing a storage class- case 1

![Amazon Storage](./diagrams/Choosing%20storage%20class-case%201.png)

Amazon S3 Pricing.
Amazon S3 Pricing is transparent, pricing is based on the type of object, how long it is stored, and how it is accessed.

Object Ownwership and Access.

By default object does not have public access and ACL(Access Control List) is turned off.
![Amazon Storage](./diagrams/object%20ownership%20and%20access.png)

-Versioning- help to recover from both unintended user actions and application failures.
-Versioning is disabled by default.
-You can enable and suspend versioning at the bucket level. After you version-enable a bucket, you can never return to unversioned state.

Tags.
Tags help track your storage COSTS.

Object Life Cycle
-Lifes cycle rule is a set of actions that Amazon S3 applies to a group of objects.

2 Types of actions.
-Transaction actions define when an object transition from one storage class to another.
-Expiration action define when objects are expired and are deleted.
![Amazon Storage](./diagrams/object%20lifecycle.png)

Moving large amount of data into Amazon S3

![Amazon Storage](./diagrams/Amazon%20S3%20transfer%20acceleration.png)

![Amazon Storage](./diagrams/AWS%20Snowcone.png)

![Amazon Storage](./diagrams/AWS%20Snowball.png)

![Amazon Storage](./diagrams/AWS%20Snowmobile.png)
