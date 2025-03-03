### rapid_compliance_checker1

# Overview
Rapid Compliance Checker is a real-time parcel compliance verification system designed for small export businesses. It automates compliance checks before courier handoff, ensuring adherence to regulatory requirements and preventing illegal shipments.

# Features
- Real-time Validation: Automatically checks for missing fields, restricted items, and destination restrictions.
- Dashboard Interface: Provides a user-friendly interface for monitoring parcel compliance status.
- Alerts & Notifications: Flags issues and sends alerts for non-compliant shipments.
- Admin Control: Allows admins to review, approve, or reject parcels before dispatch.

# Tech Stack
- Frontend : HTML, CSS, Javascript
- Backend: Node.js, Express.js
- Middleware: MongoDB (used as an intermediary for data processing and validation)

# Installation & Setup

# Prerequisites
- Node.js and npm installed


# Steps
1. Clone the repository:
   sh
   git clone https://github.com/your-username/rapid-compliance-checker.git
   
2. Navigate to the project directory:
   sh
   cd rapid-compliance-checker
   
3. Install dependencies:
   sh
   npm install
   
4. Set up the database in XAMPP and configure connection in compliancechecker/db.js.
5. Start the server:
   sh
   npm start
   Nodemon server.js
   

# Project Structure
- package.json - Project dependencies and scripts
- server.js - Main server file
- db.js - Database connection setup
- rules.json - Compliance rules for parcels
- models/Parcel.js - Parcel database model
