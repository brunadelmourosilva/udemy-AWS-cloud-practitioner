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

- **slides 92 - (summary)**

