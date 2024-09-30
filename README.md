# JokerFleet - Social Media Platform

Welcome to **JokerFleet**, a Next.js-powered social media platform that redefines how users interact and connect in the digital world. Whether you’re sharing moments, stories, or ideas, JokerFleet is your playground for building community and engaging with the world.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Folder Structure](#folder-structure)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **User Authentication**: Secure login and registration using Clerk.
- **Real-time Chat and Notifications**: Powered by Liveblocks for seamless interaction.
- **Personalized Profiles**: Users can create and customize their profiles with bio, photos, and interests.
- **Post Creation**: Share updates with text, images, and videos.
- **Interactive Feed**: Like, comment, and share posts within the community.
- **Dark Mode**: Switch between light and dark themes.
- **Responsive Design**: Optimized for all devices—mobile, tablet, and desktop.

---

## Technology Stack

- **Frontend**: Next.js (TypeScript, Tailwind CSS, Shadcn components)
- **Backend**: Node.js, Next.js API routes
- **Authentication**: Clerk
- **Real-time Features**: Liveblocks
- **Database**: PostgreSQL
- **File Storage**: Supabase (Free alternative to AWS)
- **Payments**: Stripe
- **Deployment**: Vercel
- **Monitoring**: Sentry

---

## Installation

To run JokerFleet on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/jokerfleet.git
    ```
    
2. Navigate into the project directory:
    ```bash
    cd jokerfleet
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Set up environment variables by creating a `.env.local` file in the root of the project. See [Environment Variables](#environment-variables) for details.

5. Run the development server:
    ```bash
    npm run dev
    ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

---

## Running the Application

- Development mode:
    ```bash
    npm run dev
    ```
- Build for production:
    ```bash
    npm run build
    ```
- Start the production server:
    ```bash
    npm start
    ```

---

## Folder Structure


VITE_APPWRITE_URL='https://cloud.appwrite.io/v1'
VITE_APPWRITE_PROJECT_ID='Your_Project_ID'
VITE_APPWRITE_STORAGE_ID='Your_Storage_Bucket_ID'
VITE_APPWRITE_DATABASE_ID='Your_Database_ID'
VITE_APPWRITE_USER_COLLECTION_ID='Your_User_Collection_ID'
VITE_APPWRITE_POST_COLLECTION_ID='Your_Post_Collection_ID'
VITE_APPWRITE_SAVES_COLLECTION_ID='Your_Saves_Collection_ID'
"# JokerrFleet" 
