# 📝 Sample Inputs

## Example Use Cases and Input Patterns

This document provides real-world examples of effective inputs for the Quantum Code Artisan, demonstrating how to craft prompts for optimal results.

## 🚀 API Development Examples

### Example 1: REST API for E-commerce
**Persona**: Senior Developer
**Task**: 
```
Create a comprehensive REST API for an e-commerce platform that handles user authentication, product catalog management, shopping cart operations, and order processing. Include proper error handling, input validation, and security measures.
```

**Context**: 
```
Technology stack: Node.js with Express.js framework, PostgreSQL database, JWT for authentication, bcrypt for password hashing. Need to support high traffic (10,000+ concurrent users) and integrate with third-party payment processors. Must comply with PCI DSS requirements.
```

**Output Format**: Code Solution

### Example 2: GraphQL API for Social Media
**Persona**: Full-Stack Developer
**Task**: 
```
Design and implement a GraphQL API for a social media application with features for user profiles, posts, comments, likes, follows, and real-time notifications.
```

**Context**: 
```
Using Apollo Server with Node.js, MongoDB with Mongoose, Redis for caching, Socket.io for real-time features. Need to handle complex queries efficiently and implement proper authentication and authorization.
```

**Output Format**: Technical Documentation

## 💾 Database Design Examples

### Example 3: Multi-tenant SaaS Database
**Persona**: Software Architect
**Task**: 
```
Design a multi-tenant database architecture for a SaaS project management tool that supports team collaboration, task tracking, time logging, and reporting while ensuring complete data isolation between tenants.
```

**Context**: 
```
PostgreSQL database, expected 1000+ tenants with varying sizes (10-1000 users each). Need to balance performance, security, and maintainability. Consider both row-level security and schema-per-tenant approaches.
```

**Output Format**: Analysis Report

### Example 4: Data Warehouse Schema
**Persona**: Data Analyst
**Task**: 
```
Create a dimensional model for a retail analytics data warehouse that tracks sales, inventory, customers, and marketing campaigns across multiple channels and regions.
```

**Context**: 
```
Source systems include e-commerce platform, POS systems, CRM, and marketing automation tools. Need to support both real-time dashboards and historical reporting. Target is 100M+ transactions per month.
```

**Output Format**: Step-by-Step Guide

## 🔐 Security Assessment Examples

### Example 5: Web Application Security Audit
**Persona**: Security Expert
**Task**: 
```
Perform a comprehensive security assessment of a financial services web application, including authentication mechanisms, data encryption, input validation, and compliance with industry standards.
```

**Context**: 
```
React frontend with Node.js backend, JWT authentication, PostgreSQL database. Handles sensitive financial data and must comply with SOX, PCI DSS, and state banking regulations. Recently experienced credential stuffing attacks.
```

**Output Format**: Analysis Report

### Example 6: API Security Review
**Persona**: Security Expert
**Task**: 
```
Conduct a security review of our public REST API focusing on authentication, authorization, rate limiting, input validation, and protection against common vulnerabilities like OWASP Top 10.
```

**Context**: 
```
Express.js API with OAuth 2.0, serving mobile and web applications. Handles user data and integrates with third-party services. Current rate limiting is basic and we've seen some suspicious traffic patterns.
```

**Output Format**: Checklist

## 📱 Mobile Development Examples

### Example 7: Cross-Platform Mobile App
**Persona**: Mobile Developer
**Task**: 
```
Develop a cross-platform mobile application for expense tracking and budget management with offline capabilities, data synchronization, receipt scanning, and financial goal tracking.
```

**Context**: 
```
Using React Native for cross-platform development, need offline-first architecture with SQLite local storage, camera integration for receipt capture, and synchronization with cloud backend when connectivity is available.
```

**Output Format**: Project Timeline

### Example 8: Native iOS App Performance
**Persona**: Mobile Developer
**Task**: 
```
Optimize performance of an iOS news reading app that experiences slow scrolling, high memory usage, and battery drain issues. The app displays article lists with images and supports offline reading.
```

**Context**: 
```
Swift app with UIKit, Core Data for offline storage, SDWebImage for image loading. App loads 100+ articles with images per session. Users report lag when scrolling through article lists.
```

**Output Format**: Step-by-Step Guide

## 🚀 DevOps and Infrastructure Examples

### Example 9: CI/CD Pipeline Setup
**Persona**: DevOps Engineer
**Task**: 
```
Design and implement a complete CI/CD pipeline for a microservices application that includes automated testing, security scanning, containerization, and deployment to Kubernetes with zero-downtime releases.
```

**Context**: 
```
5 microservices written in different languages (Node.js, Python, Java), using Docker containers, deploying to AWS EKS, GitHub as source control. Need automated testing, vulnerability scanning, and rollback capabilities.
```

**Output Format**: Technical Documentation

### Example 10: Infrastructure as Code
**Persona**: DevOps Engineer
**Task**: 
```
Create Infrastructure as Code templates for a scalable web application infrastructure including load balancers, auto-scaling groups, databases, caching layers, and monitoring on AWS.
```

**Context**: 
```
Using Terraform for IaC, need to support development, staging, and production environments. Application expects high availability, auto-scaling based on load, and comprehensive monitoring and alerting.
```

**Output Format**: Code Solution

## 🤖 AI/ML Development Examples

### Example 11: Recommendation System
**Persona**: AI/ML Engineer
**Task**: 
```
Build a recommendation system for an e-commerce platform that suggests products based on user behavior, purchase history, and similar user patterns using collaborative and content-based filtering.
```

**Context**: 
```
Python with scikit-learn and TensorFlow, 1M+ users, 100K+ products, sparse user interaction data. Need to handle cold start problem for new users and products, and provide real-time recommendations.
```

**Output Format**: Code Solution

### Example 12: Computer Vision Model
**Persona**: AI/ML Engineer
**Task**: 
```
Develop a computer vision model for automated quality inspection in manufacturing that can detect defects in products on an assembly line with high accuracy and speed.
```

**Context**: 
```
Using PyTorch and OpenCV, need to process images in real-time (30 FPS), detect various defect types with >95% accuracy. Training data includes 50K labeled images of products with and without defects.
```

**Output Format**: Step-by-Step Guide

## 📊 Data Analysis Examples

### Example 13: Customer Analytics Dashboard
**Persona**: Data Analyst
**Task**: 
```
Create a comprehensive customer analytics dashboard that tracks user acquisition, engagement, retention, and lifetime value with interactive visualizations and automated insights.
```

**Context**: 
```
Data sources include Google Analytics, CRM system, customer support tickets, and transaction database. Need to update daily and provide both high-level metrics and detailed drill-down capabilities.
```

**Output Format**: Technical Documentation

### Example 14: A/B Testing Framework
**Persona**: Data Analyst
**Task**: 
```
Design and implement an A/B testing framework for a web application that can run multiple concurrent experiments, track various metrics, and provide statistical significance testing.
```

**Context**: 
```
Python-based analysis with SQL database for data storage. Need to support feature flags, user segmentation, and integration with existing analytics pipeline. Must handle 100K+ daily active users.
```

**Output Format**: Analysis Report

## 🧪 Quality Assurance Examples

### Example 15: Test Automation Strategy
**Persona**: QA Engineer
**Task**: 
```
Develop a comprehensive test automation strategy for a complex web application that includes unit testing, integration testing, end-to-end testing, and performance testing with CI/CD integration.
```

**Context**: 
```
React frontend with Node.js backend, multiple databases, third-party integrations. Need to achieve >80% code coverage, run tests in parallel, and integrate with existing Jenkins pipeline.
```

**Output Format**: Project Timeline

### Example 16: API Testing Framework
**Persona**: QA Engineer
**Task**: 
```
Create an automated API testing framework that validates REST endpoints, handles authentication, tests error scenarios, and generates detailed test reports with performance metrics.
```

**Context**: 
```
Using Postman/Newman or REST Assured with Java. API has 50+ endpoints with OAuth authentication. Need to test various scenarios including edge cases, error handling, and load conditions.
```

**Output Format**: Code Solution

## 📋 Project Management Examples

### Example 17: Agile Transformation Plan
**Persona**: Project Manager
**Task**: 
```
Create a comprehensive plan for transitioning a traditional waterfall development team to agile methodologies, including team training, process changes, tool implementation, and success metrics.
```

**Context**: 
```
20-person development team working on enterprise software, currently using waterfall with 6-month release cycles. Stakeholders want faster delivery and better responsiveness to changing requirements.
```

**Output Format**: Project Timeline

### Example 18: Risk Management Framework
**Persona**: Project Manager
**Task**: 
```
Develop a risk management framework for a complex software migration project that identifies potential risks, mitigation strategies, contingency plans, and monitoring procedures.
```

**Context**: 
```
Migrating legacy mainframe system to cloud-based architecture, 18-month timeline, $5M budget, critical business operations dependent on system. Multiple vendors and regulatory compliance requirements.
```

**Output Format**: Analysis Report

## 💡 Tips for Crafting Effective Inputs

### Task Description Best Practices

#### Be Specific and Detailed
- **Include technical requirements**: Programming languages, frameworks, databases
- **Specify constraints**: Performance requirements, scalability needs, compliance standards
- **Define scope**: What features to include/exclude, integration requirements

#### Provide Context
- **Technology stack**: Current tools and technologies in use
- **Environment details**: Development, staging, production considerations
- **Team information**: Skill levels, availability, experience with technologies

#### Set Clear Expectations
- **Output format**: Choose the most appropriate format for your needs
- **Complexity level**: Indicate if you need beginner-friendly or advanced solutions
- **Deliverables**: Specify what you want to receive (code, documentation, plans, etc.)

### Common Input Patterns

#### Problem-Solution Pattern
```
Task: "Solve [specific problem] by [approach/method]"
Context: "Current situation is [description], constraints are [list], requirements include [details]"
```

#### Implementation Pattern
```
Task: "Implement [feature/system] that [functional requirements]"
Context: "Using [technology stack], need to support [scale/performance], integrate with [systems]"
```

#### Analysis Pattern
```
Task: "Analyze [system/situation] and provide [type of analysis]"
Context: "Current state is [description], concerns are [issues], goals are [objectives]"
```

#### Planning Pattern
```
Task: "Create a plan for [project/initiative] that [goals/objectives]"
Context: "Timeline is [duration], resources include [team/budget], constraints are [limitations]"
```

---

**💡 Remember**: The more specific and detailed your input, the more targeted and useful the generated solution will be. Don't hesitate to include technical details, constraints, and context that might seem obvious - they help create more accurate and actionable outputs.