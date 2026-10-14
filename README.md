# Team Follow-Up Application: AWS Data Protection, Encryption & Privacy Compliance Project
Graduation project for the Cloud Security track under the supervision of Digital Egypt Pioneers Initiative (DEPI).
![Project Banner](https://github.com/user-attachments/assets/ffeb7372-7e91-4b57-b3f9-d6fee4416191)
## Team
-  [Marwa Abdullah Ouf Elzoghby](https://github.com/marwa-elzoghby⁠)
- Nadine Amr Sayed Fahmy
-  [Omar Mohsen Emam Youssef](https://github.com/OmarMohsen9)
-  [Zyad Ahmed Mahmoud Ibrahim](https://github.com/retzed)
- Dina Bahy Mostafa El-shiekh
- Haneen Mosad Mohammed Elgebaly
#### Instructor: Samah Eisa
## Architecture
![arch Banner](https://github.com/user-attachments/assets/93655534-49e3-4756-9cab-b05330023960)
## Project Overview
The Team Follow-Up Application helps team members track work, manage assignments, and keep an activity history of updates. The frontend is hosted using **AWS Amplify**, while AWS serverless services provide authentication, API access, data storage, and monitoring.
## Project Objectives
- Develop a centralized web application for managing team projects, work items, assignments, and follow-ups.
- Improve team coordination and visibility into task ownership and progress.
- Maintain an auditable history of application activities and data changes.
- Provide authenticated access to shared project information across desktop and mobile devices.
- Establish a scalable, serverless architecture with operational visibility into application health.
## Project Scope
- **Frontend:** Host and deliver the static web dashboard through AWS Amplify.
- **Authentication:** Manage user sign-in and issue JWT tokens using Amazon Cognito.
- **API Layer:** Expose authenticated REST endpoints through Amazon API Gateway.
- **Backend Processing:** Implement request validation, business logic, and hierarchy enforcement using AWS Lambda.
- **Data Storage:** Maintain work items, assignments, and activity history in Amazon DynamoDB.
- **Observability:** Collect application logs and metrics and configure alarms using Amazon CloudWatch.
## Project Plan
### Week 1 — Frontend & AWS Foundation
* **Tasks:**
  - Initialize the repository structure and base HTML/CSS layout.
  - Configure AWS Amplify for static frontend hosting and CDN routing.
  - Establish UI design components for task tracking and dashboard views.
* **Deliverables:**
  - Deployed static frontend prototype accessible via Amplify.
  - Initial repository layout and styling assets.
### Week 2 — Authentication & API
* **Tasks:**
  - Set up an Amazon Cognito User Pool for team identity management and sign-in.
  - Create the Amazon API Gateway HTTP/REST API endpoints.
  - Implement JWT authorizer rules to secure API routes.
* **Deliverables:**
  - Configured Cognito user authentication flow.
  - Functional API Gateway routing with active token validation.
### Week 3 — Data & Application Integration
* **Tasks:**
  - Develop AWS Lambda functions to handle backend requests, validate hierarchies, and process queries.
  - Create Amazon DynamoDB tables for storing work items, assignments, and activity history.
  - Connect the frontend and API layers to perform end-to-end data read/write operations.
* **Deliverables:**
  - Deployed Lambda backend logic.
  - Operational DynamoDB tables tracking tasks and activity events.
### Week 4 — Testing & Observability
* **Tasks:**
  - Configure Amazon CloudWatch log groups, metrics, and operational alarms.
  - Perform end-to-end integration testing across authentication, API, and storage layers.
  - Finalize documentation and repository instructions.
* **Deliverables:**
  - Active CloudWatch monitoring and error logs.
  - Fully tested, production-ready serverless deployment workflow.
