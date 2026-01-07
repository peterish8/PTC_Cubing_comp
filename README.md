# PTC Cubing Competition - Season 2

A dynamic and modern web application built for the **Prathick The Cube.R** Season 2 Cubing Competition. This platform serves as the central hub for the event, offering registration, event details, and personalized dashboards for participants and organizers.

## 🚀 Features

- **Immersive Landing Page**:
  - Interactive 3D Cube elements.
  - Smooth parallax scrolling and particle effects.
  - Comprehensive sections: About, Benefits, Team, and Previous Season Highlights.
- **Participant Portal**:
  - Secure login access for registered competitors.
  - View room assignments, schedules, and live results.
- **Admin Dashboard**:
  - Backend management for event organizers.
  - Participant tracking and score management.
- **Responsive Design**: Mobile-first approach ensuring a seamless experience across all devices.
- **Modern UI/UX**: Built with a dark-themed, premium aesthetic using Tailwind CSS and Radix UI.

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: 
  - [Tailwind CSS](https://tailwindcss.com/)
  - [Styled Components](https://styled-components.com/)
- **Components**: 
  - [shadcn/ui](https://ui.shadcn.com/) (Radix UI primitives)
  - [Lucide React](https://lucide.dev/) (Icons)
- **Backend & Database**: [Firebase Firestore](https://firebase.google.com/)
- **Animations**: `tailwindcss-animate`, Magic UI

## 📋 Prerequisites

Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) or [pnpm](https://pnpm.io/)

## ⚙️ Installation & Setup

1.  **Clone the repository**
    ```bash
    git clone <repository-url>
    cd PTC-Cubing-Comp-Website/PTC_Cubing_comp
    ```

2.  **Install Dependencies**
    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

3.  **Environment Configuration**
    Create a `.env.local` file in the root directory and add your Firebase configuration:
    ```env
    NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
    NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
    NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
    NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
    NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
    NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
    ```

4.  **Run the Development Server**
    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📂 Project Structure

- `/app`: Key application pages and routing (Next.js App Router).
- `/components`: Reusable UI components (buttons, cards, landing page sections).
- `/lib`: Utility functions and Firebase configuration (`auth.ts`, `firebase.ts`).
- `/public`: Static assets (images, icons).
- `/styles`: Global styles.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
