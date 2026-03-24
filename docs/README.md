# 📄 Documentation

This folder contains detailed documentation for the Employee Helpdesk Portal solution.

## 📌 Contents

Power pages Solution
Power BI file
Power Pages Screenshots


## 📊 Purpose and Logic

This project demonstrates a self-service Employee Helpdesk Portal built using Microsoft Power Pages and Dataverse.

The portal allows authenticated employees to submit support tickets and securely view only their own requests through role-based access control.

### Key Implementation Details

• Authentication is implemented using Microsoft Entra ID login to ensure secure access for employees.

• Table permissions and Web Roles are configured in Power Pages to enforce row-level security, ensuring users can only access their own records.

• Liquid templates are used to dynamically retrieve the logged-in user's Contact ID and filter ticket data accordingly on the **My Tickets** page.

• A ticket submission interface allows employees to create new requests directly from the portal using Dataverse-backed forms.

• A personalized **My Tickets** dashboard displays user-specific tickets by leveraging Liquid-based filtering logic.

• A reporting dashboard has been integrated using Power BI to provide insights into ticket activity and trends.

• The solution is packaged and exported as a Power Platform Solution to support deployment across environments.

This implementation demonstrates secure portal authentication, role-based data access, dynamic content filtering using Liquid, and analytics integration using Power BI within a Power Pages environment.

---
