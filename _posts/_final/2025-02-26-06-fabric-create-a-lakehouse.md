---
layout: post
title:  "Creating a Lakehouse in Microsoft Fabric"
author: sanchit
categories: [Fabric, tutorial, microsoft, learn, microsoft fabric, organization, enable, workspaces, workspace]
#image: assets/images/2.jpg
---

This tutorial provides a quick overview of how to create a Lakehouse within Microsoft Fabric.

<video width="640" height="360" controls controlsList="nodownload">
  <source src="https://github.com/imsunchips/tutorial-videos/raw/refs/heads/main/04-fabric-how-to-create-a-fabric-lakehouse.mp4" type="video/mp4">
</video>

## Step-by-Step Instructions

1.  **Navigate to Your Workspace:**
    * Open your Microsoft Fabric workspace where you want to create the Lakehouse.

2.  **Create a New Lakehouse:**
    * Click the **"+ New Item"** button located in the workspace toolbar.

    <img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-13.png?raw=true" width="1000" height="500">

    * A pane will appear on the right side of the screen.
    * In the search bar, type "Lakehouse" and select it from the results.

    <img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-14.png?raw=true" width="1000" height="500">


3.  **Name and Create the Lakehouse:**
    * Provide a descriptive name for your Lakehouse.
    * **Naming Convention:** It's highly recommended to establish a naming convention for your organization. Consider using prefixes or suffixes like "lh-" or "-lh" to easily identify Lakehouses within your workspace as the number of items grows.

    <img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-15.png?raw=true" width="1000" height="500">

    * Click the **"Create"** button.
    * Wait a few seconds for the Lakehouse to be provisioned and ready for use.

    <img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-16.png?raw=true" width="1000" height="500">

**Note:** After creating the Lakehouse, you'll find three associated items within your workspace:

<img src="https://github.com/imsunchips/imanagedata.com/blob/develop/assets/screenshots/01-17.png?raw=true" width="1000" height="500">

1.  **Lakehouse:** The core Lakehouse storage and management component.
2.  **Semantic model:** A model for analyzing the data within the Lakehouse.
3.  **SQL analytic endpoint:** An endpoint for querying the Lakehouse data using SQL.

**We will delve deeper into these three items in future blogs.**