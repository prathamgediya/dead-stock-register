# Online Dead Stock Register (ODSR)

A modern, secure, and efficient web application designed to replace traditional handwritten dead stock registers. This system automates inventory record-keeping by extracting data directly from uploaded bill documents, providing real-time access to authorized users across an organization.

## 🚀 The Problem & Our Solution

**The Problem:** Managing dead stock (permanent, non-consumable assets) using handwritten registers is prone to:
- **Manual Errors:** Human error in data entry leads to inaccurate records.
- **Inefficiency:** The process of writing, updating, and searching logs is slow and tedious.
- **Poor Accessibility:** Physical registers are available in only one location at a time.
- **Security Risks:** Paper records are vulnerable to damage, loss, and unauthorized access.
- **Cumbersome Reporting:** Generating audit reports or summaries requires manual compilation.

**Our Solution:** The Online Dead Stock Register is a web-based platform that:
- **Automates Data Entry:** Automatically populates inventory records by parsing data from digital bills upon upload.
- **Centralizes Data:** Provides a single source of truth for all dead stock inventory, accessible from anywhere.
- **Enhances Security:** Implements user authentication and role-based access control to protect sensitive data.
- **Improves Reporting:** Offers built-in tools for generating accurate and real-time reports instantly.
- **Boosts Efficiency:** Drastically reduces manual work, minimizes errors, and saves valuable time.

## 🛠️ Tech Stack (To Be Determined)

*This section will be updated once the technology choices are finalized. Potential candidates include:*
*   **Frontend:** React.js / Vue.js / Angular
*   **Backend:** Node.js (Express) / Python (Django) / .NET Core
*   **Database:** PostgreSQL / MySQL / MongoDB
*   **Cloud Storage:** AWS S3 / Google Cloud Storage / Azure Blob Storage (for bill documents)
*   **OCR Service:** Tesseract.js / Google Vision AI / Amazon Textract
*   **Authentication:** JWT / OAuth 2.0

## 📋 Key Features (Planned)

1.  **User Authentication & Authorization**
    *   Secure login/logout.
    *   Role-based access (e.g., Admin, Auditor, Viewer).
2.  **Bill Upload & OCR Processing**
    *   Drag-and-drop or manual file upload.
    *   Automatic data extraction from bill images/PDFs using OCR.
3.  **Inventory Dashboard**
    *   View all dead stock items in a sortable and filterable table.
    *   See summary statistics (total items, total value, etc.).
4.  **CRUD Operations**
    *   Create, Read, Update, and Delete inventory records (with appropriate permissions).
5.  **Advanced Search & Filters**
    *   Search by item name, ID, date of purchase, location, etc.
6.  **Reporting**
    *   Generate and export PDF/Excel reports for audits and analysis.
7.  **Audit Trail**
    *   Track changes made to any record (who changed what and when).

## 🗺️ Project Roadmap

- [ ] Phase 1: Requirement Analysis & Finalize Tech Stack
- [ ] Phase 2: UI/UX Design & Database Schema Design
- [ ] Phase 3: Core Development (Backend API, Frontend Components)
- [ ] Phase 4: Integration with OCR Service
- [ ] Phase 5: User Authentication & Authorization Implementation
- [ ] Phase 6: Testing (Unit, Integration, User Acceptance)
- [ ] Phase 7: Deployment & Documentation

## 🔮 Getting Started

*Instructions for setting up the project locally will be provided here once development begins.*

### Prerequisites
*   Node.js / Python
*   npm / yarn / pip
*   A running database instance

### Installation
```bash
# Example commands will be placed here
git clone https://github.com/your-username/online-dead-stock-register.git
cd online-dead-stock-register
npm install
npm run dev

