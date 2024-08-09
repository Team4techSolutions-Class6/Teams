**Automating IAM Tasks Rotation Key Change**

**Objective**

In this assignment, you will work in teams to develop a series of bash scripts that automate AWS Identity and Access Management (IAM) tasks and file backups.
You will use Git for version control, collaborate through GitHub, and manage tasks using Jira. 
This project is designed to enhance your skills in cloud computing, scripting, version control, and team collaboration.

**Requirements**

+ Basic understanding of AWS and IAM (e.g., creating an IAM user and giving the user permissions).
+ Familiarity with Git and GitHub (ensure Git is installed on your system).
+ Basic knowledge of bash scripting (use resources like ChatGPT if needed).
+ Access to AWS CLI and permission to configure it (ensure AWS CLI is configured, e.g., aws configure).
+ Access to Team4Tech Solutions's GitHub account and Jira.

  
**Assignment Setup**

Step 1: AWS CLI Configuration

+ Install and configure the AWS CLI on your local machine (ensure you have the latest version).
+ Verify that you have the necessary AWS permissions to create and manage IAM users and policies.

**Step 2: GitHub Repository Creation**

+ The team lead should create a new repository on the Team4Tech Solutions GitHub account. Name the repository according to your team name (e.g., team-5-automation-scripts).
+ Create a development ,staging and production branch on the GitHub repository.
+ Ensure the repository has appropriate access permissions for all team members. Verify that you can push and clone the repository.

**Step 3: Initial Bash Script**

+ The first team member shold manually create an IAM USER 

**Step 4: Jira Ticket Management**

Open Jira tickets for each task:

+ Ticket 1: Write a Bash shell script that can create a group and add the user to the group 
+ Ticket 2: Edit the script to attach an administrative policy to the group.
+ Ticket 3: Further modify the script to create an AWS access key for the user.
+ Ticket 5: Create a script to rotate the oldest access key and generate a new one.
+ Ticket 6: Update the script to also update the developer's local environment with the new key.
+ Ticket 7: Another script to delete the old key 


**Each team member (starting with the second) will:**

+ Clone the GitHub repository.
+ Create a new branch named after their ticket number (e.g., ticket-2-add-user-to-group).
+ Complete their assigned task and push changes to GitHub.
+ Open a pull request for review.
+ Members will Review the pull requests from others before merging them into the development branch.


**Follow Git Workflow:**

+ After merging into the development branch, initiate a pull request to move changes to the staging branch.
+ Review and merge into staging.
+ Finally, initiate a pull request to merge changes into the main branch.
+ Document the reasons for these steps in the readme.md file.
  
**Step 6: Documentation**

+ Update the readme.md file in the repository with:
+ Instructions on configuring the AWS CLI.
+ Prerequisites for running the scripts.
+ A description of what each script does.
+ Ensure each member modifies the readme.md file before pushing their changes.

**Submission Guidelines**

+ Submit the URL of your GitHub repository.
+ Ensure all pull requests are merged into the main branch by the submission deadline.
+ Submit links to the Jira tickets associated with each task.

**Evaluation Criteria**

+ Functionality: Scripts should work as expected without errors.
+ Collaboration: Effective use of Git branches, pull requests, and code reviews.
+ Documentation: Clear, concise, and complete documentation in the readme.md file.
+ Jira Management: Proper use of Jira for task management and tracking.


Submission date : 22md of August 2024
