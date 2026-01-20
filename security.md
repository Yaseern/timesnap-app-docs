# TimeSnap for Jira Security Policy

**TimeSnap for Jira** is a Forge-powered app for Jira Cloud, designed with security and privacy in mind.

---

## Data Storage

- All End-User Data (worklogs, user-specific settings) is stored securely in **Atlassian Forge KVS**.
- Only the **current user and Jira admins** can access this data.
- No data is stored on external servers or third-party services.

---

## Data Transmission

- All communications between the app and Jira are encrypted using **HTTPS**.
- Sensitive data is transmitted only to Atlassian APIs within Jira Cloud.

---

## Access Control
  
- The app only performs actions the user is authorized to perform in Jira.

---

## Security Updates

- All updates are deployed through Atlassian Forge, which manages the **secure execution environment**.
- Dependencies are monitored and updated regularly.

---

## Reporting Security Issues

If you discover a security vulnerability, please report it via email:  
**yaseermunas@mail.com**

---

## Compliance

- TimeSnap complies with **GDPR** by acting as a **data processor**.  
- Atlassian customers are the **data controllers**, and the app only processes data on their behalf.

