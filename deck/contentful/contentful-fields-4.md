<!-- Slide 1 -->
# Fields

---

<!-- Slide 2 -->
### How to Create Fields

- **Navigate to Content Model:** Go to the “Content Model” tab in your space and choose the content type you want to add fields to.
- **Add New Field:** Once inside a content type, click “Add Field.”
- **Choose Field Type:** Contentful offers a wide range of field types. After selecting a type, customize the field with a label, help text, and validation rules.
- **Set Field Properties:**
    - **Required Field:** Specify whether the field is mandatory or optional.
    - **Localized Field:** Enable localization to manage content in multiple languages.

---

<!-- Slide 3 -->
### Types of Fields

- **Text Fields**
    - **Short Text:** Ideal for titles, names, or other brief inputs.
    - **Long Text:** Suitable for more extended text input, such as descriptions or body content.
    - **Rich Text:** Allows rich formatting like bold, italics, lists, and embedded links.

---

<!-- Slide 4 -->
### Types of Fields - Continued

- **Media Fields**
    - **Media/Asset:** Used to upload and manage files such as images, PDFs, or videos.
- **Number Fields**
    - **Number (Integer or Decimal):** Used to store numerical values.

---

<!-- Slide 5 -->
### Types of Fields - Continued

- **Date and Time Fields**
    - **Date/Time:** Store a date and time. Can also be used for scheduling or historical data.
- **Boolean Fields**
    - **Boolean (True/False):** A simple toggle field for true/false values.

---

<!-- Slide 6 -->
### Types of Fields - Continued

- **Reference Fields**
    - **Reference:** Used to link one content type to another, creating relationships between entries.
- **Location Fields**
    - **Location:** For storing geographical coordinates (latitude and longitude).

---

<!-- Slide 7 -->
### Types of Fields - Continued

- **JSON Object Fields**
    - **JSON Object:** For storing custom JSON objects, useful for advanced use cases where specific structured data is required.
- **Dropdown and List Fields**
    - **Dropdown (Enumeration):** Predefine a set of options that editors can select from.

---

<!-- Slide 8 -->
### Field Validation Options

- **Character Limits:** Set minimum and maximum character limits on text fields.
- **Number Validation:** Specify range limits for number fields (e.g., prices between 1 and 1000).
- **Regex Validation:** Use regular expressions to enforce specific patterns (e.g., phone number format, email validation).
- **Unique Values:** Ensure that no duplicate values are entered into a field (e.g., unique product SKU).

---

<!-- Slide 9 -->
### Localization and Field Defaults

- **Enable Localization:** If your content is available in multiple languages, you can enable the "localized" option for a field. This allows different values for each locale.
- **Default Value:** Some fields allow setting a default value. This is useful for common fields that usually take the same input (e.g., default date or a common tag).

---

<!-- Slide 10 -->
### Field Grouping and Ordering

- **Field Groups:** To enhance editor experience, fields can be grouped logically. This allows users to easily navigate through different sections of complex content types.
- **Field Ordering:** You can drag and drop fields to organize their order within the content type, ensuring editors fill them in the correct sequence.

---

<!-- Slide 11 -->
### Field Permissions

- **Role-based Access:** You can control which fields are editable by different user roles. Some fields can be hidden or read-only for specific roles. 
