# Analytics Dashboard

This is a static web application that provides an advanced analytics dashboard with data visualization and accessibility features.

## Features

- Interactive Chart.js line chart with multiple series and legend.
- Export options for visible data as CSV and PNG.
- Responsive summary panel with aggregated KPIs.
- Lazy-loaded responsive logo.
- Accessible collapsible 'Report Summary' area with extracted text from PDF.
- Keyboard-accessible filters for date range and series toggles.
- LocalStorage for saving last selected filters.

## Architecture

The application is built using HTML, CSS, and JavaScript with Bootstrap for styling and Chart.js for data visualization. It is designed to be deployed as a static site on GitHub Pages.

## Deployment

1. Clone the repository.
2. Ensure all static assets (CSV, JSON, PDF, logo) are in the root directory.
3. Push the code to a GitHub repository.
4. Enable GitHub Pages in the repository settings.

## Developer Notes

- Ensure all external libraries are loaded via CDN for simplicity.
- The CSV and JSON data are fetched and parsed on the client-side.
- PDF text extraction is simulated; consider using a library like PDF.js for real extraction.
- The application is designed to be responsive and accessible.
