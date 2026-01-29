# 🎥 Yoom - Real-Time Video Conferencing App

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Next.js](https://img.shields.io/badge/Framework-Next.js-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-6C47FF?logo=clerk)](https://clerk.com/)
[![getstream](https://img.shields.io/badge/Real--Time-Stream-005FFF?logo=stream)](https://getstream.io/)
[![shadcn/ui](https://img.shields.io/badge/UI-shadcn/ui-black)](https://ui.shadcn.com/)

A high-performance, full-stack video conferencing application built with Next.js, TypeScript, and Stream's Video SDK. Engineered for real-time, low-latency media streaming, and a seamless user experience.

## 🛠 Engineering Highlights
Building a video platform requires robust handling of real-time data and state. Here’s how this project tackles the core engineering hurdles:

*   **Real-Time Communication:** Leverages **Stream's Video & Voice SDK** to handle the complexities of WebRTC, including signaling, media stream optimization, and connection lifecycle management. This ensures reliable and scalable video sessions.
*   **Modern Full-Stack Architecture:** Built on **Next.js**, providing a powerful foundation with server-side rendering (SSR), static site generation (SSG), and seamless API route integration.
*   **Secure Authentication:** Integrates **Clerk** for hassle-free, secure, and customizable user authentication, supporting various sign-in methods out of the box.
*   **Component-Based UI:** Developed with **React** and styled using **Tailwind CSS** with **Shadcn/UI** for a professional, responsive, and easily maintainable design system.

## 🚀 Technical Stack
-   **Framework:** Next.js
-   **Language:** TypeScript
-   **Real-Time Video/Audio:** Stream Video SDK
-   **Authentication:** Clerk
-   **UI/Styling:** Tailwind CSS & Shadcn/UI
-   **State Management:** React (Hooks & Context API)

## ✨ Core Features
-   **Secure Authentication:** Log in with Google or other social providers.
-   **Create & Schedule Meetings:** Instantly create a new meeting or schedule one for later.
-   **Personal Meeting Room:** Join a personal, dedicated meeting room.
-   **Recording & Playback:** Record meetings and view past recordings.
-   **Real-Time Interaction:** See a list of upcoming meetings and join with one click.

## 📦 Local Setup & Installation

### Prerequisites
-   Node.js (v18.x or higher)
-   npm or yarn

### 1. Clone the Repository
```bash
git clone https://github.com/Manthan03583/zoom-clone.git
cd zoom-clone
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Environment Configuration
Create a `.env.local` file in the root directory and add the necessary environment variables for Clerk and Stream.

```bash
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# Stream
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

### 4. Run the Application
```bash
npm run dev
```
The app will be available at `http://localhost:3000`.

## 📈 Future Roadmap
-   **Advanced Participant Controls:** Mute/unmute, start/stop video for other participants.
-   **Interactive Features:** Implement features like polling, Q&A, and virtual backgrounds.
-   **Data Channel Integration:** Use WebRTC DataChannels for low-latency file sharing and chat during calls.

**Author:** Manthan Moharana

Focused on building the future of real-time communication.
