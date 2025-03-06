Create a Role in Google Cloud IAM

Overview

This lab involves configuring Identity and Access Management (IAM) in Google Cloud to control user access to a sensitive database used by Cymbal Bank. The main goal is to create a custom IAM role, assign it to a user, and verify the assigned permissions.

Scenario

Cymbal Bank is migrating its workflows to Google Cloud. One of these workflows includes a database that stores customer billing and invoice data. Before deployment, the database needs a third-party audit, and auditors require access. To maintain security, a specific IAM role must be created to grant view-only permissions to the auditors.

Steps Completed

1. Create a Custom IAM Role

Accessed the Google Cloud Console.

Navigated to IAM & Admin > Roles.

Clicked Create Role and provided a name and description.

Assigned specific permissions required for viewing and listing database contents.

Saved the role.

2. Assign the Role to a User

Navigated to IAM in the Google Cloud Console.

Selected a test user who needs access.

Clicked Add Role and assigned the newly created custom role.

Confirmed and saved changes.

3. Verify Role Assignment

Tested access by logging in with the assigned user credentials.

Confirmed that the user was able to list and view database contents but not modify them.

Ensured that permissions aligned with security best practices.

Key Learnings

IAM Best Practices: Custom roles allow fine-grained control over permissions, improving security.

Role-Based Access Control (RBAC): Assigning only necessary permissions minimizes security risks.

Auditing & Compliance: Implementing IAM controls ensures compliance with security standards during audits.

Conclusion

This lab provided hands-on experience in managing IAM roles, ensuring proper access controls, and verifying role assignments. The correct implementation of IAM policies strengthens security and streamlines access control in cloud environments.

