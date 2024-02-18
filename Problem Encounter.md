In the README, I mentioned that, along with the project documentation, I created a separate document highlighting the problems I encountered and the procedures I followed to solve them. So, let's get started.
### Problem 1: Creating an S3 Bucket

#### Problem:
I needed to create an S3 bucket on AWS for Ir project.

#### Solution:
1. **Steps Taken:**
   - Opened the [Amazon S3 Console](https://s3.console.aws.amazon.com/).
   - Created a new S3 bucket with a unique name.
   - Choose the desired region for the bucket.
   - Configure additional settings.

### Problem 2: Configuring Bucket Policies

#### Problem:
I faced challenges in configuring bucket policies for controlling access.

#### Solution:
1. **Steps Taken:**
   - Navigated to the "Permissions" tab in the S3 Console.
   - Added or updated bucket policies to control access.
   - Ensured that public access settings aligned with project requirements.

### Problem 3: Adjusting Object ACLs and Permissions

#### Problem:
I encountered issues while adjusting Access Control Lists (ACLs) for individual objects.

#### Solution:
1. **Steps Taken:**
   - Adjusted ACLs for individual objects.
   - Granted or denied permissions based on specific use cases.

### Problem 4: AWS CLI Commands and Permissions

#### Problem:
I needed to interact with the S3 bucket using AWS CLI commands, but encountered permission issues.

#### Solution:
1. **Steps Taken:**
   - Checked IAM policies for the user.
   - Reviewed and updated bucket policies and ACLs.
   - Ensured AWS CLI was properly configured.

### Problem 5: Making Objects Public

#### Problem:
The "Make public" option was unclickable, preventing me from making objects public.

#### Solution:
1. **Steps Taken:**
   - Checked bucket ACLs.
   - Checked for restrictions in bucket policies.
   - Checked IAM user permissions.
   - Explored AWS S3 Block Public Access settings.
