---
title: Content Type
description: A **Content Type** in Contentful is a template that defines the structure of a particular type of content.
slides: 6
level: Beginner
author: John Doe
designation: Senior Web Developer & Trainer
---

<!-- Slide 1 -->
# Content Type

---

<!-- Slide 2 -->
### What is a Content Type

- A **Content Type** in Contentful is a template that defines the structure of a particular type of content.
- It’s a blueprint that consists of multiple fields which describe the properties of that content.
- **Types of Content Type:**
    - **Assemblies** are content types that hold (or link to) other content types
    - **Topics** are content types that contain pure content


---

<!-- Slide 3 -->
### Fields of Content Type

- **Settings:** Name, ID, Localisation, Formatting options in case of RTE
- **Validations:** Required field, Character limit count, match specific pattern, prohibit specific pattern, accept specified values
- Default Value
- **Appearance:** Single Line, Multiple Line, Markdown, Dropdown, Radio, Asset Card, Object, Json, Custom

---

<!-- Slide 4 -->
### How to Create a Content Type

- **Access Contentful:** Log in to your Contentful account and navigate to your desired space.
- **Go to Content Model:** Click on the "Content model" tab in the top bar.
- **Add Content Type:** Click the "Add content type" button.
- **Define the Name:** Give your content type a descriptive name (e.g., "Blog Post," "Product").
- **Add Description:** Optionally, provide a description to clarify the purpose of the content type.
- **Set Icon:** Choose an icon to represent the content type visually in the Contentful dashboard.

---

<!-- Slide 5 -->
### Configuring Fields

- **Add Fields:** After creating the content type, you can add fields:
    - **Field Name:** A label for the field (e.g., "Title").
    - **Field Type:** Choose from various types like Text, Rich Text, Media, Number, etc.
    - **Validation Rules:** Set rules to ensure data integrity (e.g., required fields, character limits).
    - **Localized:** Optionally enable localization for multi-language support.
- **Organizing Content Types:**
    - **Create Hierarchies:** Establish parent-child relationships between content types (e.g., a "Category" content type could be a parent of "Product").

---

<!-- Slide 6 -->
### Versioning and Updates

- **Version Control:** Content types can be updated over time. Contentful maintains a version history, allowing you to track changes or revert if necessary.
- **Deactivation:** If a content type is no longer needed, you can deactivate it without losing existing entries.
