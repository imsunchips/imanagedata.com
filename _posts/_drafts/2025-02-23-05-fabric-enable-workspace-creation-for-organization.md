---
layout: post
title:  "Enabling Microsoft Fabric workspace for Your Organization (Tenant-Wide)"
author: sanchit
categories: [Fabric, tutorial, microsoft, learn, microsoft fabric, organization, enable, workspaces, workspace]
#image: assets/images/2.jpg
---

This guide outlines the steps to enable workspace creation in Microsoft Fabric for your entire organization within a single tenant. If you manage multiple tenants, these steps must be repeated for each one.

## Video Tutorial

<video width="640" height="360" controls controlsList="nodownload">
  <source src="https://github.com/imsunchips/tutorial-videos/raw/refs/heads/main/05-fabric-enable-workspace-creation-for-organization.mp4" type="video/mp4">
</video>

## Step-by-Step Instructions

1.  **Access the Admin Portal:**
    * Click the **gear icon (Settings)** in the top right corner of the Fabric interface.
    * Select **Admin portal** from the "Governance and Insights" section.

     <img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-09.png?raw=true" width="1000" height="500">

2.  **Navigate to Workspace Settings:**
    * In the left navigation pane of the Admin portal, choose **Tenant settings**.
    * Scroll down to the **Workspace settings** section.
    * Expand the **Create workspaces** option.

     <img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-12.png?raw=true" width="1000" height="500">

3.  **Enable Workspace Creation:**
    * The setting may initially be **Disabled**. Toggle the switch to **Enabled**.
    * You'll see two options:
        * **The entire organization:** Enables workspace creation for all users within the current tenant.
        * **Specific security groups:** Allows you to limit workspace creation to selected user groups.
    * Choose **The entire organization** (if you want to enable workspace creation for everyone in the tenant).
    * Click **Apply** to save your changes.

## Important Considerations

* **Tenant-Level Scope:** Enabling workspace creation at the tenant level provides broad access. Ensure you understand the implications before proceeding.
* **Security Groups (Optional):** Use security groups for more granular control over workspace creation.
* **Governance Policies:** Align workspace creation with your organization's data management and security policies.
* **Multiple Tenants:** Repeat these steps for each tenant that requires workspace creation access.