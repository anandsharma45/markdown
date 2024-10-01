---
title: Content Delivery API
description: API that allows you to retrieve published content.
slides: 8
level: Beginner
author: Neha Prakash
designation: Technical Delivery Manager & Trainer
---

<!-- Slide 1 -->
# Content Delivery API

---

<!-- Slide 2 -->
### What is CDA

- The Content Delivery API (CDA) is a read-only API that allows you to retrieve published content from Contentful.
- It’s designed for delivering content across different digital platforms in real-time.
- **Key Points:**
    - Retrieves the latest published content instantly from a Contentful space.
    - Deliver content to any platform using RESTful API requests.
    - Fetch localized content for different markets or languages via the API.

---

<!-- Slide 3 -->
### How CDA Works

- **RESTful Architecture:**
    - CDA uses standard HTTP methods to fetch data. GET requests retrieve content such as entries, assets, and content types.
- **API Endpoint:**
    - Main endpoint: https://cdn.contentful.com/spaces/{space_id}/entries
- **Authentication:**
    - Requires a delivery access token, which is unique to each space.

---

<!-- Slide 4 -->
### Authenticating with CDA

- **Delivery Access Token** is required for every API request.
- **How to Generate:**
    - Go to Settings > API Keys in your Contentful space.
    - Create or view an existing CDA token.
- **Example Request:**
    - GET https://cdn.contentful.com/spaces/{space_id}/entries?access_token={access_token}

---

<!-- Slide 5 -->
### Fetching Content with CDA

- **Fetching Entries:**
    - GET https://cdn.contentful.com/spaces/{space_id}/entries
- **Querying Entries:**
    - GET https://cdn.contentful.com/spaces/{space_id}/entries?content_type=blogPost&fields.author=JohnDoe
- **Pagination:**
    - GET https://cdn.contentful.com/spaces/{space_id}/entries?limit=10&skip=10

---

<!-- Slide 6 -->
### Working with Assets and Media Files

- **Fetching Assets:**
    - Assets such as images, videos, or PDFs are also retrievable:
    - GET https://cdn.contentful.com/spaces/{space_id}/assets

---

<!-- Slide 7 -->
### Limitations of Content Delivery API

- **Published Content Only:**
    - The CDA retrieves only published entries and assets. Draft or archived content is not accessible.
- **Rate Limitations:**
    - Contentful enforces rate limits (default: 55 requests/second). Plan your requests efficiently.

---

<!-- Slide 8 -->

### Documentation

https://www.contentful.com/developers/docs/references/content-delivery-api/
