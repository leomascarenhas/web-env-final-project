# Web Development Environment 1 — Final Project

**Course:** Web Development Environment 1  

**Instructor:** Leonardo Mascarenhas

**Purpose:** Provide a hands-on exercise to install tools, explore a public API, run an existing collection, and write additional API tests.

---

## Overview 💡
This repository contains a starter API testing exercise using the **Art Institute of Chicago (AIC)** public API. Students will:
- Explore the AIC API documentation,
- Use the provided collection (`Art Institute of Chicago API/bruno.json`) to run tests,
- Add and run further tests (manual and automated if they choose),
- Submit results via GitHub.

API docs: https://api.artic.edu/docs/#introduction

---

## What’s in this repo 🔎
- `Art Institute of Chicago API/`
  - `bruno.json` — Postman (or compatible) collection for the exercise
  - `Get all Artworks.bru` — provided request export
- This README — instructions and tasks

---

## Getting started — prerequisites & tools 🔧
Install one of these:
- Bruno https://www.usebruno.com/

Basic steps:
1. Clone the repo:
   ```bash
   git clone <repo-url>
   cd web-env-final-project
   ```
2. Open the folder in your tool of choice and import `Art Institute of Chicago API/bruno.json`.

---

## Use the provided collection
- Import `Art Institute of Chicago API/bruno.json` into Bruno.
- Run the included request "Get all Artworks".
- Inspect response body, headers, and status codes.

---

## Organize your work!
Create a Trello board or a GitHub Project to organize the group tasks.

---

### API tests
Implement at least 3 to 5 additional tests from the list below (or propose their own):
- Verify pagination and `limit` works correctly.
- Validate a response field schema (e.g., each artwork has `id`, `title`).
- Test search/filter endpoint or query parameter (e.g., filter by artist).
- Handle invalid requests (expect 4xx) or empty results.
- Check presence of image URLs and test fetching one image.
- Write a negative test (bad param) and assert correct status code.

---

## HTML Page
Using the data from the AIC API, create a webpage displaying the artworks with the related information: Title, Artist(s), Date and Place of Origin

No need for "Coding": The instructor will provide an html that you can modify to implement your features.

---

## Submission instructions & workflow 📥
- Create a branch `lab1-<yourname>` (e.g., `lab1-leo`).
- Add your tests and any notes/screenshots.
- Update this README with a 1-paragraph summary of your approach and findings.
- Zip your project folder with:
  - README containing all the team members
  - Test files,
  - Screenshot of your trello board,
  - Screenshots / test output logs,
  - A short description of what you implemented and any issues you found.

---

## Tips & resources 💬
- Read the AIC docs carefully before testing.  
- Prefer automated tests for reproducibility (students may choose tools they know).  
- If you’re unsure about a request, add an issue in the repo and tag the instructor.

---

> **Important:** This exercise is about practicing **installation, configuration, and testing of APIs**. Encourage curiosity — explore endpoints, try variations, and document results.


Good luck!
