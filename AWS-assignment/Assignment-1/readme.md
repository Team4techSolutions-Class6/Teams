**Deployment of a Highly Available Web Application on AWS**
 
**Objective:**

The goal of this project is to deploy a secure, highly available, and resilient web application on AWS. 
The application will be a simple HTML website or Nginx Webserer use any of your choice with the content: 
"Welcome to Team4Tech Solutions Inc, This is Group 'your group name'."  feel free to add any creative content and make the web site great !
This project will emphasize best practices in cloud architecture, including security, disaster recovery, and cost optimization.
 
**Requirements:**

+ EC2 Instance within an Auto Scaling Group:
Deploy an EC2 instance that automatically scales according to the load.

+ Application Load Balancer (ALB):
Place the application behind an ALB to distribute incoming HTTPS traffic evenly across the scaled instances.

+ HTTPS Security:
Ensure that the website is accessible only via HTTPS to secure the data transmission.

+ Content Delivery Network (CDN):
Utilize AWS CloudFront to cache the website globally to reduce latency and improve the user experience for international visitors or global content.

+ DNS Configuration:
Configure a Route 53 subdomain (e.g., groupA.team4techsolutions.com) to route the users to the application effectively.

+ Infrastructure Design:
Use Flowchart Maker & Online Diagram Software to create and document the architecture design, emphasizing Security, High Availability, High Resilience, Disaster Recovery, and Cost Optimization.

+ Collaboration and Task Management:
  
Utilize Jira for creating and assigning tasks related to different components of the project. Each team member should be accountable for specific tasks.

+ AWS Account and Access Management:
  
  Decide whose AWS account will be used for the deployment. Create IAM users for each team member to ensure secure access control.

+ AWS CloudWatch Alarms: Set up CloudWatch alarms to monitor the health and performance of the application servers, ensuring prompt notification in case of issues.

**Evaluation Criteria:**

**Architecture**: Robustness and adherence to best practices in cloud architecture.
**Team Collaboration**: Effectiveness in working as a team and utilizing Jira for task management.
**Documentation**: Quality of documentation on Confluence detailing the design process, challenges, and solutions.
**Execution**: Smooth deployment and operation of the infrastructure.
**Presentation**: Clarity and depth of the final presentation, with each member explaining their contributions.

**Deliverables:**

+ A fully functional website accessible via the custom subdomain.
+ A detailed architecture diagram created with Flowchart Maker & Online Diagram Software e.g the one i use in class .
+ Documentation on Confluence covering all aspects of the project.
+ A final presentation in class explaining the architecture, process, and individual contributions.
  
**Instructions for Submission:**

Complete all components of the project, document each step on Confluence and github readme file, and prepare a presentation to be delivered on the due date. 
Ensure all resources are properly cleaned up post-presentation to avoid unnecessary costs.
