# Project Documentation: Deploy a Basic (Static) Website on AWS:

## Table of Contents

1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Prerequisites](#prerequisites)
4. [Project Setup](#project-setup)
    - [Step 1: Create an S3 Bucket](#step-1-create-an-s3-bucket)
    - [Step 2: Configure Bucket Policies](#step-2-configure-bucket-policies)
    - [Step 3: Object ACLs and Permissions](#step-3-object-acls-and-permissions)
5. [AWS CLI Commands](#aws-cli-commands)
6. [Troubleshooting](#troubleshooting)
7. [Conclusion](#conclusion)
8. [Acknowledgments](#acknowledgments)

## Introduction

This document provides documentation for the configuration of an Amazon S3 bucket for a project. It covers the necessary steps to set up the bucket, configure policies, manage object-level access, and use the AWS Command Line Interface (CLI) for various tasks.

## Project Overview

The project involves creating an S3 bucket on AWS and configuring it for specific use cases, including setting bucket policies, managing object ACLs, and interacting with the bucket using AWS CLI commands.

## Prerequisites

- AWS account with the necessary permissions to create and configure S3 buckets.
- AWS CLI installed and configured with appropriate credentials.

## Project Setup

### Step 1: Create an S3 Bucket

1. Open the [Amazon S3 Console](https://s3.console.aws.amazon.com/).
2. Create a new S3 bucket with a unique name.
3. Choose the desired region for the bucket.
4. Configure additional settings as needed.

### Step 2: Configure Bucket Policies

1. Navigate to the "Permissions" tab in the S3 Console.
2. Add or update bucket policies to control access.
3. Ensure that public access settings align with project requirements.

### Step 3: Object ACLs and Permissions

1. Adjust Access Control Lists (ACLs) for individual objects.
2. Grant or deny permissions based on specific use cases.

## AWS CLI Commands

- Use the AWS CLI for various tasks related to the S3 bucket:
  ```bash
  aws s3 ls                            # List buckets
  aws s3 ls s3://portfolio-website-project     # List objects in a bucket
  aws s3 sync . s3://portfolio-website-project     # command to upload your local repository content to your S3 bucket.
  ``` 

## Troubleshooting
If you encounter issues:
- Check IAM policies for the user.
- Review bucket policies and ACLs.
- Ensure AWS CLI is properly configured.

## Conclusion

This documentation provides a guide for setting up and configuring an S3 bucket on AWS for your project. Follow the steps carefully, and refer to the troubleshooting section if needed.
