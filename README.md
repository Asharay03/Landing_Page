# 🏠 Real Estate Website

A modern, responsive real estate website built with React.js frontend and Node.js backend. The platform provides consultation, design, and marketing services for real estate properties.

## 🌟 Features

### Frontend Features
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Hero Section** - Eye-catching landing area with consultation form
- **Service Sections** - Why Choose Us, About Us, Projects showcase
- **Contact Forms** - Multiple contact forms with real-time validation
- **Newsletter Subscription** - Email subscription functionality
- **Project Gallery** - Showcase of real estate projects
- **Client Testimonials** - Happy clients section
- **Modern UI/UX** - Clean design with Tailwind CSS

### Backend Features
- **RESTful API** - Well-structured API endpoints
- **Contact Management** - Handle contact form submissions
- **Newsletter Management** - Manage email subscriptions
- **Project Management** - CRUD operations for projects
- **Client Management** - Manage client information

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI framework
- **Tailwind CSS** - Utility-first CSS framework
- **Axios** - HTTP client for API calls
- **React Hooks** - State management

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database (assumed)
- **RESTful API** - API architecture

## 📁 Project Structure

```
flipr/
├── controllers/          # Backend controllers
├── models/              # Database models
├── routes/              # API routes
├── server/              # Server configuration
├── flipr-frontend/      # React frontend
│   ├── public/          # Static assets
│   │   └── assests/     # Images and SVG files
│   ├── src/
│   │   ├── admin/       # Admin components
│   │   ├── api/         # API configuration
│   │   ├── assets/      # Frontend assets
│   │   ├── components/  # Reusable components
│   │   └── pages/       # Page components
│   ├── package.json
│   └── tailwind.config.js
├── index.js             # Main server file
├── package.json         # Backend dependencies
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB (for database)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Asharay03/Landing_Page.git
   cd Landing_Page
   ```

2. **Install backend dependencies**
   ```bash
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd flipr-frontend
   npm install
   ```

4. **Environment Setup**
   Create a `.env` file in the root directory:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   NODE_ENV=development
   ```

5. **Start the development servers**
   
   **Backend (from root directory):**
   ```bash
   npm start
   # or for development with nodemon
   npm run dev
   ```
   
   **Frontend (from flipr-frontend directory):**
   ```bash
   cd flipr-frontend
   npm start
   ```

6. **Access the application**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

## 📱 Components

### Main Components
- **Home.jsx** - Main landing page with all sections
- **ContactForm.jsx** - Contact form component
- **ProjectList.jsx** - Display projects
- **ClientList.jsx** - Display client testimonials
- **NewsletterForm.jsx** - Email subscription form

### Key Sections
1. **Hero Section** - Main banner with consultation form
2. **Why Choose Us** - Service highlights with icons
3. **About Us** - Company information
4. **Our Projects** - Portfolio showcase
5. **Happy Clients** - Client testimonials
6. **Newsletter** - Email subscription

## 🎨 Styling

The project uses **Tailwind CSS** for styling with:
- Responsive design principles
- Custom color scheme (blue and orange theme)
- Modern UI components
- Smooth transitions and hover effects

## 📡 API Endpoints

### Contact Routes
- `POST /api/contacts` - Submit contact form
- `GET /api/contacts` - Get all contacts (admin)

### Newsletter Routes
- `POST /api/newsletter` - Subscribe to newsletter
- `GET /api/newsletter` - Get all subscribers (admin)

### Project Routes
- `GET /api/projects` - Get all projects
- `POST /api/projects` - Create new project (admin)
- `PUT /api/projects/:id` - Update project (admin)
- `DELETE /api/projects/:id` - Delete project (admin)

### Client Routes
- `GET /api/clients` - Get all clients
- `POST /api/clients` - Add new client (admin)

## 🔧 Configuration

### Tailwind CSS Configuration
The project includes custom Tailwind configuration for:
- Custom colors
- Font families
- Responsive breakpoints
- Custom utilities

### PostCSS Configuration
Configured for Tailwind CSS processing and optimization.

## 📝 Scripts

### Backend Scripts
```bash
npm start          # Start production server
```

### Frontend Scripts
```bash
npm start          # Start development server
```




## 👥 Authors

- **Asharay Paliwal** -- (https://github.com/Asharay03)

## 🙏 Acknowledgments

- React.js community
- Tailwind CSS team
- All contributors and testers


---

⭐ **Star this repository if you find it helpful!**
