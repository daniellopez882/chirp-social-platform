# Chirp Social Platform

Chirp is a high-performance, full-stack Twitter clone built with modern web technologies. This platform replicates core social media functionalities, providing a seamless experience for posting updates, engaging with content, and real-time interactions.

## 🚀 Key Features

- **User Authentication**: Secure login and session management powered by NextAuth with Google integration.
- **Dynamic Microblogging**: Create, view, and delete tweets with support for text and image uploads.
- **Real-time Interactions**: Instant updates for new tweets and comments using Firebase's real-time capabilities.
- **Threaded Conversations**: Engaging comment system for every tweet.
- **Responsive Interface**: A mobile-first design crafted with Tailwind CSS for a premium feel on all devices.
- **State Management**: Robust state handling using Recoil.

## 🛠️ Technology Stack

- **Frontend**: [Next.js](https://nextjs.org/), [React](https://reactjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Backend Services**: [Firebase](https://firebase.google.com/) (Firestore & Storage)
- **Authentication**: [NextAuth.js](https://next-auth.js.org/)
- **Icons & UI**: [Headless UI](https://headlessui.com/), [Heroicons](https://heroicons.com/)

## 📦 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/daniellopez882/chirp-social-platform.git
   cd chirp-social-platform
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   Create a `.env.local` file in the root directory and add your credentials:
   ```env
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   NEXTAUTH_URL=http://localhost:3000
   NEXTAUTH_SECRET=your_generated_secret
   ```

4. **Initialize Firebase**
   Update the `firebase.js` configuration file with your Firebase project credentials.

5. **Run Development Server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) to view the application.

## 👤 Author

**Daniel Lopez Orta**
- **GitHub**: [@daniellopez882](https://github.com/daniellopez882)
- **Email**: [daniellopezorta39@gmail.com](mailto:daniellopezorta39@gmail.com)

---
*Developed with passion for modern web experiences.*
