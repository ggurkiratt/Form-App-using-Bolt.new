# Contact Form Application

A modern, responsive contact form built with React, TypeScript, and Tailwind CSS. This application provides a beautiful user interface for collecting contact information and document uploads.


## Prerequisites

Before you begin, ensure you have the following installed:
Node.js (v18 or higher)
npm (v9 or higher)

## Quick Start

1. Clone the repository:bash
git clone <repository-url>
cd contact-form-app
2. Install dependencies:bash
npm install
3. Start the development server:bash
npm run dev
4. Open your browser and visit:http://localhost:5173
## Available Scripts

npm run dev - Starts the development server
npm run build - Creates a production build
npm run preview - Previews the production build locally
npm run lint - Runs ESLint to check code quality

## Project Structure
contact-form-app/
├── src/
│   ├── App.tsx           # Main application component
│   ├── main.tsx         # Application entry point
│   └── index.css        # Global styles and Tailwind imports
├── public/              # Static assets
├── index.html          # HTML template
├── package.json        # Project dependencies and scripts
├── tsconfig.json       # TypeScript configuration
├── tailwind.config.js  # Tailwind CSS configuration
└── README.md          # Project documentation
## Form Fields

The contact form includes the following fields:
First Name (required)
Last Name (required)
Email Address (required, validated)
Phone Number (required, validated)
Company Name (required)
Document Upload (required, supports drag & drop)

## Validation

The form implements the following validations:
All fields are required
Email must be in a valid format
Phone number must contain only digits, spaces, and common separators
File upload is required

## Technologies Used

React 18
TypeScript
Tailwind CSS
Vite
Lucide React (for icons)

## Browser Support

The application supports all modern browsers:
Chrome (latest)
Firefox (latest)
Safari (latest)
Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/amazing-feature)
3. Commit your changes (git commit -m 'Add some amazing feature')
4. Push to the branch (git push origin feature/amazing-feature)
5. Open a Pull Request

