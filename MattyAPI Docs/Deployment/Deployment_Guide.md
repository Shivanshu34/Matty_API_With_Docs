
# Deployment Guide for Matty

## Frontend
- Build: `cd client && npm run build`
- Deploy on Vercel or Netlify.

## Backend
- Build Docker image:
  ```
  docker build -t matty-backend:latest .
  ```
- Push to registry and deploy on Render/Railway.

## Environment Variables
- FRONTEND_URL
- DATABASE_URI
- JWT_SECRET
- CLOUDINARY_CLOUD_NAME, API_KEY, API_SECRET
