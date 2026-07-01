# Parth Home Decor Website

Welcome to the official website repository for Parth Home Decor, a premier home decor and trading company. This repository contains the complete frontend React application that powers the Parth Home Decor website.

## About Parth Home Decor
Parth Home Decor (Parth Traders) is a trusted provider of high-quality home decor products and services. Our commitment to quality, aesthetics, and customer satisfaction drives everything we do. This website serves as our digital platform to showcase our products, outline our services, and connect with our customers.

## Project Overview
This is a modern, responsive React-based frontend application built with the latest web technologies. The website features multiple pages including product showcases, detailed service information, an interactive contact form, and more.

## Key Features
- **Multi-page Application**: Home, About, Products, Services, and Contact pages
- **Responsive Design**: Mobile-first approach using Tailwind CSS
- **Interactive UI Components**: Built with Radix UI primitives and animated with Framer Motion
- **Contact Forms**: Email integration via EmailJS for seamless communication
- **Analytics**: Vercel Analytics for tracking user engagement
- **Modern Build System**: Vite for fast development and optimized production builds

## Technology Stack

### Frontend Framework & Build Tools
- **React 19.2.0**: Modern UI library with the latest features
- **TypeScript 5.8.3**: Type-safe JavaScript for better development experience
- **Vite 8.0.16**: Next-generation frontend build tool for lightning-fast development
- **React Router 6.28.0**: Client-side routing for seamless navigation

### Styling & UI
- **Tailwind CSS 4.2.1**: Utility-first CSS framework for rapid UI development
- **Radix UI**: Unstyled, accessible UI components
- **Framer Motion 12.40.0**: Powerful animation library for React
- **Lucide React**: Clean and modern icon library
- **Recharts**: Composable charting library built on React components

### Additional Libraries
- **EmailJS 4.4.1**: Backend-less email service for contact forms
- **React Hook Form & Zod**: Form validation and state management
- **Vercel Analytics 2.0.1**: User analytics and monitoring

### Development Tools
- **ESLint 9.32.0**: Code linting and quality
- **Prettier**: Code formatting
- **TypeScript ESLint**: TypeScript-aware linting rules

## Project Structure
```text
parthhomedecor-website/
├── frontend/                          # Main frontend application
│   ├── src/
│   │   ├── components/               # Reusable UI components
│   │   ├── pages/                    # Page components
│   │   │   ├── Home.tsx              # Main landing page
│   │   │   ├── About.tsx             # Company information
│   │   │   ├── Products.tsx          # Product showcase
│   │   │   ├── Services.tsx          # Offered services
│   │   │   └── Contact.tsx           # Contact form and information
│   │   ├── data/                     # Static data and constants
│   │   ├── hooks/                    # Custom React hooks
│   │   ├── lib/                      # Utility functions and library wrappers
│   │   ├── assets/                   # Images, icons, and static files
│   │   ├── config/                   # Configuration files
│   │   ├── main.tsx                  # React application entry point
│   │   ├── App.tsx                   # Main application router
│   │   ├── styles.css                # Global styles
│   │   └── vite-env.d.ts            # Vite environment types
│   ├── index.html                    # HTML template
│   ├── vite.config.ts               # Vite configuration
│   ├── tsconfig.json                # TypeScript configuration
│   ├── eslint.config.js             # ESLint configuration
│   ├── components.json              # UI components configuration
│   ├── package.json                 # Dependencies and scripts
│   └── .env.example                 # Environment variables template
└── README.md
```

## Key Components

### Pages
- **Home** - Main landing page highlighting featured products, services, and company overview
- **About** - Company story, mission, vision, and team information
- **Products** - Comprehensive product catalog showcasing our home decor range
- **Services** - Detailed information about the trading and decor services we offer
- **Contact** - Interactive contact form and business location information

### Theming System
The application uses a Tailwind CSS based theming approach combined with Radix UI components:

- **Tailwind v4 Integration**: Leveraging the latest Tailwind engine for optimized styling
- **Custom Fonts**: Typography configured for a premium home decor aesthetic
- **Responsive Typography**: Scales seamlessly across device sizes
- **Dynamic Styling**: Components styled with Tailwind utility classes for extreme flexibility

## Getting Started

### Prerequisites
- Node.js 18.x or higher (recommended 20.x+)
- npm 10.x or higher (or yarn/pnpm)

### Installation
Clone the repository:
```bash
git clone https://github.com/your-username/parthhomedecor-website.git
cd parthhomedecor-website
```

Navigate to frontend directory:
```bash
cd frontend
```

Install dependencies:
```bash
npm install
```

Set up environment variables:
```bash
cp .env.example .env
```
Update the `.env` file with your configuration (EmailJS credentials, etc.)

### Development
Start the development server:
```bash
npm run dev
```
The application will be available at `http://localhost:5173/` (Vite default port)

### Building
Create a production build:
```bash
npm run build
```
This runs TypeScript compilation and Vite build optimization for production deployment.

### Linting & Formatting
Check code quality:
```bash
npm run lint
```

Format code:
```bash
npm run format
```

### Preview Production Build
Preview the production build locally:
```bash
npm run preview
```

## Environment Variables
Create a `.env` file based on `.env.example`:

```env
# EmailJS Configuration
VITE_EMAILJS_SERVICE_ID=your_service_id
VITE_EMAILJS_TEMPLATE_ID=your_template_id
VITE_EMAILJS_PUBLIC_KEY=your_public_key

# Analytics
VITE_ENABLE_ANALYTICS=true
```

## Development Guidelines

### Code Quality
- Use TypeScript for type safety
- Follow ESLint rules defined in `eslint.config.js`
- Format code using Prettier
- Maintain component organization in appropriate directories
- Use React best practices and hooks

### Styling
- Use Tailwind CSS for all utility styles
- Utilize Radix UI components for complex, accessible UI elements
- Maintain design consistency with the established premium decor theme
- Ensure responsiveness across mobile, tablet, and desktop views

## Deployment
The optimized build output will be in the `frontend/dist/` directory after running `npm run build`.

### Deployment Steps
1. Build the application: `npm run build`
2. Deploy the `dist` folder to your hosting platform (Vercel, Netlify, etc.)
3. Configure environment variables on the hosting platform
4. Set up custom domain and SSL certificate

## Contributing
We welcome contributions to improve the website! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code follows our coding standards and passes linting checks.

## Contact & Support
For questions, bug reports, or feature requests:
- **Repository Issues**: GitHub Issues
- **Business Inquiries**: Use the contact form on the website

## Developer Information
**Name**: Aviral Kumar  
**Email**: aviralkumar2003@gmail.com  

**Client Feedback**:  
*"Excellent developer with great skills, incorporates feedback quickly and ensures timely delivery. Glad to have him to make our website and is heavily reliable and trustworthy."*
