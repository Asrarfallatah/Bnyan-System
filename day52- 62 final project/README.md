# Bnyan | بُنيان

## Tuwaiq Final Project

**Group Members:** Mohammed Alrashedi, Rand Abalkhail, and Asrar Fallatah

---

## Abstract

Managing construction projects presents significant challenges for landowners due to fragmented communication, lack of transparency, and inefficient coordination among multiple stakeholders. The construction lifecycle typically involves architects, engineers, interior designers, and contractors operating across disconnected platforms, leading to delays, cost overruns, and limited visibility into project progress. 

Bnyan is a web-based platform designed to address these challenges by providing a unified digital environment that enables landowners and prospective land buyers to define requirements, manage stakeholders, and monitor construction projects from initiation to completion through a single, centralized system.

---

## Project Objective

Current construction management practices rely on manual processes and scattered communication channels, resulting in: 

- Limited transparency across project stages
- Inefficient stakeholder coordination
- Difficulty tracking progress and milestones
- Increased risk of delays and budget overruns
- Absence of a unified system to manage the full construction lifecycle

There is a clear need for a centralized digital solution that streamlines project planning, execution, and monitoring while improving collaboration and accountability. 

---

## System Design

### 1. Database ERD

The database schema includes the following key entities: 
- **User**: System users with roles (customer, specialist)
- **Customer**: Landowners and clients
- **Specialist**: Construction professionals (architects, engineers, contractors)
- **Land**: Property information
- **Built**: Construction specifications
- **Project**:  Core project management entity
- **BuildRequest**: Construction requests from customers
- **UserRequest**: General user requests
- **SpecialistRequest**:  Requests for specialist services
- **Task**: Project tasks and milestones
- **Meeting**:  Scheduled meetings
- **Review**:  Project reviews and ratings
- **Domain**: Specialist domains/expertise areas
- **ProjectManager**: Project management assignments

### 2. Figma Prototype

[Figma Design](Figma Design)

### 3. Project Flow

The project follows a structured workflow: 
1. **User Registration** → User creates an account
2. **Project Creation** → Customer initiates a construction project
3. **Specialist Assignment** → Relevant specialists are assigned
4. **Planning & Approval** → Project planning and approval phase
5. **Progress Tracking** → Ongoing monitoring and updates
6. **Project Completion** → Final delivery and closure

---

## Team Contributions

| Member | Contribution |
|--------|-------------|
| **Mohammed Alrashedi** | User, UserRequest, Customer, Built, Meeting<br>ERD relations, Security, Email Configuration, Figma |
| **Rand Abalkhail** | ProjectManager, Project, Specialist, SpecialistRequest, Domain<br>AI Configuration, Figma |
| **Asrar Fallatah** | Task, Review, BuiltRequest, Land, Payment<br>JUnit testing, Moyasser, one AI endpoint, Figma |

---

## Features

- ✅ Unified project management platform
- ✅ Multi-stakeholder coordination
- ✅ Real-time progress tracking
- ✅ Specialist assignment and management
- ✅ Meeting scheduling and coordination
- ✅ Review and rating system
- ✅ Payment integration (Moyasser)
- ✅ Email notifications
- ✅ AI-powered recommendations
- ✅ Secure authentication and authorization

