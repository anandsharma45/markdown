---
title: Contentful Images API
description: Resize, crop, fit, and format images dynamically.
slides: 7
level: Beginner
author: John Doe
designation: Senior Web Developer & Trainer
---

<!-- Slide 1 -->
# Images API

---

<!-- Slide 2 -->
### Key Features of the Contentful Images API

- **Image Transformations:**
    - Resize, crop, fit, and format images dynamically.
- **Format Conversion:**
    - Convert images to popular web formats (JPEG, PNG, WebP).
- **Lazy Loading & Caching:**
    - Ensure images load quickly with caching and lazy-loading techniques.
- **Content Delivery Network (CDN):**
    - All images are delivered via a globally distributed CDN.

---

<!-- Slide 3 -->
### How Image API Works

- **Endpoint:**
    - Images stored in Contentful assets are delivered through the CDN endpoint:
    - https://images.ctfassets.net/{space_id}/{asset_id}/{file_name}
- **Image Transformations:**
    - Image transformations can be applied as query parameters, directly in the URL.
    - Example: https://images.ctfassets.net/{space_id}/{asset_id}/{file_name}?w=300&h=300

---

<!-- Slide 4 -->
### Image Resizing and Cropping

- **Resizing Parameters:**
    - ?w=400&h=400
- **Cropping:**
    - ?w=400&h=300&fit=crop
- **Example:**
    - https://images.ctfassets.net/{space_id}/{asset_id}/{file_name}?w=300&h=300&fit=thumb

---

<!-- Slide 5 -->
### Format Conversion

- **Supported Formats:**
    - JPEG, PNG, WebP
- **Format Conversion Query Parameter:**
> ?fm=webp
- **Example:**
    - https://images.ctfassets.net/{space_id}/{asset_id}/{file_name}?fm=webp

---

<!-- Slide 6 -->
### Image Quality, Focul Point & Cropping

- **Quality Control:**
    - ?q=80
- **Focul Point Cropping:**
    - ?fit=crop&f=faces
- **Custom Focal Points:**
    - ?focal_point=x,y

---

<!-- Slide 7 -->
### Image Flipping, Rotation, and Orientation

- **Flipping Images:**
    - ?flip=h
- **Rotation:**
    - ?r=90
- **Orientation Correction:**
    - >auto=compress