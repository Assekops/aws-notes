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

Amazon S3 Glacier.
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
