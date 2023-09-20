# EC2 Backup and Restore Management :

## Project Overview:
The "EC2 Backup and Restore Management" project aims to establish robust data protection and recovery procedures for Amazon Elastic Compute Cloud (EC2) instances within our AWS environment. It focuses on creating automated backup schedules, implementing efficient data recovery processes, and developing comprehensive disaster recovery plans to ensure data resilience and minimal downtime in the face of unexpected failures. The project will enhance our data security, availability, and overall operational continuity.

## Overview :

![Blank diagram (4)](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/60617430-ab6f-4bb5-896f-7ae1aa4d6762)



## Project Objectives:
1. We have to create a custom EC2 instance with the necessary software and configurations.
2. And then we have to create an AMI from the custom EC2 instance to ensure reproducibility.
3. Now , We can Launch multiple instances from the same AMI when needed.
4. It implement data persistence and backup strategies to ensure data availability and recovery.
5. It define access controls and security measures to protect our instances and data.

## Steps :

### Step 1:
### Creating the EC2 Instance :
1. Navigate to the EC2 console.
2. Follow the Outlines steps below.


![b1](https://github.com/itz-mathesh/disaster-recovery-ec2/assets/144098846/a25737f4-f5a8-44a5-8411-25a162448b91)

![b2](https://github.com/itz-mathesh/disaster-recovery-ec2/assets/144098846/3d268e9f-17ad-4004-b807-d18e2fcfb488)


![b3](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/75ee12b6-5835-4440-9391-aacff0be9295)


![b4](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/ce37c517-14b6-4b5c-b2aa-5ac8231caca4)


![b6](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/b7833969-e19e-4606-aafd-353d9eb7def2)


![b7](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/4c44d67c-8219-43eb-a4d0-20c7370b557d)

3. Now , Iam going to insert some Data in the Instance.


![b8](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/a028687d-8d12-4f00-af6b-2f561210ea61)


### Step 2 :
### Creating AMI from Instance :

1. Now , Iam going to create AMI from our Instance.

#### Steps :


![b9](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/221803bd-d42d-487f-9e9f-59909182d77e)


![b10](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/abf42b31-421d-4181-96de-a1d86ab95e0f)

![b11](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/d1a5f782-d459-49a5-9490-5abf342e5161)



### Step 3 :
### Terminating the  Instance :

1. Now , Iam going to Terminate the Instance and after that Iam going to create a new instance to retrieve data.

#### Steps :


![b99](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/b10f63f0-92a5-4e43-853d-105ef9407f51)


![b100](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/f4f90d91-41fe-45dc-ba2c-b8aa279a59da)


### Step 4 :
### Banking-up and Restore the Data :

1. Now , Iam going to Create a new instance to retrieve data.

#### Steps :


![b12](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/91cbb8ec-b749-4ed6-9ce3-28c1a449769d)


![c1](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/ba690c68-01f5-4425-bb0e-0690206ebe54)


![c2](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/d89d00c8-059e-4acc-b967-fb1d9c53e7ac)


![c3](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/d8944a13-e1cd-4f57-96e8-e21a2d689aee)


![c4](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/ef725fb6-9131-45fa-a78f-a30fc8cbb59f)


![c5](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/16c4c8fd-4b29-42a6-9b06-e22900d85abb)


![c6](https://github.com/itz-mathesh/backup-restore-ec2/assets/144098846/69116087-1bbe-4526-9d15-b90c8df9814c)


### We successfully backed-up and restored the Old Data using AMI.


