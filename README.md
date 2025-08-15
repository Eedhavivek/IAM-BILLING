AWS IAM + Billing Setup

 Overview

This project demonstrates the configuration of **AWS IAM** (Identity and Access Management) and **Billing & Cost Management** settings to ensure secure access and proper budget tracking in an AWS account.

 Objectives

 Create IAM users and groups with specific permissions.
 Enable Billing access for IAM users.
 Set up a monthly budget alarm to control AWS costs.


 Steps Performed

IAM Setup

1. Create a new IAM user

    Access type: AWS Management Console
   Permissions: AdministratorAccess (for testing/demo purposes)
    Downloaded `.csv` with access details.

2. Create IAM Group

   Added new IAM user to the group.
   Attached policies for Billing and Admin access.

3. Enable Billing Access

    Navigated to `IAM > Account Settings.
   Checked **Activate IAM access to the Billing Console.


Billing & Budget Setup

1. Go to Billing Console  from the AWS Management Console.
2. Navigate to Budgets → Click Create Budget.
3. Choose Cost Budget → Set monthly budget limit (e.g., `$120`).
4. Add email notification for threshold (e.g., 80% usage).
5. Save and verify budget status.


Project Files

Video Recording : Steps of IAM creation and budget setup.
Screenshots : For documentation purposes.

 Conclusion:

Through this project, I successfully configured AWS IAM to securely manage user access and enabled Billing & Budget controls to monitor AWS costs. This setup ensures better security, transparency, and cost control in any AWS environment. It can be easily replicated for real-world projects to prevent unauthorized access and avoid unexpected expenses.

