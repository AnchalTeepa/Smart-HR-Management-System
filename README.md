# Smart HR Management System

<div align="center">

### An Integrated Employee, Timesheet & Appraisal Management Application

**Built with Microsoft Power Apps, Microsoft Dataverse, and Microsoft Power Automate**

</div>

---

## 📌 Project Overview

The **Smart HR Management System** is a role-based Human Resources Management application developed using Microsoft Power Platform. It integrates employee records, timesheet submission and review, and employee appraisal workflows into a centralized application.

The system enables HR, managers, and employees to interact with relevant HR processes through role-based navigation, structured approval workflows, and centralized data management.

## 🎯 Business Problem

Traditional HR processes can involve scattered employee records, manual timesheet submissions, delayed reviews, and difficulties coordinating employee self-appraisals, manager feedback, and final HR decisions.

The Smart HR Management System addresses these challenges by providing a centralized solution for employee information, timesheet management, and appraisal tracking.

## ✨ Key Features

### 1. Employee Management
- Create and maintain employee records.
- View employee details and profile information.
- Organize employee information for HR operations.

### 2. Timesheet Management
- Create and manage draft timesheets.
- Capture work date, project, task, hours worked, and work description.
- Enable employee submission and manager review.
- Maintain review status, manager comments, and review dates.
- Support automated timesheet review notifications.

### 3. Appraisal Management
- Create appraisal cycles and initiate employee appraisals.
- Capture employee self-appraisal responses.
- Record manager feedback and ratings.
- Support manager approval or rejection.
- Enable final HR review and appraisal status updates.

### 4. Role-Based Access
The application provides role-specific navigation and screens for:

- **HR** — employee management, appraisal cycle management, and final appraisal review.
- **Manager** — timesheet review and appraisal review.
- **Employee** — profile access, timesheet submission, and self-appraisal.

Available actions depend on the application's configuration and assigned security roles.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Microsoft Power Apps | Application screens, forms, dashboards, and role-based navigation |
| Microsoft Dataverse | Storage for employee records, timesheets, appraisals, and appraisal cycles |
| Microsoft Power Automate | Automated timesheet review notifications |
| Power Fx | Navigation, form behavior, record selection, validation, and status updates |

## 🔄 Application Workflow

### Employee Management
1. HR creates and maintains employee records.
2. Employees access their profile information through the application.

### Timesheet Management
1. The manager creates a draft timesheet.
2. The employee enters work details and submits the timesheet.
3. The manager reviews the submission and approves or rejects it.

### Appraisal Management
1. HR creates the appraisal cycle and initiates appraisals.
2. The employee completes and submits the self-appraisal.
3. The manager reviews the appraisal and approves or rejects it.
4. HR completes the final review.

## 🗄️ Data Model

The application uses Microsoft Dataverse to organize its core HR data.

| Table | Description |
|---|---|
| **Employees** | Employee information and profile details |
| **Timesheets** | Employee, work date, project, task, hours worked, status, manager comments, and review details |
| **Appraisals** | Employee, manager, appraisal cycle, self-appraisal, manager feedback, manager rating, and review status |
| **Appraisal Cycles** | Cycle name, start date, end date, and related appraisal records |

## 🖥️ Main Application Screens

- **Role-Based Login:** Accepts email, password, and role selection for HR, Employee, or Manager.
- **Home Dashboard:** Provides navigation to the application's main modules.
- **Employee Management:** Supports employee record management and employee details.
- **Employee Profile:** Displays employee profile information.
- **Manager Dashboard:** Provides access to manager timesheets.
- **Timesheet Details and Review:** Supports timesheet information, review, and status tracking.
- **HR Appraisals:** Supports appraisal and appraisal cycle management.
- **Employee Self-Appraisal:** Enables employees to submit self-assessment responses.
- **Manager Appraisal Review:** Supports manager feedback, ratings, and review decisions.
- **HR Final Review:** Supports the final appraisal review by HR.

## 📈 Project Achievements

- Integrated three core HR modules into one application.
- Implemented structured timesheet submission and manager review.
- Connected employee self-appraisal, manager review, and final HR review.
- Centralized HR data using Microsoft Dataverse.
- Configured timesheet review notifications using Power Automate.


## 👩‍💻 Author

**Anchal Teepa**  
B.Tech in Computer Science and Engineering | 2026

---

<div align="center">

*Streamlining HR operations through centralized data management and structured workflows with Microsoft Power Platform.*

</div>
