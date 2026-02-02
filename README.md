# Strapi CMS – Local Setup Project

## What is Strapi?
Strapi is an open-source headless CMS that helps developers build APIs quickly without worrying about backend boilerplate. Content is managed through an Admin Panel and delivered via REST or GraphQL APIs.

## Why Use Strapi?
- Fast backend/API development
- Headless (works with any frontend)
- Easy content-type creation
- Built-in authentication & roles
- Open source and production ready

## How Strapi Works
- Create content types from Admin UI
- Strapi auto-generates APIs
- Content stored in database
- APIs consumed by frontend apps

---

## Project Overview
This project demonstrates running Strapi locally, creating a sample content type, and following a Git fork → branch → PR workflow.

---

## Tech Stack
- Node.js 20 (LTS)
- npm
- Strapi v5
- SQLite
- Git & GitHub

---

## Project Summary

### Project Setup
- Installed Node.js (v20.20.0) and npm (v10.8.2)
- Created a new Strapi project using `create-strapi-app`
- Configured SQLite as the database
- Skipped TypeScript and example content for a minimal setup

### Content Management
- Created a collection type named **Article**
- Defined the following fields:
  - `title` (Text, required)
  - `description` (Rich Text)
- Added sample entries to validate content creation and management

### Local Development
- Ran Strapi in development mode
- Verified Admin Panel access at `http://localhost:1337/admin`

### Git & GitHub Workflow
- Forked the original Strapi repository
- Created a dedicated feature branch for this task
- Pushed local changes to the forked repository
- Raised a Pull Request targeting the `main` branch



