# React Frontend with Azure AD SSO (MSAL.js)
This is a demo React app using MSAL.js for Single Sign-On (SSO) via Azure AD.
## Configuration:
- Replace the following placeholders in `src/authConfig.js` with your Azure AD tenant and client details:
  - `clientId`
  - `tenantId`
  - `authority`
## Role-Based Access:
- The app checks user roles to allow access to specific pages based on claims.
