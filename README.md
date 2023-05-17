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

****

---



