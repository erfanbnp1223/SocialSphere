# SocialSphere - Social Media Service Panel

A modern social media service panel built with React, TypeScript, and Express.js with BDClick24 API integration.

## Features

- 🚀 Modern React frontend with TypeScript
- 🎨 Beautiful UI with TailwindCSS and Material Design
- 🔐 Firebase Authentication with demo mode
- 📱 Mobile-first responsive design
- 🛒 Order management system
- 💰 Balance and payment tracking
- 👨‍💼 Admin panel for service management
- 🔄 Real-time order status updates
- 📊 1000+ social media services (Instagram, Facebook, YouTube, TikTok, etc.)

## Tech Stack

### Frontend
- React 18 with TypeScript
- TailwindCSS for styling
- Wouter for routing
- TanStack Query for data fetching
- Firebase for authentication

### Backend
- Express.js with TypeScript
- BDClick24 API integration
- JSON file-based persistent storage
- CORS enabled for cross-origin requests

## Deployment

### Vercel Deployment

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/socialsphere.git
   git push -u origin main
   ```

2. **Deploy to Vercel:**
   - Connect your GitHub repository to Vercel
   - Set environment variables in Vercel dashboard:
     - `BDCLICK24_API_KEY=your_api_key_here`
     - `ADMIN_KEY=dev`
   - Deploy automatically

### Environment Variables

Create a `.env` file in the root directory:

```env
ADMIN_KEY=dev
BDCLICK24_API_KEY=your_api_key_here
```

## Local Development

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Set up environment variables:**
   ```bash
   cp .env.example .env
   # Edit .env with your API keys
   ```

3. **Start development server:**
   ```bash
   npm run dev
   ```

4. **Build for production:**
   ```bash
   npm run build
   ```

## Admin Panel

Access the admin panel at `/admin` with credentials:
- Email: `darkerfanx@gmail.com`
- Password: `Erfaranbnp123`

## API Integration

The app integrates with BDClick24 API for:
- Fetching available services
- Placing orders
- Checking order status
- Managing service pricing

## License

MIT License
