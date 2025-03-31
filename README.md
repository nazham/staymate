# Staymate

An AI-powered stay finder that helps users discover the best hotels and accommodations based on their preferences and search queries. Staymate leverages artificial intelligence to provide personalized recommendations, ensuring a seamless and efficient booking experience.

## Features
- **AI-Powered Search**: Find the best stays based on your preferences.
- **Real-Time Availability**: Get up-to-date information on hotels and accommodations.
- **Intelligent Filtering**: Filter stays by location, price, ratings, and more.
- **User-Friendly Interface**: Intuitive UI for a smooth booking experience.
- **Secure & Scalable**: Backend built with Node.js, Express, and MongoDB.

## Tech Stack
### Frontend
- React.js (Next.js)
- Tailwind CSS
- Redux Toolkit

### Backend
- Node.js (Express.js)
- MongoDB (Mongoose)
- Clerk Authentication
- Railway (Deployment)

## Project Links
- **Frontend Repository**: [staymate-frontend](https://github.com/nazham/staymate-frontend)
- **Backend Repository**: [staymate-backend](https://github.com/nazham/staymate-backend)
- **Live Application**: [Staymate](https://staymate-frontend.vercel.app/)

## Setup Instructions
### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/nazham/staymate-backend.git
   cd staymate-backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in `.env` file:
   ```env
   PORT=8000
   MONGO_URI=your_mongodb_connection_string
   CLERK_SECRET_KEY=your_clerk_secret
   ```
4. Start the server:
   ```sh
   npm run dev
   ```

### Frontend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/nazham/staymate-frontend.git
   cd staymate-frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in `.env.local` file:
   ```env
   NEXT_PUBLIC_BACKEND_URL=https://staymate-backend-production.up.railway.app
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```

## Contributing
We welcome contributions! Please open an issue or submit a pull request if you’d like to improve Staymate.

## License
This project is licensed under the MIT License.

---

Enjoy seamless stay booking with **Staymate**! 🚀

