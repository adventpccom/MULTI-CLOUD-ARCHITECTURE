# MULTI-CLOUD-ARCHITECTURE

*COMPANY* : CODTECH IT SOULTIONS

*NAME* : AKASH RAJ

*INTERNID* : CT04DH590

*DOMAIN* : CLOUD COMPUTING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

##DESCRIPTION OF TASK 3 :
In this task, I explored and implemented a Multi-Cloud Architecture setup where services are distributed across two different cloud platforms. The idea was to design a solution that does not rely solely on one cloud provider and ensures better redundancy, availability, and flexibility. For this task, I selected AWS and Google Cloud Platform (GCP) as the two cloud providers. I began by identifying a basic architecture that could work across both platforms. On AWS, I used S3 for storage and EC2 for hosting a lightweight application. On GCP, I set up Cloud Storage and Compute Engine. The purpose was to simulate how data or services could interact between platforms. I created an architecture where files uploaded to AWS S3 could be synced to Google Cloud Storage using a script or automation, showcasing interoperability.

One of the main challenges was handling authentication and permissions securely between both platforms. For that, I generated keys from both AWS and GCP and securely stored them. I used Python and command-line tools like AWS CLI and GCloud CLI to transfer or sync data between the two clouds. I documented all the steps involved — from setting up IAM roles and service accounts to writing the scripts for syncing data. To demonstrate interoperability, I created a report showing how a file uploaded on AWS was reflected on GCP using automated sync. I also explained in the documentation how multi-cloud setups help avoid vendor lock-in and improve failover options.

I created a basic architecture diagram and added it to the documentation. This helped visualize the data flow between both clouds. All the resources (buckets, instances, script files, and logs) have been uploaded to the GitHub repository under the Task-3 folder. Through this task, I understood the pros and cons of managing a multi-cloud environment. While it offers more flexibility, it also brings complexity in terms of monitoring, cost management, and security. This was a valuable experience in handling cross-cloud communication and designing architectures that are resilient and not limited to one platform.

