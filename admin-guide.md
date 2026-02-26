# AI Email Intelligence for Zoho CRM — Administrator Guide

## 1. Introduction

This guide is intended for Zoho CRM administrators responsible for installing, configuring, and managing the AI Email Intelligence extension within their organization.

The administrator performs the initial setup and controls how the extension interacts with CRM email data.

---

## 2. Prerequisites

Before installation, ensure:

• You have Administrator privileges in Zoho CRM
• Users have access to Contacts module
• Email integration is enabled in Zoho CRM

---

## 3. Installing the Extension

1. Open Zoho Marketplace
2. Search for **AI Email Intelligence for Zoho CRM**
3. Click **Install**
4. Choose the users or profiles who should access the extension
5. Accept permissions and authorize the extension

After installation, the widget becomes available in Contact records.

---

## 4. Authorization & Connections

During installation, Zoho will request authorization.

The extension uses Zoho’s OAuth authorization to securely access:
• Contact records
• Email related list
• Task creation (only after user action)

No CRM login credentials are stored by the extension.

---

## 5. Initial Configuration

### Access Settings

1. Open a Contact record
2. Open **AI Email Intelligence** panel
3. Click **Settings**

### Configure AI Service

1. Enter the AI API Key
2. Select the preferred AI model
3. Click **Save**

The extension is now activated for all permitted users.

---

## 6. Prompt Configuration

Administrators can customize how AI behaves.

You may configure:

**Summary Prompt**
Controls how email summaries are generated.

**Task Extraction Prompt**
Defines how follow-up tasks are identified.

**Reply Prompt**
Controls tone and communication style for generated emails.

Changes apply immediately to users.

---

## 7. User Access Control

While installing, the administrator can:

• allow access to all users
• restrict to selected profiles
• assign only to sales teams

Only assigned users will see the widget.

---

## 8. Permissions Used

The extension requires limited permissions:

Read Access:
• Contacts
• Emails

Conditional Write Access:
• Tasks (created only when user confirms)

The extension does not modify existing CRM records automatically.

---

## 9. Security & Data Handling

The extension follows secure data handling practices:

• Data processed only when user clicks analyze
• Encrypted communication
• No storage of CRM credentials
• No permanent storage of customer emails

---

## 10. Updating the Extension

Updates are delivered through Zoho Marketplace.

Administrators will be notified inside Zoho CRM when a new version is available.
We recommend keeping the extension updated for security and feature improvements.

---

## 11. Uninstalling the Extension

1. Go to **Setup → Marketplace → Installed Extensions**
2. Locate **AI Email Intelligence for Zoho CRM**
3. Click **Uninstall**

Uninstalling removes the widget from CRM records.
No CRM data will be deleted.

---

## 12. Troubleshooting

### Widget not loading

• Refresh CRM page
• Verify user profile has access

### Users cannot analyze emails

• Ensure email exists in record
• Verify API key configured

### Task creation fails

• Verify user has permission to create tasks

---

## 13. Support

For administrative assistance:

**Email:** [support@techiesaround.com](mailto:support@techiesaround.com)

Please include:
• Organization ID
• CRM edition
• Screenshots
