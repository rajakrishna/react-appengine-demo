# React + App Engine

## Development Setup

Install dependencies:
```bash
npm install
```

Start the development server:
```bash
npm run dev
```

## Deployment to Google App Engine

For a detailed step-by-step guide, check out this [blog post](https://medium.com/@rajakrishna/how-to-deploy-a-react-vite-app-to-google-app-engine-step-by-step-guide-d34579e8ee65).

### Prerequisites
- Google Cloud SDK installed
- A Google Cloud Project
- App Engine enabled on your project

### Steps to Deploy

Build the app for production:
```bash
npm run build
```

Enable App Engine (if not already enabled):
```bash
gcloud app create
```

Deploy to App Engine:
```bash
gcloud app deploy
```

View your deployed app:
```bash
gcloud app browse
```

Your app will be available at `https://<PROJECT_ID>.appspot.com`
