## **6-Month Backend Rails Developer Roadmap with Structured Learning Resources**

This roadmap is designed to guide a junior Ruby developer to senior-level backend Rails development, leveraging Rails 8 with PostgreSQL and preparing for future SQLite compatibility. Each phase includes structured books, specific chapters, and real-life projects to reinforce knowledge and practical application.

---

### **Month 1-2: Ruby Fundamentals and Advanced Concepts**

**Core Objectives**: Build a strong foundation in Ruby programming, object-oriented design, and advanced Ruby concepts like metaprogramming.

#### Topics & Concepts:
1. **Ruby Fundamentals**: Arrays, hashes, control structures, error handling, file operations.
2. **Object-Oriented Programming (OOP)**: Classes, inheritance, modules, encapsulation.
3. **Advanced Ruby**: Metaprogramming, DSLs, Ruby’s Mixin patterns.

#### Real-Life Projects:
- **Project 1**: CLI Personal Finance Tracker
  - **Description**: Create a command-line tool for tracking income and expenses.
  - **Skills**: Practice OOP, working with files, and encapsulation.
- **Project 2**: DSL for Configuration
  - **Description**: Design a DSL for creating configuration files (e.g., a YAML generator).
  - **Skills**: Gain exposure to Ruby’s metaprogramming, refining skills with modules and mixins.

#### Key Resources:
- **Books**:
  - *"The Well-Grounded Rubyist"* by David A. Black, Chapters 1-8 (Ruby foundations, OOP)
  - *"Metaprogramming Ruby 2: Program Like the Ruby Pros"* by Paolo Perrotta, Chapters 1-6 (Advanced Ruby and DSL creation)
- **Additional Resources**:
  - [Ruby Docs](https://ruby-doc.org/core-3.1.0/)
  - [Ruby Koans Exercises](http://rubykoans.com/)

---

### **Month 3-4: Intermediate to Advanced Rails 8 Backend Development with PostgreSQL**

**Core Objectives**: Develop efficient backend APIs, practice database operations with PostgreSQL, incorporate real-time updates with ActionCable, and implement role-based access control.

#### Topics & Concepts:
1. **API Development with Rails**: RESTful API basics, GraphQL with Rails, ActiveRecord.
2. **Database Optimization**: ActiveRecord optimizations, indexing, eager loading, and N+1 query prevention.
3. **WebSocket Integration (ActionCable)**: Real-time updates with ActionCable.
4. **Authentication & Authorization**: Session-based authentication, CanCanCan for RBAC.

#### Real-Life Projects:
- **Project 1**: Task Management API with PostgreSQL
  - **Description**: Develop a task management API with CRUD functionality, filtering, sorting, and pagination.
  - **Skills**: RESTful API design, ActiveRecord optimization, working with PostgreSQL.
  - **Stretch Goal**: Refactor to include GraphQL for advanced querying.
- **Project 2**: Real-Time Notifications with ActionCable
  - **Description**: Enhance the task management API to send real-time notifications for task updates.
  - **Skills**: Implement WebSocket and ActionCable for real-time updates.
- **Project 3**: Authentication and Role-Based Access
  - **Description**: Add session-based authentication and RBAC with CanCanCan.
  - **Skills**: Manage user sessions, implement secure authentication, restrict features by user role.

#### Key Resources:
- **Books**:
  - *"Agile Web Development with Rails 7"* by Sam Ruby, Chapters 1-12 (API basics, MVC design)
  - *"Rails AntiPatterns: Best Practice Ruby on Rails Refactoring"* by Chad Pytel, Chapters 1-4 (ActiveRecord optimization)
- **Additional Resources**:
  - [GraphQL Ruby Guide](https://graphql-ruby.org/)
  - [CanCanCan Documentation](https://github.com/CanCanCommunity/cancancan)

---

### **Month 5: Modern Project Setup and DevOps for Backend Applications**

**Core Objectives**: Establish DevOps skills, containerization, CI/CD, and deployment automation with GitHub Actions and Kamal.

#### Topics & Concepts:
1. **Containerized Development**: Use DevContainers and Docker for isolated development.
2. **Continuous Integration and Deployment (CI/CD)**: Set up workflows with GitHub Actions.
3. **Kamal Deployment**: Basic deployment automation with Kamal for Rails applications.

#### Real-Life Projects:
- **Project 1**: Containerize Task Management API
  - **Description**: Use Docker and DevContainers to create consistent development environments.
  - **Skills**: Docker setup, Docker Compose, configuration for development and deployment.
- **Project 2**: CI/CD Pipeline with GitHub Actions
  - **Description**: Implement automated testing, linting, and deployment pipelines for the API.
  - **Skills**: CI/CD setup, workflow configuration, deploy using Kamal 2.

#### Key Resources:
- **Books**:
  - *"Docker: Up & Running"* by Karl Matthias and Sean Kane, Chapters 1-5 (Docker basics, containerization)
  - *"CI/CD with GitHub Actions"* by Mitesh Soni (Complete)
- **Additional Resources**:
  - [Kamal Documentation](https://kamal-docs.com)

---

### **Month 6: Advanced Rails Backend Capabilities & Comprehensive Project**

**Core Objectives**: Master caching, background jobs, testing, and complete a production-ready backend API.

#### Topics & Concepts:
1. **Caching with Solid Cache**: Learn caching techniques and SQLite compatibility.
2. **Background Jobs with Solid Queue**: Perform asynchronous tasks.
3. **Testing & Documentation**: Master RSpec, integration testing, and API documentation.

#### Real-Life Projects:
- **Project 1**: Background Jobs and Caching for Task Management API
  - **Description**: Add caching for performance and background jobs for asynchronous tasks like notifications.
  - **Skills**: Caching, Solid Queue for background tasks, SQLite compatibility.
- **Project 2**: RSpec Testing & Swagger Documentation
  - **Description**: Write RSpec tests for all API features and document endpoints with Swagger.
  - **Skills**: Comprehensive testing, API documentation for frontend integration.

#### Key Resources:
- **Books**:
  - *"Effective Testing with RSpec 3"* by Myron Marston, Chapters 1-5 (Testing fundamentals)
  - *"High Performance Rails"* by Nate Berkopec, Chapters 3-5 (Caching and performance optimization)
- **Additional Resources**:
  - [RSpec Guide](https://rspec.info/)
  - [Swagger Documentation](https://swagger.io/)

---

### **Capstone Project (Final Two Weeks)**

**Objective**: Develop a complete, production-ready Rails API incorporating all skills from the roadmap.

#### Tasks:
1. **Implement REST and GraphQL Endpoints**: Full-featured API with CRUD operations, complex queries, and filtering.
2. **Authentication and Authorization**: Session-based, role-restricted access control.
3. **DevContainers and CI/CD**: Include DevContainer configuration, automated testing, and GitHub Actions deployment.
4. **Caching and Background Processing**: Use Solid Cache and Solid Queue, preparing for SQLite compatibility.
5. **Final Deployment with Kamal 2**: Deploy the backend application to a production environment.

**Outcome**: Completing this capstone project demonstrates the developer’s proficiency in production-grade Rails backend development, preparing them for real-world API development and deployment.

---

### **Capstone Project PRD: Academic Information System (AIS) API**

**Project Overview**  
Develop a comprehensive Academic Information System (AIS) API for a tertiary institution to manage admissions, academic records, student progress, graduation requirements, and transcript issuance. The AIS will also support integration with learning management systems (LMS) such as Moodle for automated course enrollment and grade synchronization. This API will provide backend support for a frontend application (e.g., React-based) and be ready for deployment in a production environment.

---

### **Goals & Objectives**

- **Objective**: Build a feature-complete backend Rails API with PostgreSQL to manage admissions, academic records, LMS integration, real-time notifications, and transcript generation.
- **Outcome**: By completing this capstone, the developer will demonstrate advanced backend skills for managing complex academic workflows, integrating with external systems, and delivering real-world API functionalities in a production-ready environment.

---

### **Key Features and Functional Requirements**

#### **1. Admission Management**

- **Application Submission & Tracking**:
  - Allow applicants to create accounts, submit applications, and track the status of their applications.
  - Implement stages such as Application Received, Under Review, Accepted, or Rejected.

- **Admission Decision**:
  - Administrators can review applications, approve or deny admission, and update applicant status.
  - Notify applicants of their admission decision via email.

- **Enrollment**:
  - Upon admission acceptance, the student profile is created, and they are batch-enrolled into default courses based on their academic program.

#### **2. User Management**

- **Role-Based Access Control (RBAC)**:
  - Roles include Applicant, Student, Faculty, and Administrator.
  - Control permissions based on role using `CanCanCan`, ensuring only authorized actions (e.g., course registration, grade management).

- **Authentication**:
  - Implement secure authentication using `Devise` for session-based logins.
  - Include JWT support for potential integration with other systems (e.g., mobile app or third-party access).

#### **3. Academic Management**

- **Course and Enrollment Management**:
  - CRUD operations for managing courses, including prerequisites and faculty assignments.
  - Allow students to enroll/drop classes within approved timeframes.

- **Academic Performance Tracking**:
  - Students can view grades for completed semesters.
  - Store cumulative GPA, semester grades, and detailed course performance for students to track their progress toward graduation requirements.

- **Grading and Progress Reports**:
  - Faculty can submit and update grades for students.
  - Integrate with LMS to retrieve final course scores and update academic records.
  - Track academic progress in line with graduation requirements and update students’ status to “Graduated” once requirements are met.

#### **4. Transcript and Certificate Management**

- **Transcript Requests**:
  - Students can request transcripts for completed semesters or their full academic history.
  - Generate transcripts as PDFs and send them via email once approved by administrators.
  - Include semester grades, cumulative GPA, and details relevant to the requested period.

- **Digital Certificate Generation**:
  - Once students fulfill graduation requirements, generate digital certificates and badges.
  - Allow students to request digital certificates directly from the portal.

#### **5. LMS Integration (e.g., Moodle)**

- **Batch Enrollment to Courses**:
  - Integrate with the LMS to enroll students in relevant courses based on class enrollment on the AIS.
  - Automatically sync class enrollments at the start of each semester.

- **Grade Sync**:
  - Retrieve course completion scores from Moodle and update student records in the AIS.
  - Adjust cumulative GPA and other academic metrics based on final scores from the LMS.

#### **6. Class Schedule and Notifications**

- **Class Scheduling**:
  - Allow faculty to define class schedules, locations, and timing for each course.
  - Provide students and faculty with updated schedules based on enrolled or assigned courses.

- **Notifications with ActionCable**:
  - Real-time notifications for schedule updates, new grade postings, enrollment changes, and other critical academic events.
  - Push notifications to subscribed clients via WebSockets for seamless user updates.

#### **7. Background Jobs and Caching**

- **Automated Notifications**:
  - Use `Sidekiq` and Solid Queue for background job processing.
  - Schedule reminders for enrollment deadlines, application statuses, and grade postings.
  - Provide daily/weekly academic summaries to students based on preferences.

- **Caching with Solid Cache**:
  - Cache frequently accessed data, such as class schedules, course listings, and grades.
  - Implement cache expiration policies to optimize performance while ensuring data accuracy.

#### **8. CI/CD and DevOps**

- **Development Environment with DevContainers**:
  - Configure DevContainers for consistency across local development environments.
  - Ensure easy project setup with Docker support.

- **CI/CD Pipeline with GitHub Actions**:
  - Automate testing, linting, and deployment using GitHub Actions workflows.
  - Run tests on every pull request to ensure code quality and stability.

- **Production Deployment with Kamal 2**:
  - Use Kamal 2 for deployment, setting up zero-downtime deployments, SSL, and monitoring.
  - Deploy to cloud or on-premise infrastructure with scalability.

#### **9. API Documentation**

- **Swagger Documentation**:
  - Use Swagger to document all API endpoints, including admissions, academic data management, LMS integration, notifications, and transcript requests.
  - Provide request/response examples and descriptions for easy integration with frontend systems.

---

### **Technical Requirements**

- **Framework**: Rails 8 with PostgreSQL, preparing for SQLite compatibility.
- **Authentication**: Devise with JWT for future integrations.
- **Authorization**: CanCanCan for RBAC and secure data access.
- **Real-Time Notifications**: ActionCable for WebSocket notifications.
- **Background Jobs**: Sidekiq and Solid Queue for background processing.
- **Caching**: Solid Cache for data performance optimization.
- **CI/CD**: GitHub Actions for automated testing and deployment.
- **Deployment**: Kamal 2 for zero-downtime deployments.
- **Documentation**: Swagger for comprehensive API endpoint documentation.

---

### **Milestones and Task Breakdown**

#### **Milestone 1: Setup, Admissions & User Management**
- Set up Rails environment, DevContainers, and PostgreSQL.
- Implement admission process with application tracking and acceptance notifications.
- Configure user roles and permissions for Applicants, Students, Faculty, and Administrators.

#### **Milestone 2: Academic Data & Course Management**
- Develop CRUD operations for managing students, courses, and enrollment.
- Track academic performance, calculate GPA, and update academic progress.
- Integrate with CanCanCan for RBAC, securing operations based on user roles.

#### **Milestone 3: Scheduling, Real-Time Notifications & LMS Integration**
- Implement class scheduling and faculty assignments.
- Set up ActionCable for WebSocket notifications for class updates and new announcements.
- Integrate with Moodle (or other LMS) to batch-enroll students and retrieve final grades.

#### **Milestone 4: Transcript & Certification Generation**
- Develop functionality for students to request transcripts for completed semesters.
- Generate and email PDF transcripts once approved by administrators.
- Create digital certificates and badges for graduated students.

#### **Milestone 5: CI/CD, Deployment, & API Documentation**
- Configure GitHub Actions for CI/CD, automating testing and deployment.
- Deploy the AIS using Kamal 2 with SSL and zero-downtime.
- Document all endpoints with Swagger for frontend and system integration.

---

### **Acceptance Criteria**

- **Functional Requirements**: All endpoints meet functional requirements for admissions, academic records, scheduling, LMS integration, and transcript generation.
- **Testing**: Comprehensive RSpec tests for models, controllers, and integration.
- **Performance**: Effective caching and background jobs optimize API responsiveness.
- **Documentation**: Complete Swagger documentation for all API endpoints.
- **Deployment**: Successful production deployment with zero-downtime and full system integration.

---


### **Capstone Project PRD: Multi-Tenant CMMS API with Advanced Service Request and Work Order System**

**Project Overview**  
Develop a multi-tenant backend API for a Computerized Maintenance Management System (CMMS) with a robust Service Request and Work Order System. This system will allow organizations to manage and track service requests, maintenance work orders, inventory, cost management, vendor interactions, and customer satisfaction feedback. The API will support organizational isolation for a SaaS solution with role-based access control.

---

### **Goals & Objectives**

- **Objective**: Build a scalable CMMS API that integrates service request management, work order generation, inventory and cost tracking, vendor management, and customer feedback. The API will follow industry-standard maintenance practices and support seamless communication with external vendors.
- **Outcome**: The developer will gain experience in implementing a comprehensive maintenance management workflow, covering all aspects from request logging to vendor payment tracking.

---

### **Key Features and Functional Requirements**

#### **1. Multi-Tenancy and Super Admin Management**

- **Super Admin Control**:
  - Super Admin manages all tenant organizations and has high-level access to view tenant usage, deactivate or activate tenants, and manage billing (if applicable).

- **Organizational Isolation**:
  - Each organization operates in an isolated instance, with data scoped to that organization.
  - Use `apartment` gem or similar for tenant-based data isolation, allowing each organization to operate independently.

#### **2. Organization Registration and User Management**

- **Organization-Based Registration**:
  - Only organizations can register on the system. The registering individual becomes the initial Admin/Manager, who can invite other users.
  
- **User Role Management**:
  - **Admin/Manager**: Full access to manage users, assets, service requests, work orders, inventory, and vendor interactions.
  - **Facilities Management/Maintenance Team**: Access to work orders, space inventory, assets, and service requests.
  - **Building Users**: Can submit service requests, view request status, and provide feedback.

#### **3. Comprehensive Space Inventory System**

- **Space Hierarchy**:
  - Organize assets and requests by location: **Facility > Building > Floor > Space**, allowing spaces to span multiple floors if needed.
  - Each space may contain multiple assets, and each asset can be mapped to a specific space.

#### **4. Service Request and Work Order System**

- **Service Request System**:
  - **Request Logging**: Issues can be logged by the Building User or by FM staff on behalf of a user. Each request includes location, description, priority, and requester information.
  - **Investigation and Evaluation**: Each request is reviewed to determine if resources or cash are needed.
  - **Resolution Without Work Order**: 
    - If no inventory or cash is required, the technician completes the task, and the request is marked as "Completed."
    - Requester (or user for whom the issue was raised) is notified to confirm resolution and provide feedback.
    - Positive feedback closes the request. Negative feedback reopens it and alerts the FM team for further action.

- **Work Order Generation**:
  - **Automatic or Manual Generation**: 
    - Work orders are created automatically by the PPM system or manually via the Service Request System when additional resources or external services are needed.
    - FM team marks the request "In Progress" and creates a work order if materials, cash, or external vendors are needed.
  - **Cost and Inventory Management**:
    - Track inventory usage (quantity, cost) and external resources.
    - Generate Purchase Orders (POs) for external vendors as needed, including costs based on agreed rates.

#### **5. Inventory and Cost Tracking**

- **Inventory Management**:
  - Inventory items can be requested directly from the work order.
  - Items are tracked by name, quantity, and cost, allowing calculation of total cost per work order.
  - Inventory levels are adjusted with each use, and alerts are sent if items fall below reorder levels.

- **Cost Tracking and Purchase Order (PO) Management**:
  - **External Vendor Requests**:
    - Work orders needing external vendor services generate a PO based on agreed terms.
    - POs are emailed to vendors to authorize the work.
  - **Cost Tracking**:
    - Track total costs associated with each work order, including inventory and external services.
    - Link completed work with invoices for payment processing.
  - **Work Completion Certificate**:
    - After external work completion, generate a certificate for vendor verification.
    - Vendors submit the certificate to the accounts department for payment, which is verified in the CMMS before approval.

#### **6. Maintenance Scheduling and Real-Time Notifications**

- **Preventive Maintenance Scheduling**:
  - Define PPM tasks for asset types, linking assets to predefined task sets.
  - Generate PPM work orders as scheduled and track completion.

- **Real-Time Notifications**:
  - Notify users of new assignments, updates, and completion statuses via ActionCable.
  - Send alerts to FM teams for reopened requests or customer dissatisfaction.

#### **7. Customer Feedback and Performance Tracking**

- **Customer Feedback Collection**:
  - Upon completion of a service request or work order, Building Users can leave feedback on resolution quality.
  - Positive feedback closes the ticket, while negative feedback reopens it and alerts the FM team.

- **Performance Reporting**:
  - Collect feedback to evaluate the quality of maintenance responses.
  - Generate reports based on customer satisfaction, resolution times, and team performance metrics.

#### **8. Reporting and History**

- **Maintenance and Cost Reporting**:
  - Track total maintenance costs, inventory usage, and vendor services per work order.
  - Generate reports on maintenance frequency, average response times, and customer feedback.

- **Work Order and Service Request History**:
  - Maintain a history of all completed work orders and service requests by asset and space for tracking and compliance.

#### **9. CI/CD and DevOps**

- **Development Environment with DevContainers**:
  - Set up DevContainers to ensure consistent development and testing environments.
  - Configure for easy project setup across different environments using Docker.

- **CI/CD Pipeline with GitHub Actions**:
  - Use GitHub Actions for testing, linting, and automated deployments.
  - Run tests on every pull request to maintain code quality and stability.

- **Production Deployment with Kamal 2**:
  - Deploy the CMMS API with Kamal 2, enabling secure, zero-downtime deployment.
  - Enable scaling options to support multiple organizations in a SaaS environment.

#### **10. API Documentation**

- **Swagger Documentation**:
  - Document all API endpoints with Swagger, covering multi-tenancy, service requests, work orders, inventory, vendor management, and cost tracking.
  - Provide detailed request/response examples and endpoint descriptions for frontend integration.

---

### **Technical Requirements**

- **Framework**: Rails 8 with PostgreSQL, implementing multi-tenancy with `apartment` or similar.
- **Authentication**: Devise with CanCanCan for secure, role-based access within each organization.
- **Real-Time Notifications**: ActionCable for WebSocket-based task updates.
- **Background Jobs**: Sidekiq and Solid Queue for asynchronous job processing.
- **Caching**: Solid Cache to optimize access to commonly accessed data.
- **CI/CD**: GitHub Actions for automated testing and deployment.
- **Deployment**: Kamal 2 for containerized, zero-downtime deployment.
- **Documentation**: Swagger for comprehensive API documentation.

---

### **Milestones and Task Breakdown**

#### **Milestone 1: Multi-Tenancy Setup and Organization Registration**
- Implement organization registration, allowing only organizations (not individuals) to create accounts.
- Configure multi-tenancy using `apartment`, enabling data isolation for each organization.

#### **Milestone 2: Service Request and Work Order System**
- Develop the Service Request System, allowing issues to be logged by users or FM staff.
- Create Work Order management that tracks inventory, costs, and vendor interactions.
- Implement customer feedback collection, allowing users to close or reopen requests based on satisfaction.

#### **Milestone 3: Inventory, Cost Tracking, and Vendor Management**
- Set up inventory management for tracking part usage and cost per work order.
- Implement external vendor engagement, with PO generation and cost tracking.
- Enable work completion certificates and verification for accounts payment processing.

#### **Milestone 4: Notifications, Scheduling, and PPM Integration**
- Set up PPM scheduling, linking assets to predefined task lists.
- Implement real-time notifications with ActionCable for task updates and request completion.

#### **Milestone 5: CI/CD, Deployment, and API Documentation**
- Configure GitHub Actions for CI/CD, with automated testing and deployment.
- Deploy using Kamal 2, ensuring secure, isolated tenant environments.
- Document all endpoints with Swagger, detailing workflows for service requests, work orders, and inventory tracking.

---

### **Acceptance Criteria**

- **Functional Requirements**: All endpoints meet functional requirements for multi-tenancy, service requests, work order management, cost tracking, and vendor management.
- **Testing**: Comprehensive RSpec tests cover tenant isolation, role-based access control, work order and service request workflows.
- **Performance**: Effective caching and background processing optimize response times.
- **Documentation**: Complete Swagger documentation, covering multi-tenancy, service requests, work orders, inventory, and cost tracking.
- **Deployment**: Successful production deployment with isolated tenant environments, SSL, and scaling for high usage.

---