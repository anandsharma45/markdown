---
title: Content Custom Apps
description: Custom apps are external applications or interfaces that integrate directly into the Contentful environment.
slides: 7
level: Beginner
author: Neha Prakash
designation: Senior Web Developer & Trainer
---

<!-- Slide 1 -->
# Custom Apps

---

<!-- Slide 2 -->
### Dfinition & Uses

- Custom apps are external applications or interfaces that integrate directly into the Contentful environment.
- Provide specialized UI, features, and integrations beyond native Contentful capabilities.
- Custom apps allow businesses to address specific challenges or features that are not covered by standard Contentful.
- Allows integration with external APIs, databases, or services to bring additional functionality into the Contentful editor.

---

<!-- Slide 3 -->
### Where Custom Apps Fits

- **Entry Editor Extensions:**
    - Add custom apps as tabs or panels within the entry editor for specific content types.
- **Field Extensions:**
    - Build custom field editors that can replace or enhance default fields (e.g., color picker, maps, or rich media).
- **Page Extensions:**
    - Add standalone pages within the Contentful web app to show dashboards, reports, or tools relevant to your workflow.

---

<!-- Slide 4 -->
### Technologies Behind Custom Apps

- **React.js / Typescript:**
    - Contentful’s Custom Apps are built using React, Typescript enabling rich user experience of the app.
- **Contentful App Framework:**
    - Use the App SDK to communicate with Contentful APIs.
- **APIs and Webhooks:**
    - Integrate with the CMA, CDA, and webhooks to automate and enhance workflows.

---

<!-- Slide 5 -->
### Steps to Create a Custom App

- **Install the Contentful CLI:**
    - npm install -g contentful-cli
- **Command to create App scaffold:**
    - npx @contentful/create-contentful-app my-first-app
- **Command to create App definition:**
    - npm run create-app-definition

---

<!-- Slide 6 -->
### Creating an App Definition

- Access Contentful Web App
- Go to 'Apps' Section
    - In the **Settings** menu, find and select the **Apps** option.
- Create New App Definition
    - Click on **"Create App"**.
    - Provide name and description.
    - Add App Locations.
    - Provide Installation URL.
    - Configure App Permissions.
    - Save and Install App Definition.

---

<!-- Slide 7 -->
### App Locations

- **Entry Field**: Custom App appearance for chosen field types
- **Entry Editor**: Custom panel in entry editors.
- **Entry Sidebar**: Sidebar widget.
- **Page**: Standalone app page.