# Multi-Platform-ERP-Integrator-Zoho-SAP-Legacy-(Torres y Torres Project)

This repository showcases the architectural logic of a complex integration middleware developed at **Viamatica** for **Torres y Torres**, a leader in customs and logistics. The project focused on synchronizing data across three distinct ecosystems to streamline foreign trade operations.

---

### 🔄 Integration Ecosystem

The solution acted as a central nervous system, orchestrating data between:

1.  **Zoho CRM:** Managed the front-end sales pipeline and customer engagement.
2.  **SAP Business One:** Handled the core ERP functions, financial accounting, and inventory.
3.  **Legacy Customs System:** A specialized proprietary platform for managing customs declarations and maritime logistics.

### 🛠️ Key Technical Challenges & Solutions

*   **Tri-Directional Sync:** Implemented robust logic to ensure data consistency across the CRM, ERP, and Legacy database, preventing duplicates and synchronization conflicts.
*   **API & SDK Integration:** Leveraged the **SAP Business One SDK/Service Layer** and **Zoho REST APIs** to automate the flow of sales orders and customs documentation.
*   **Data Transformation:** Built a translation layer to map complex logistics codes between the modern Zoho environment and the rigid structures of the legacy customs system.

---

### 🚀 Business Impact

*   **Operational Efficiency:** Eliminated manual data re-entry between the sales team and the customs operations desk.
*   **Data Integrity:** Established a "Single Source of Truth" for customer and shipment status across the organization.
*   **Scalability:** Designed the integration to handle the high-volume transactional load typical of a top-tier customs agency.

---

### 🛠️ Technical Stack

*   **Middleware:** C#.
*   **APIs:** Zoho CRM API (REST), SAP BO Service Layer.
*   **Database:** SQL Server (T-SQL) for legacy data mapping and logging.

---

### 🔒 Privacy & Compliance Note

This repository is for **architectural demonstration only**. To protect the intellectual property of **Viamatica** and the sensitive data of **Torres y Torres**, all specific connection strings, API keys, and proprietary business rules have been removed or blinded.

---
*Developed by Carlos Reyes - Senior Business Systems Analyst*
