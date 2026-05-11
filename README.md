<div align="center">
  <h1>🚀 QMS-Flow</h1>
  <p>A centralized web-based platform for Metafour Sdn Bhd to automate ISO 9001:2015 compliance workflows[cite: 1, 78].</p>
  
  <img src="https://img.shields.io/badge/Status-Version%203-brightgreen?style=for-the-badge" alt="Version 3" />
  <img src="https://img.shields.io/badge/Architecture-Layered-blue?style=for-the-badge" alt="Layered Architecture" />
  <img src="https://img.shields.io/badge/UTM-SECJ2203-red?style=for-the-badge" alt="UTM Course" />
</div>

<hr />

## 📌 Project Overview
**QMS-Flow** replaces fragmented, manual quality workflows with a centralized, standards-compliant web system[cite: 3]. It is designed to foster a proactive quality culture by digitizing the annual audit cycle and linking customer feedback directly to corrective actions[cite: 79, 80].

### Core Subsystems:
* **Document Control:** Secure repository for version-handled SOPs with automated approval workflows[cite: 79].
* **Audit Management:** Digitizes audit planning, scheduling, and real-time recording of findings[cite: 49, 79].
* **Customer Complaint:** Bridges external feedback with internal Non-Conformance Reports (NCR) and CAPA records[cite: 79].
* **Management Review:** A strategic hub that aggregates data from all modules into a reporting dashboard[cite: 79].

## 🛠️ Technical Architecture
The system adopts a **Layered Architecture** with an MVC presentation tier and modular domain services[cite: 15].

* **Presentation Layer:** Responsive, browser-based UI using PHP and JavaScript[cite: 16, 29].
* **Domain Layer:** Encapsulates business logic for compliance tracking and ISO traceability[cite: 17, 20].
* **Data Layer:** Persistent storage using a relational database (MySQL) to manage entities like Audits, Documents, and NCRs[cite: 18, 65].
* **Infrastructure:** Shared services for Auth/RBAC, Audit Trails, and File Storage[cite: 19].

## 🚀 Key Features
* **ISO 9001:2015 Compliance:** Automated tracking ensuring every state transition is attributable[cite: 7, 82].
* **Automated Reminders:** Asynchronous background processing for audit schedules and follow-ups[cite: 8].
* **RBAC Security:** Centralized Role-Based Access Control to guard endpoints and domain operations[cite: 20].
* **Reporting Dashboard:** Real-time data visualization for executive decision-making[cite: 79].

## 📋 Getting Started
### Prerequisites
* Web Browser (Chrome, Edge, or Firefox)[cite: 16].
* PHP Environment (e.g., XAMPP/WAMP).
* Relational Database (MySQL)[cite: 65].

### Installation
1. Clone the repository.
2. Import the SQL entities from the `Data Design` directory[cite: 64].
3. Configure your database connection in the infrastructure layer.

## 👥 Project Contributors
* **Nur Anisah Solehah binti Mohd Hamim** [cite: 1]
* **Najihah binti Azhan Khan** [cite: 1]
* **Alisya Humayraa binti Mohd Khairani** [cite: 1]
* **Allisya Maisarah binti Suraizal** [cite: 1]

---
<div align="center">
  <p><b>SECJ2203: Software Engineering</b><br>Faculty of Computing, Universiti Teknologi Malaysia (UTM) [cite: 1]</p>
</div>
