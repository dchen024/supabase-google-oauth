# EcoIsland

### Fitch Group + Earth Matters Sustainability Hackathon NYC Fall 2024

**Created by:** Daniel Chen, Wilson Liu, Bi Rong Liu, and Adam Elsayed

![EcoIsland Home Page](ecoisland_homepage.png)

## Demo Video

  <a href="https://youtu.be/y03QCVIFyu4">
    <img src="https://img.youtube.com/vi/y03QCVIFyu4/1.jpg" alt="Quizify Demo Video" width="800">
  </a>


## Project Overview

EcoIsland provides both customers and vendors with tools to manage and track reusable containers. It offers real-time data on the environmental impact of returning containers, user-specific metrics, and a loyalty points system.

### Inspriation
We were inspired by the global movement toward sustainability and reducing single-use plastics. Governors Island provided the perfect opportunity to promote reusable containers and reduce waste.

### Key Users:

- **Customers**: Track their impact, earn points for returning containers, and view recent container transactions.
- **Vendors**: Activate containers and track their status through QR code scanning.

## Features

- **QR Code Scanning**: Track reusable containers by scanning QR codes.
- **User Metrics**: View personal environmental impact and recent returns.
- **Vendor Tools**: Activate and manage containers with QR codes.
- **Real-Time Updates**: Track containers, users, and returns in real-time.
- **Loyalty Program**: Earn points for returning containers and contributing to sustainability goals.

## Technologies Used

- **Frontend**:
  - Next.js 14
  - TypeScript
  - Tailwind CSS
  - shadcn
- **Backend**:
  - Node.js
  - Supabase
- **Authentication**: OAuth2 (Google) via Supabase
- **Database**: Supabase

## App Preview

### Admin Panel
![EcoIsland Admin Panel](ecoisland_admin.png)

### User Metrics
![EcoIsland User Metrics](ecoisland_metrics.png)

### Leaderboard
![EcoIsland Leaderboard](ecoisland_leaderboard.png)

## Installation

To get started with EcoIsland locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/ecoisland.git
   ```

2. **Navigate into the project directory**:

   ```bash
   cd ecoisland
   ```

3. **Install dependencies: Make sure you have Node.js installed, then run**:

   ```bash
   npm install
   ```

4. **Set up environment variables: Create a .env.local file in the root directory and add your environment variables**:
   ```bash
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```
5. **Run the development server**:
   ```bash
   npm run dev
   ```

## Usage

- **Sign up/Login**: Create an account or log in using Google OAuth2.
- **Scan QR Code**: Customers and vendors can scan container QR codes to track and manage returns.
- **View Metrics**: Users can track their environmental impact and return history.
- **Vendor Dashboard**: Vendors can activate and manage container statuses.
