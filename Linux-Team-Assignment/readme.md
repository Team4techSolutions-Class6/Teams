## LINUX TEAM PROJECT AND ASSIGNMENT
 

For a hands-on team assignment that involves provisioning an Ubuntu server on AWS, user and group management, file permissions, and software installation, you can structure the assignment as follows. This structure ensures that each aspect of the assignment is captured in a Jira ticket, promoting teamwork and project management skills alongside technical execution.

**Assignment Overview:**

**Linux Server Setup and Configuration Project**

**Objective:**

The goal is to set up an Ubuntu server on AWS, manage user and group permissions, create and configure a specific directory and file with precise permissions, and install the necessary software. This project will utilize Jira for task management and documentation.

 

**Preparation:**

+ The team lead or team will provision an Ubuntu server on AWS and share its public IP and access credentials with the team for initial setup.

+ Create a project in Jira for this assignment and generate individual tickets for each task outlined below.

+ Assigned each ticket to each member

+ Each team member will be able to log into the server and carry out their task

+ Once each member starts working on their ticket they should mark the ticket on Jira as in progress and once they are done they should mark the ticket as done.

**Task Breakdown and Jira Ticket Creation:**
 

1. **Provision Ubuntu Server on AWS**

+ **Ticket Title**: Provision Ubuntu Server

+ **Assigned to**: The team should decide which member will carryout this task and assigned the ticket to the member

+ **Description**: Create an Ubuntu server instance on AWS EC2. Ensure the instance is accessible over the internet with an Elastic IP.

+ **Acceptance Criteria**: The server is running and accessible via SSH.

 

2. **Create User Accounts for All Team Members on the Ubuntu Server**

**Ticket Title**: User Account Creation for Team Members

**Assigned to**: The team should decide which member will carryout this task and assign the ticket to the member

**Description**: Create a user account for each team member on the Ubuntu server. Ensure users can log in via SSH using ssh  authentication. ( configure ssh authentication for each user in your team to be able to login to the server)

**Acceptance Criteria**: All team members can successfully SSH into the server with their user names .

 

3. **Add User 'Calson' and Share Login Details**

+ **Ticket Title**: Create User 'Calson' for Assignment Review

+ **Assigned to**: The team should decide which member will carryout this task and assign the ticket to the member

+ **Description**: Create a user account named 'Calson' and configure ssh authentication. you can request for my public keys via slack

+ **Acceptance Criteria**: 'Calson' can login via SSH

 

4. **Create Groups and Add Members**

**Ticket Title**: Setup User Groups 'DevOps Engineer' and 'Cloud Engineers'

**Assigned to**: The team should decide which member will carryout this task and assign the ticket to the member

**Description**: Create two groups, 'DevOps Engineer' and 'Cloud Engineers'. Add the specified team members to each group accordingly.

**Acceptance Criteria**: Groups are created, and members are correctly assigned.

 

5. **Create a Directory and File with Specific Content and Permissions**

+ **Ticket Title**: Create a Directory called 'Class6' and a File called 'Assignment'

+ **Assigned to**: The team should decide which member will carryout this task and assign the ticket to the member

+ **Description**: Inside the server, create a directory named 'Class5'. Within this directory, create a file named 'Assignment'. Write the specified content into the file “ Welcome to Team4Tech Solution Group (your group) first assignment “ . Set file permissions to read and write for the user and group, and no permissions for other . Change the file ownership to Calson and Group should be DevOps

+ **Acceptance Criteria**: Directory and file are created with correct content and permissions. File ownership is set to 'Calson', and the group is set to 'DevOps Engineer'.

 

6. **Install Git on the Server**

+ **Ticket Title**: Install Git Software

+ **Assigned to**: Team should decide which member will carryout this task and assigned the ticket to the member

+ **Description**: Install Git on the Ubuntu server using the package manager.

+ **Acceptance Criteria**: Git is installed and can be accessed via the command line.

 

7. **Documentation and Reporting**:

+ Each team member is responsible for updating their assigned Jira ticket to "In Progress" when starting and marking it as "Done" upon completion.

+ Detailed documentation of the steps taken, commands used, and any configurations applied must be included in the ticket.

+ Screenshots or output logs should be attached to the respective Jira tickets as proof of work.

+ Document your process using Confluence and a readme.md file

Submission:
Due Date : July 4, 2024

 

Happy Learning !!