# Insurance Fraud Detection Platform

An advanced web-based insurance fraud detection platform leveraging AI technologies to provide proactive fraud prevention and user-friendly risk management.

## Features

- React.js frontend with interactive dashboards
- AI-powered fraud detection algorithms
- Real-time claim tracking and risk assessment
- OpenAI-integrated chatbot for fraud query support
- Responsive design for multiple device support

## Local Development Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya-Sureka/insurance-fraud-detection.git
   cd insurance-fraud-detection
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Update the values in `.env` with your actual credentials:
     ```
     OPENAI_API_KEY=your_openai_api_key
     VITE_OPENAI_API_KEY=your_openai_api_key
     SESSION_SECRET=your_session_secret
     ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open http://localhost:5000 in your browser

## Deployment on Vercel

1. Fork or push this repository to your GitHub account

2. Create a new project on Vercel:
   - Go to [Vercel](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Select the "Insurance Fraud Detection" repository

3. Configure environment variables:
   - In Vercel project settings, add the same environment variables from your `.env` file

4. Deploy:
   - Vercel will automatically build and deploy your application
   - Any future pushes to your main branch will trigger automatic deployments

## Tech Stack

- Frontend: React.js with TypeScript
- Backend: Express.js
- UI Components: shadcn/ui
- Authentication: Passport.js
- AI Integration: OpenAI API
- Charts: Recharts

## Development Commands

- `npm run dev`: Start development server
- `npm run build`: Build for production
- `npm run start`: Start production server

## License

MIT License - feel free to use this code for your own projects!#   A I - P r o t o t y p e  
 