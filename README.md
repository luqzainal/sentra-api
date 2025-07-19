# Sentra API Server

API server untuk handle file upload ke AWS S3.

## 🚀 Quick Deploy

### 1. Set Environment Variables
Create `.env` file dengan credentials:

```env
# AWS S3 Configuration
AWS_ACCESS_KEY_ID=your_aws_access_key_here
AWS_SECRET_ACCESS_KEY=your_aws_secret_key_here
AWS_REGION=ap-southeast-1
AWS_S3_BUCKET=sentra-test

# Server Configuration
PORT=3001
NODE_ENV=production
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start Server
```bash
npm start
```

## 📋 API Endpoints

- `GET /api/health` - Health check
- `POST /api/generate-upload-url` - Generate S3 upload URL

## 🔧 DigitalOcean Deployment

1. **Create App** di DigitalOcean App Platform
2. **Set Environment Variables** (AWS credentials)
3. **Deploy** dari GitHub repository

## 📞 Support

Check logs di DigitalOcean dashboard untuk troubleshooting.
