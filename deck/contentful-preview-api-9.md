---
title: Content Preview API
description: The Content Preview API allows preview of unpublished content.
slides: 6
level: Beginner
author: Neha Prakash
designation: Technical Delivery Manager & Trainer
---

<!-- Slide 1 -->
# Content Preview API

---

<!-- Slide 2 -->
### What is Preview API

- The Content Preview API allows preview of unpublished content.
- This is a read only API
- Provides a real-time, unpublished version of entries and assets, helping you ensure content looks correct before publishing.
- API Base URL: https://preview.contentful.com

---

<!-- Slide 3 -->
### How Preview API Works

- **Endpoint:**
    - https://preview.contentful.com/spaces/{space_id}/environments/{environment_id}/entries
- **Accessing Draft Entries:**
 - https://preview.contentful.com/spaces/{space_id}/entries/{entry_id}
 
---

<!-- Slide 4 -->
### Authentication for Preview API

- **Access Token:**
    -The Preview API requires a preview API key (separate from the Delivery API key) for authentication.
- **Setup:**
    - In Contentful, navigate to Settings > API Keys and create a Preview API key.
    - Use the generated space ID and access token to make authenticated requests.

---

<!-- Slide 5 -->
### Setting Up a Preview Environment

- **Environment Configuration:**
    - Set up different environments, and preview content specific to those environments.
- **Contentful Web App Integration:**
    - Contentful’s Web App has a built-in preview button that, when configured, redirects editors to a preview environment to see unpublished changes.
- **Setting the Preview URL:**
    - In Settings > Environments, configure a custom preview URL for each environment, linking to your preview site.

---

<!-- Slide 6 -->
### Limitations of the Preview API

- **Performance:**
    - The Preview API may be slightly slower than the Delivery API due to additional processing for unpublished content.
- **No Access to Deleted Entries:**
    - Entries that have been deleted from Contentful will not appear in the Preview API.
- **Rate Limits:**
    - The Preview API has rate limits that may affect how frequently content can be fetched. Default is 14 requests/second.
