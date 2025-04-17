# Careers Proxy for Workday RAAS

Simple Express proxy that fetches jobs from a secured Workday JSON API and exposes them over a public CORS-enabled `/jobs` endpoint.

## Setup

1. Create a `.env` file based on `.env.example`:
```
WORKDAY_USERNAME=your-username
WORKDAY_PASSWORD=your-password
```

2. Install dependencies:
```
npm install
```

3. Run locally:
```
npm start
```

4. Deploy on Railway and set environment variables in the dashboard.
