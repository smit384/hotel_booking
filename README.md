# Hotel Booking Fullstack Web App

This is a full-stack web application for booking hotels, adding new hotels, and logging in with Google. The app is built using modern technologies such as **ExpressJS**, **ReactJS**, and **Cloudinary** for handling media, with **Vite** as the bundler and **TailwindCSS** for styling.

## Features

- **Book a Hotel:** Browse and book your desired hotel easily.
- **Add a Hotel:** Admins or authorized users can add hotels.
- **Google Authentication:** Log in with your Google account for a personalized experience.

## Tech Stack

- **Frontend:** ReactJS, TailwindCSS, Vite
- **Backend:** Node.js, ExpressJS
- **Media Management:** Cloudinary
- **Package Manager:** Yarn
- **Authentication:** Google OAuth

## Installation

### Backend and Frontend Setup

1. Clone the repository
```bash
git clone https://github.com/your-username/hotel-booking-app.git
cd hotel-booking-app/api

# Install dependencies using Yarn

```bash
yarn install

# Set up environment variables in .env file (see .env.example for reference)

PORT=5000
MONGO_URI=your_mongodb_uri
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

# Start the backend server

yarn dev

# ----------------------------------------------------

# Install frontend dependencies
cd ./client
yarn install

# set up appropriate environment variables

VITE_BACKEND_URL=http://localhost:5000
VITE_GOOGLE_CLIENT_ID=your_google_client_id

# Start the dev server

yarn dev
```


### Frontend: 
You can deploy the frontend using services like Vercel or Netlify. Ensure that the frontend environment variables are set correctly for production.

### Contributing
Feel free to open issues and submit pull requests. We welcome all contributions!

Author: Smit Italiya

### Explanation of Sections:

1. **Features**: Describes the key features of the app.
2. **Tech Stack**: Lists all the technologies used.
4. **Installation**: Provides detailed steps for setting up the backend locally.
5. **Deployment**: Offers guidance on deploying the app.
6. **Contributing**: Standard sections to encourage collaboration and specify licensing.

