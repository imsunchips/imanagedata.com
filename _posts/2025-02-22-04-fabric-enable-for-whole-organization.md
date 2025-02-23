---
layout: post
title:  "Enabling Microsoft Fabric for Your Organization (Tenant-Wide)"
author: sanchit
categories: [Fabric, tutorial, microsoft, learn, microsoft fabric, organization, enable, tenant]
#image: assets/images/2.jpg
---

This guide outlines the steps to enable Microsoft Fabric for your entire organization (or a specific security group) within a single tenant. If you manage multiple tenants, these steps must be repeated for each one.

<video width="640" height="360" controls controlsList="nodownload">
  <source src="https://github.com/imsunchips/tutorial-videos/raw/refs/heads/main/03-fabric-how-to-enable-fabric-for-organization.mp4" type="video/mp4">
</video>

## Step-by-Step Instructions

1.  **Access the Admin Portal:**
    * Click the **gear icon (Settings)** in the top right corner of the Power BI interface.
    * Select **Admin portal** from the "Governance and Insights" section.

    <img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-09.png?raw=true" width="1000" height="500">

2.  **Navigate to Tenant Settings:**
    * In the left navigation pane of the Admin portal, choose **Tenant settings**.
    * Locate and expand the **Users can create Fabric items** option.

    <img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-10.png?raw=true" width="1000" height="500">


3.  **Enable Fabric:**
    * The setting will initially display **Disabled**. Toggle the switch to **Enabled**.
    * You'll see two options:
        * **Entire organization:** Enables Fabric for all users within the current tenant.
        * **Specific security groups:** Allows you to limit Fabric access to selected user groups.
    * Choose **Entire organization** (if you want to enable Fabric for everyone in the tenant).
    * Click **Apply** to save your changes.

    <img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-11.png?raw=true" width="1000" height="500">

## Important Considerations

* **Tenant-Level Scope:** Enabling Fabric at the tenant level provides broad access. Ensure you understand the implications before proceeding.
* **Fabric Capacity:** Microsoft Fabric requires capacity. Confirm that your organization has the necessary capacity.
* **Security Groups (Optional):** Use security groups for more granular control over Fabric access.
* **Governance Policies:** Align Fabric usage with your organization's data management and security policies.
* **Multiple Tenants:** Repeat these steps for each tenant that requires Fabric access.