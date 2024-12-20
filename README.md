# GAMO - Driver's Test Prep Application

## Overview
GAMO is a modern, user-friendly mobile application designed to help users prepare for their driver's license test. Built with React Native and Expo, it offers an interactive learning experience with features focused on driver education and test preparation.

## Core Features

### 1. Authentication System
- Secure login and signup functionality
- Social media integration
- Password recovery
- Session management

### 2. Learning Path
- Structured curriculum with progressive lessons
- Interactive content delivery
- Progress tracking
- XP-based reward system
- Streak tracking for consistent learning

### 3. Study Materials
- Comprehensive handbook sections
- Road signs and signals
- Traffic rules and regulations
- Safe driving practices
- Vehicle maintenance basics
- Emergency procedures

### 4. Progress Tracking
- Detailed statistics dashboard
- Learning analytics
- Achievement system
- Progress visualization
- Performance metrics

### 5. User Experience
- Dark/Light theme support
- Smooth animations
- Gesture-based interactions
- Offline capability
- Accessibility features

## Technical Architecture

### Frontend Structure

app/
├── (auth)/
│ ├── login.tsx
│ ├── signup.tsx
│ └── welcome.tsx
├── (tabs)/
│ ├── index.tsx
│ ├── handbook.tsx
│ ├── statistics.tsx
│ └── settings.tsx
├── lesson/
│ └── [id]/
├── settings/
│ ├── about.tsx
│ └── profile.tsx
└── layout.tsx
src/
├── components/
├── stores/
├── theme/
├── constants/
└── styles/


### Key Technologies
- React Native / Expo
- TypeScript
- Moti for animations
- Expo Router for navigation
- Context API for state management
- Custom theming system

## Design Philosophy
- Modern, clean UI/UX
- Performance-focused architecture
- Accessibility-first approach
- Responsive design
- Progressive enhancement

## Getting Started

### Prerequisites
- Node.js 16+
- Expo CLI
- iOS Simulator or Android Emulator

### Installation

bash
Clone the repository
git clone [repository-url]
Install dependencies
npm install
Start the development server
npx expo start


## Contributing
Contributions are welcome! Please read our contributing guidelines for details on our code of conduct and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.# driving-provisoire
