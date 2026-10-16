# Portfolio Website

A modern, responsive portfolio website built with React, Tailwind CSS, and Node.js.

## Features

- 🎨 Modern and clean design
- ✨ Smooth animations and transitions
- 📱 Fully responsive
- 📝 Contact form with email functionality
- 🚀 Fast and optimized performance

## Tech Stack

- Frontend:
  - React
  - TypeScript
  - Tailwind CSS
  - Framer Motion
  - React Icons

- Backend:
  - Node.js
  - Express
  - Nodemailer

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Gmail account (for contact form)

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/nashiruddinabbas/Nashir-Portfolio
   cd portfolio
   ```

2. Install frontend dependencies:
   ```bash
   npm install
   npm install --legacy-peer-deps
   npm install ajv --save-dev --legacy-peer-deps
   npm start
   ```



4. Create a `.env` file in the server directory with the following variables:
   ```
   PORT=5000
   EMAIL_USER=your.email@gmail.com
   EMAIL_PASS=your_app_specific_password
   ```
   Note: For Gmail, you'll need to use an App Password. You can generate one in your Google Account settings.

## Running the Application


2. In a new terminal, start the frontend development server:
   ```bash
   cd ..
   npm start
   ```

3. Open [http://localhost:3000](http://localhost:3000) to view the website.

## Building for Production

1. Build the frontend:
   ```bash
   npm run build
   ```



## Customization

- Update personal information in the components
- Modify the color scheme in `tailwind.config.js`
- Add or remove sections as needed
- Update project information in the Projects component

## License

MIT License - feel free to use this template for your own portfolio!

## Contact

For any questions or suggestions, please reach out through the contact form on the website.
