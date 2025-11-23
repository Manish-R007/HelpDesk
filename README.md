Campus Disruption System (CDS) 🏫
📋 Project Overview

A comprehensive issue tracking and management system designed for educational campuses to efficiently report, track, and resolve various types of disruptions and maintenance issues. From LAN connectivity problems to facility maintenance, CDS provides a centralized platform for students, staff, and administrators to collaborate on issue resolution.
🎯 Key Features

    🔧 Real-time Issue Tracking - Monitor issue status from reporting to resolution

    🎯 Smart Priority Detection - AI-powered priority assignment based on content analysis

    👥 Role-based Access Control - Different interfaces for students, staff, and admins

    📱 Responsive Design - Optimized for desktop, tablet, and mobile devices

    🔔 Notifications & Updates - Real-time status updates and comments

    📊 Analytics Dashboard - Comprehensive reporting and statistics

    🏢 Department Assignment - Automatic routing to relevant departments

    📈 Progress Tracking - Visual progress indicators and timelines

    🔍 Advanced Filtering - Smart search and filter capabilities

    📋 Resolution Workflow - Structured resolution process with notes

🏗 System Architecture
text

Frontend (React) → API Gateway (Express) → Backend Services → Database (MongoDB)
        ↓                   ↓                    ↓               ↓
    User Interface    Request Routing    Business Logic      Data Storage
    Real-time Updates Authentication     Priority Detection  User Management
    State Management  Validation         Notifications       Issue Tracking

🛠 Tech Stack
💻 Frontend

    ⚛️ React 18 - Modern UI framework with hooks and functional components

    🎨 Tailwind CSS 3 - Utility-first CSS framework for responsive design

    🔄 React Router 6 - Client-side routing and navigation

    📡 Axios - HTTP client for API communication

    ✨ Framer Motion - Smooth animations and transitions

    📦 Context API - State management across components

    🎯 Custom Hooks - Reusable logic for API calls and state management

🚀 Backend

    🟢 Node.js - JavaScript runtime environment

    ⚡ Express.js - Web application framework

    🍃 MongoDB - NoSQL database for flexible data storage

    📄 Mongoose - MongoDB object modeling for Node.js

    🔐 JWT - JSON Web Tokens for authentication

    🔒 bcrypt - Password hashing and security

    📧 Nodemailer - Email notifications and alerts

    🛡 Helmet - Security middleware

    🌐 CORS - Cross-origin resource sharing

🗄 Database Schema
text

Users → Issues → Comments → Departments → Categories
  ↓         ↓         ↓           ↓           ↓
Roles   Status    Timestamps   Staff      Priorities
        Priority  Attachments  Location   Resolution

🔄 Key Components
🎛 Core Modules

    👤 User Management - Authentication, authorization, profile management

    📝 Issue Management - Creation, tracking, updating, resolution

    💬 Comment System - Real-time communication and updates

    📊 Dashboard - Analytics, statistics, and overview

    🔔 Notification System - Alerts and status updates

    📋 Reporting - Generate reports and insights

🎨 UI Components

    🖼 Modal System - Reusable modal dialogs

    ⌨️ Form Handling - Validation and submission

    📱 Responsive Layout - Mobile-first design

    🎪 Loading States - Spinners and skeleton screens

    📄 Pagination - Efficient data loading

    🔍 Search & Filter - Advanced filtering capabilities

🚀 Installation & Setup
Prerequisites

    Node.js 18.0 or higher

    MongoDB 6.0 or higher

    npm or yarn package manager

Environment Setup
bash

# Clone the repository
git clone https://github.com/your-username/campus-disruption-system.git

# Install dependencies
cd campus-disruption-system
npm install

# Set up environment variables
cp .env.example .env
# Configure your database and other settings

Development
bash

# Start backend server
npm run server

# Start frontend development server
npm run client

# Start both concurrently
npm run dev

👥 User Roles
🎓 Student

    Report new issues

    View own reported issues

    Add comments to issues

    Track issue progress

👨‍💼 Staff

    View department-assigned issues

    Update issue status

    Add resolution notes

    Manage issue priorities

👨‍💼 Admin

    Full system access

    User management

    Department management

    Analytics and reporting

    System configuration

📊 Issue Workflow
text

1. 🆕 Reported → Student submits issue with details
2. 🔍 Triage → System assigns priority and department
3. 📋 Assigned → Issue routed to relevant department
4. 🚧 In Progress → Staff starts working on resolution
5. ✅ Resolved → Issue marked as completed with notes
6. 🔒 Closed → Final verification and archiving

🎯 Smart Features
🤖 Priority Detection

    🔴 Critical - Safety, security, complete outages

    🟠 High - Major functionality broken, multiple users affected

    🟡 Medium - Minor issues, single feature affected

    🟢 Low - Cosmetic issues, enhancement requests

📍 Location Tracking

    Building-level issue tracking

    Room and floor-specific reporting

    Department-based assignment

    Geographic issue clustering

📱 Responsive Design

    💻 Desktop - Full-featured dashboard with advanced controls

    📱 Mobile - Optimized touch interface for on-the-go reporting

    🖥 Tablet - Hybrid interface balancing functionality and usability

🔒 Security Features

    🔐 JWT Authentication - Secure token-based authentication

    👮 Role-based Access Control - Granular permissions per user role

    🔒 Input Validation - Server-side and client-side validation

    📝 Audit Logging - Comprehensive activity tracking

    🛡 Data Encryption - Secure data storage and transmission

🚀 Deployment
Production Build
bash

# Build frontend for production
npm run build

# Start production server
npm start

Environment Configuration
javascript

// Required environment variables
NODE_ENV=production
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
EMAIL_SERVICE=your_email_service
EMAIL_USER=your_email_address
EMAIL_PASS=your_email_password

🤝 Contributing

We welcome contributions! Please see our Contributing Guidelines for details.
Development Workflow

    🍴 Fork the repository

    🌿 Create a feature branch

    💻 Make your changes

    ✅ Add tests

    📦 Commit your changes

    🔀 Create a Pull Request

📄 License

This project is licensed under the MIT License - see the LICENSE.md file for details.
🆘 Support

    📧 Email: support@campusdisruption.com

    💬 Discord: [Join our community]

    📚 Documentation: [Full documentation]

    🐛 Issues: [GitHub Issues]

🙏 Acknowledgments

    Icons and graphics from various open-source libraries

    Inspiration from existing campus management systems

    Contributors and testers from the educational community

Built with ❤️ for better campus management
