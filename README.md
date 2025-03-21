# DRIVE - VANET Frontend

![DRIVE Logo](./public/assets/drivelogo.jpg)

## Overview

The DRIVE frontend is a modern, responsive React application for the Vehicular Ad Hoc Network (VANET) traffic management system. It provides an intuitive interface for users to interact with the VANET system, visualize traffic data, and access advanced traffic management features.

## Features

- **Modern UI**: Beautiful, responsive design with animations and transitions
- **Interactive Dashboard**: Real-time traffic visualization and management
- **Feature Exploration**: Detailed information about VANET technology features
- **Customizable Interface**: Theme customization and logo personalization
- **Animated Components**: Smooth transitions and engaging user experience
- **Mobile-Friendly Design**: Works seamlessly across devices of all sizes

## Technologies Used

- **React**: Frontend library for building user interfaces
- **Framer Motion**: Animation library for creating fluid UI animations
- **GSAP**: GreenSock Animation Platform for advanced animations
- **CSS3**: Advanced styling with CSS variables, gradients, and transitions
- **Intersection Observer API**: For scroll-based animations and effects
- **React Router**: For navigation and routing between components

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)

### Installation

1. Navigate to the frontend directory:
   ```bash
   cd VANET-main/frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
frontend/
├── public/                # Public assets and HTML template
│   ├── assets/            # Images and static assets
│   │   ├── logo192.png        # Default logo
│   │   └── index.html         # HTML template
│   ├── src/                   # Source code
│   │   ├── components/        # React components
│   │   │   ├── Header.js      # Application header with navigation
│   │   │   ├── HomePage.js    # Main landing page
│   │   │   ├── FeaturesPage.js # Features showcase page
│   │   │   ├── AboutPage.js   # About information page
│   │   │   └── LogoUploader.js # Logo customization component
│   │   ├── styles.css         # Global styles
│   │   ├── App.js             # Main application component
│   │   └── index.js           # Application entry point
│   └── package.json           # Project dependencies and scripts
```

## Core Components

### Header
The application header provides navigation and branding. It includes a responsive design with a mobile-friendly menu and smooth animations.

### HomePage
The main landing page features:
- Hero section with animated typography
- Traffic simulation visualization
- Key feature highlights with animations
- Call-to-action sections

### FeaturesPage
An interactive showcase of VANET technology features:
- Interactive tabs for different features
- Detailed information with benefits and applications
- Visual representations and animations
- Color palette showcase

### AboutPage
Information about the DRIVE project, including:
- Project overview
- Technology stack details
- Development team information

### LogoUploader
Allows users to customize the application with their own logos:
- Logo upload functionality
- Pre-set logo options
- Preview functionality

## Styling System

The application uses a comprehensive styling system with CSS variables for consistent theming:

- **Color Variables**: Primary, secondary, accent, and utility colors
- **Gradient Combinations**: Various gradient patterns for visual appeal
- **Animation Utilities**: Consistent transitions and animations
- **Responsive Breakpoints**: Mobile-first design approach

## Available Scripts

- `npm start`: Starts the development server
- `npm build`: Creates an optimized production build
- `npm test`: Runs the test suite
- `npm eject`: Ejects from Create React App configuration

## Contribution Guidelines

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- All contributors to the DRIVE VANET project
- React and its ecosystem of libraries
- The open-source community for inspiration and resources
- 
