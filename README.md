# Ex--10-IAM-working-overview
Name: DEEPIKA V

Reg No: 212224240030

Aim

To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.

Procedure

Start the AWS Lab and open the AWS Management Console.

Open IAM → Users and verify user-1, user-2, and user-3.

Open User groups and verify the groups S3-Support, EC2-Support, and EC2-Admin and their attached policies.

Add:

user-1 → S3-Support
user-2 → EC2-Support
user-3 → EC2-Admin
Open the IAM Sign-in URL and sign in as each user using the given lab credentials.

Test user-1: verify S3 access and confirm EC2 access is denied.

Test user-2: verify EC2 read-only access and confirm that stopping an EC2 instance is denied; verify S3 access is denied.

Test user-3: open EC2, select LabHost, and stop the instance successfully.

Submit the lab and check the Grades/Submission Report.

End the lab after completing all tasks.

Output

<img width="624" height="275" alt="image" src="https://github.com/user-attachments/assets/51b956ab-1289-44a7-a7b3-6b8827fcbbb1" />

<img width="872" height="570" alt="image" src="https://github.com/user-attachments/assets/681cde72-9962-4c6b-852c-7a2d5bb908dd" />

<img width="868" height="589" alt="image" src="https://github.com/user-attachments/assets/8ad53354-591a-4581-8c80-1a3523fd103b" />

<img width="868" height="596" alt="image" src="https://github.com/user-attachments/assets/a51b9db7-0abb-4b72-8b66-c041457d3189" />

<img width="868" height="589" alt="image" src="https://github.com/user-attachments/assets/a59e5b2e-82f7-4d28-954a-640bdd49a035" />

<img width="862" height="428" alt="image" src="https://github.com/user-attachments/assets/5ed22515-59cb-4446-afc0-5299e6fc19b0" />

<img width="870" height="445" alt="image" src="https://github.com/user-attachments/assets/284ab78d-9c62-4b5e-b231-0ba6aab0c7ab" />

Result

The IAM users were successfully assigned to their respective groups, and the required permissions were verified. user-1 received S3 read-only access, user-2 received EC2 read-only access, and user-3 received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
