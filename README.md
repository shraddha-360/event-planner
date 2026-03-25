# Event Planner Website

A dynamic event management website built using Craft CMS, designed to showcase different types of events with filtering, search, and detailed pages.

---

## Features

* Event listing (multi-level structure)
* Category-based filtering (Level 2 events)
* Dynamic event detail pages
* Event search functionality
* Blog section with category filter
* Image gallery
* Speaker section
* Responsive design

---

## Tech Stack

* Craft CMS
* Twig (templating)
* Alpine.js (frontend interactivity)
* Tailwind CSS (styling)

---

## Project Structure

* Level 1: Events (Main section)
* Level 2: Event categories (Tech, Music, Startup, Workshops)
* Level 3: Individual events

---

## Key Functionalities

* Dynamic filtering using Alpine.js
* Pagination for event listing
* Blog category filtering
* Form integration (event registration)
* Reusable components (header, footer, sections)

---

## Setup (Local)

1. Clone the repository
2. Place inside htdocs (XAMPP)
3. Import database (.sql file)
4. Update `.env` file
5. Run `composer install`
6. Open in browser:
   http://localhost/project-folder/web

---

## Deployment

* Upload files via FTP
* Create and import database on server
* Update `.env` with live credentials
* Set `PRIMARY_SITE_URL` to domain
* Ensure storage and assets folders are writable

---

## Future Improvements

* Advanced search with filters
* Event booking system
* User authentication
* API integration

---

## Author

Shraddha

---
