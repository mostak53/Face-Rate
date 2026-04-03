# Photo Rating App

A full-stack application for rating photos, built with React, Tailwind CSS, and Firebase.

## Features

- **Admin Dashboard**: Upload photos, manage ratings, and export data to Excel.
- **User Dashboard**: Rate photos and view your rating history.
- **Authentication**: Secure Google Login.
- **Real-time Updates**: Instant updates using Firestore.

## Deployment to GitHub Pages

This project is configured for static hosting on GitHub Pages.

### Prerequisites

1.  Create a new repository on GitHub.
2.  Push your code to the repository.

### Deployment Steps

1.  **Configure Firebase**:
    *   Go to the [Firebase Console](https://console.firebase.google.com/).
    *   Navigate to **Authentication > Settings > Authorized domains**.
    *   Add your GitHub Pages domain (e.g., `mostak53.github.io`).
2.  **Deploy**:
    *   Run `npm run deploy`. This will build the app and push the `dist` folder to the `gh-pages` branch.
3.  **Configure GitHub**:
    *   In your GitHub repository, go to **Settings > Pages**.
    *   Set the **Source** to "Deploy from a branch" and select the `gh-pages` branch and `/ (root)` folder.

## Development

To run the project locally:

1.  Install dependencies: `npm install`
2.  Start the development server: `npm run dev`
