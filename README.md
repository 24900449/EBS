## WORKING WITH EBS

### NAME: Stephen raj Y
### REGISTER NO:212223230217

## AIM:

In this lab environment, access to AWS services and service actions might be restricted to the ones that are needed to complete the lab instructions. You might encounter errors if you attempt to access other services or perform actions beyond the ones that are described in this lab.

## OBJECTIVE:

1. Create an Amazon EBS volume
2. Attach and mount your volume to an EC2 instance
3. Create a snapshot of your volume
4. Create a new volume from your snapshot
5. Attach and mount the new volume to your EC2 instance

## Illustration:

# STEP 1:
In this step, you will create and attach an Amazon EBS volume to a new Amazon EC2 instance.You will see an existing volume that is being used by the Amazon EC2 instance. This volume has a size of 8 GiB, which makes it easy to distinguish from the volume you will create next, which will be 1 GiB in size.

<img width="1917" height="927" alt="Screenshot 2026-08-20 103613" src="https://github.com/user-attachments/assets/e4eff4f6-f161-43b0-a8a2-e0b3471576ba" />

<img width="1917" height="923" alt="Screenshot 2026-08-20 103838" src="https://github.com/user-attachments/assets/51cd4375-e2d6-4bdd-ae36-5fea8c9d65bb" />


# STEP 2:
In this step, you will connect to the Lab EC2 instance using Session Manager.You can now attach your new volume to the Amazon EC2 instance.

<img width="1917" height="925" alt="Screenshot 2026-08-20 104036" src="https://github.com/user-attachments/assets/2807e27c-c7f6-411c-b8fb-f6c233c2bd28" />

<img width="1917" height="926" alt="Screenshot 2026-08-20 104339" src="https://github.com/user-attachments/assets/a03a2234-a616-437d-af5a-67768b99d0a9" />



# STEP 3:
In this step, you will add the new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point.
<img width="1917" height="927" alt="Screenshot 2026-08-20 104545" src="https://github.com/user-attachments/assets/a16f3e24-90d7-41b6-918c-4c90c3f5ddea" />
<img width="1917" height="930" alt="Screenshot 2026-08-20 105003" src="https://github.com/user-attachments/assets/37d6ad7d-244b-4f4e-98ad-e67bbcfdb8e0" />
<img width="1917" height="922" alt="Screenshot 2026-08-20 105514" src="https://github.com/user-attachments/assets/11a91602-49c1-4103-8562-0b6336b17cc7" />


# STEP 4:
You can create any number of point-in-time, consistent snapshots from Amazon EBS volumes at any time. Amazon EBS snapshots are stored in Amazon S3 with high durability. New Amazon EBS volumes can be created out of snapshots for cloning or restoring backups. Amazon EBS snapshots can also be easily shared among AWS users or copied over AWS regions.

<img width="1917" height="927" alt="Screenshot 2026-08-20 105319" src="https://github.com/user-attachments/assets/76b13ccf-5966-4b83-9087-00f8d3716fba" />

<img width="1917" height="931" alt="Screenshot 2026-08-20 105732" src="https://github.com/user-attachments/assets/34ceb08f-a035-4c3d-93f9-29eb995123b4" />



# STEP 5:
<img width="1551" height="581" alt="Screenshot 2026-08-20 105821" src="https://github.com/user-attachments/assets/a8fd8bfb-c483-4cdc-b5b0-9c511598e405" />


## RESULT:
Successfully created, managed, and deleted an EBS bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon EBS.


