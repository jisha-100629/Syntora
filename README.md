# Syntora — Role-Based Student Management Portal

Syntora is a enterprise-grade web application designed to centralize and automate academic record workflows. The platform enforces strict role-based access control (RBAC), providing tailored dashboards and secure data portals for administrators, faculty, and students alike.

---

##  Key Features

###  Secure Authentication Layer
* **Role-Based Routing:** Customized, isolated dashboards for Admins, Faculty, and Students based on authenticated session privileges.
* **Controlled Access Data Visiblity:** Data exposure is programmatically locked down to enforce security boundaries across roles.

###  Admin Administration Module
* **Curation Core:** Add, edit, and maintain holistic student profiles and academic histories.
* **System Metrics:** Monitor institutional attendance trends and broad performance analytics.
* **System-Wide Broadcasts:** Instantly push notices and critical timeline notifications to specific user tiers.

###  Faculty Management Portal
* **Attendance Ledger:** Dynamically upload, parse, and adjust periodic attendance metrics.
* **Performance Tracking:** Analyze individualized student milestones and record performance logs.

###  Student Self-Service Portal
* **Academic Dashboard:** Real-time access to personal transcripts, attendance tallies, and grading sheets.
* **Notification Feed:** Live tracking of administrative notices and institutional updates.

---

##  Technical Ecosystem

* **Backend Engine:** Java (JSP & Servlets)
* **Frontend Layer:** HTML5, CSS3, JavaScript (Bootstrap 5)
* **Persistent Storage:** MySQL Database
* **Server Runtime:** Apache Tomcat (v9.0)

---

##  Engineering & Implementation Highlights

* **Stateful Session Management:** Implemented bulletproof, server-side session authentication to protect user identities and handle request handling safely.
* **Relational Database Design:** Architected a robust, multi-table MySQL schema with relational mapping to handle normalized data structures cleanly.
* **JSP-Servlet Layering:** Maintained clean architectural separation by separating presentation logic (JSP layouts) from business controller paths (Java Servlets).
* **Enterprise Deployment:** Configured structural context paths and deployment descriptors to cleanly host the application stack via an Apache Tomcat environment.
