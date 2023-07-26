# udemy-AWS-cloud-practitioner

## Section 3 - What is the cloud computing?

- **slides 10 - 38**

## Section 4 - IAM (Identity And Access Management)

- **slides 39 - 56(summary)**

**TO REMEMBER**

**IAM POLICIES**
  - INLINE POLICIES: policy that is attached directly to a user (created / existent).
  - "Deny" has priority over any permission ("Allow").

**AWS CLI - GENERATE AND USING AN ACCESS KEY TO AN USER**

- Go to "Users" and click in the user

- Go to "Security credentials" and create the access key

- Insert the access keys infos on CLI

```aws configure```

- To see the access key infos

```aws iam list-users```

**IAM ROLES**

• Some AWS service will need to perform actions on your behalf

• To do so, we will assign permissions to AWS services with IAM Roles

• Common roles: • EC2 Instance Roles • Lambda Function Roles • Roles for CloudFormation

**IAM SECURITY TOOLS**

**Shared Responsibility Model for IAM**

---

## Section 5 - EC2 (Elastic Cloud Computing)

- **slides 57 - 91(summary)**

**TO REMEMBER**

**AWS BUDGET SETUP**

- To see the charges by service: aws billing -> bills -> chargers by service
- To see the free tier usage: aws billing -> free tier
- Create alerts for cost usage on services: aws billing -> create budget

**EC2 - INSTANCES TYPES**

- https://aws.amazon.com/ec2/instance-types/
![image](https://github.com/brunadelmourosilva/udemy-AWS-cloud-practitioner/assets/61791877/a5647ed3-54f2-42fd-b34e-afae960cdbe7)

**Security Groups**

- "Good to know" - slide
- Classic ports to know - slide

- On AWS EC2 INSTANCE
  - INBOUND RULES
  - OUTBOUND RULES

**SSH OVERVIEW**

- CONNECT IN EC2 INSTANCE USING LINUX: 

```
ssh -i downloaded-private-key.pem ec2-user@public-ip
```

- CONNECT IN EC2 USING WINDOWS:

```
USE THE PUTTY PROGRAM
CONVERT THE .PEM TO .PPK
```

```
USE POWERSHELL

ssh -i udemy-key-pair.pem ec2-user@34.238.114.128

```

**EC2 PURCHASING OPTIONS**

**Shared Responsibility Model for EC2**

---

## Section 6 - EC2 Instance Storage

- **slides 92 - 111(summary)**

**TO REMEMBER**

- EBS VOLUME
  - ATTACHED AND DESTACHED VOLUMES ON INSTANCES 

- EBS SNAPSHOTS
  - can create a snapshot and create a volume from the snapshot created, for differents AZ. 

- AMI
  - create a custom image in a EC2 instance and use it in another EC2 instance.

- EC2 Instance Store
  - high-performance hardware disk
  - lose their storage if they are stopped (EPHEMERAL) 

- EFS

- FXs

--- 

## Section 7 - Elastic Load Balancing & Auto Scaling Groups Section

- **slides 113 - 128(summary)**

---

## Section 8 - Amazon S3 - Simple Storage Service

- **slides 129 - 169(summary)**

---

## Section 9 - Databases & Analytics

- **slides 170 - 198(summary)**

---

## Section 10 - Other Compute

- **slides 199 - 221(summary)**

---

## Section 11 - Deployment

- **slides 222 - 247(summary)**

---

## Section 12 - Global Infrasctructure

- **slides 249 - 273(summary)**

---

## Section 13 - Global Infrasctructure

- **slides 275 - 286(summary)**

---

## Section 14 - Cloud Monitoring

- **slides 287 - 308(summary)**

---

## Section 15 - VPC

- **slides 309 - 327(summary)**

---

## Section 16 - Security and Compliance

- **slides 328 - 362(summary)**

---

## Section 17 - Machine Learning

- **slides 363 - 375(summary)**
