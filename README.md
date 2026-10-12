# Digital-Archive-Repository
A web application for storing, organizing, searching and viewing historical documents, photographs and research records with traceable sources.
# Digital Archive & Repository Management System

A responsive web application for organizing, searching, and managing digital archival records, photographs, research documents, and source references.

## Overview

The Digital Archive & Repository Management System provides a simple interface for managing structured records with metadata and source information. It demonstrates how digital content can be organized for easier discovery, retrieval, and traceability.

This project was developed as a portfolio project to explore frontend development, data management, usability, and digital repository concepts.

## Features

- **Responsive UI:** Adapts to desktop, tablet, and mobile screens.
- **Record Management:** Add, view, edit, and delete archival records.
- **Search Functionality:** Search by title, description, record ID, category, and source.
- **Category Filtering:** Filter records by category and document type.
- **Metadata Management:** Store unique IDs, titles, categories, dates, descriptions, and source references.
- **Source Traceability:** Display source citations alongside repository records.
- **Image Previews:** Display images when a valid image URL is provided.
- **CSV Export:** Export repository records for further analysis.
- **Input Validation:** Validate required fields and source URLs.
- **Browser Storage:** Preserve changes using localStorage.

## Technology Stack

- HTML5 — page structure and semantic markup
- CSS3 — responsive layouts, Flexbox, Grid, and styling
- JavaScript — application logic, DOM manipulation, search, filtering, and validation
- Browser localStorage — persistence of demo records

## Project Structure

```text
digital-archive-repository/
├── index.html
├── styles.css
├── app.js
├── README.md
└── .gitignore
```

## Getting Started

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/digital-archive-repository.git
   ```

2. Open the project folder in VS Code.
3. Open `index.html` in your browser, or use the VS Code Live Server extension.

No package installation or build process is required.

## Deployment

This project can be hosted using GitHub Pages.

1. Push the project files to a GitHub repository.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose the `main` branch and `/(root)` folder.
5. Save and open the published website URL after deployment completes.

## Future Improvements

- Integrate a FastAPI backend.
- Store records in PostgreSQL instead of browser storage.
- Implement server-side search, filtering, and pagination.
- Add user authentication and role-based authorization.
- Add audit logs and record version history.
- Implement automated testing and stronger security controls.

## Limitations

This version is a frontend prototype. Records are stored locally in the browser and are not shared across devices or users. It does not provide production-grade authentication, server-side authorization, or audit logging. The sample records are fictional.

## Disclaimer

This is an independent educational portfolio project. It is not affiliated with or endorsed by any government or military organization. Do not enter classified, confidential, or sensitive information.

## Author

**Bhoomi Gupta**  
B.Tech. — Artificial Intelligence and Machine Learning  
Technocrats Institute of Technology, Bhopal
