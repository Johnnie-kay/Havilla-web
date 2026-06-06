# Havilla Web

A comprehensive web platform for event planning and venue management.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Features](#features)
- [Getting Started](#getting-started)
- [API Documentation](#api-documentation)
- [Project Pages](#project-pages)
- [Contributing](#contributing)

## Overview

Havilla Web is a web application designed to facilitate event planning and venue management. The platform serves multiple user roles including planners, venue owners, and administrators, providing them with dedicated interfaces and tools.

**Repository:** [Havilla-web](https://github.com/Johnnie-kay/Havilla-web)  
**Status:** Active Development  
**Visibility:** Public  
**License:** ISC

## Project Structure

```
Havilla-web/
├── Admin Page/              # Administrator dashboard and controls
├── Planner Page/            # Event planner interface
├── Venue Owner/             # Venue owner management portal
├── Images/                  # Image assets and media files
├── landingPage.html         # Main landing page
├── landingPage.js           # Landing page scripts
├── signin.html              # User sign-in interface
└── signup.html              # User registration interface
```

### Main Pages

| Page | File | Purpose |
|------|------|---------|
| Landing | `landingPage.html` | Main entry point showcasing platform features |
| Sign In | `signin.html` | User authentication interface |
| Sign Up | `signup.html` | New user registration |
| Admin | `Admin Page/` | Administrative management tools |
| Planner | `Planner Page/` | Event planning dashboard |
| Venue Owner | `Venue Owner/` | Venue management portal |

## Features

- **Multi-role Support:** Distinct interfaces for Planners, Venue Owners, and Administrators
- **Authentication:** Secure sign-in and sign-up functionality
- **Event Planning:** Comprehensive event planning tools for users
- **Venue Management:** Dedicated portal for venue owners
- **Admin Controls:** Administrative dashboard for platform management
- **Responsive Design:** HTML-based responsive user interface

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Johnnie-kay/Havilla-web.git
   cd Havilla-web
   ```

2. **Open in Browser**
   - Open `landingPage.html` in your preferred web browser
   - Or serve using a local web server:
   ```bash
   # Using Python
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Navigation**
   - Start from the landing page
   - Navigate to Sign Up to create an account
   - Use Sign In to access the platform based on your role

## API Documentation

### Authentication Endpoints

#### Sign Up
- **File:** `signup.html`
- **Method:** POST
- **Purpose:** Create a new user account
- **Fields:**
  - Email
  - Password
  - User Role (Planner/Venue Owner)
  - Profile Information

#### Sign In
- **File:** `signin.html`
- **Method:** POST
- **Purpose:** Authenticate existing users
- **Fields:**
  - Email
  - Password

### User Role Endpoints

#### Event Planner
- **Location:** `Planner Page/`
- **Functionality:**
  - Create and manage events
  - Browse and book venues
  - Manage event details and timelines

#### Venue Owner
- **Location:** `Venue Owner/`
- **Functionality:**
  - Manage venue information
  - View and respond to booking requests
  - Monitor availability and reservations

#### Administrator
- **Location:** `Admin Page/`
- **Functionality:**
  - User management
  - Platform oversight
  - Content moderation
  - System settings

## Project Pages

### Admin Page
Administrative interface for platform management and user oversight.

### Planner Page
Event planning dashboard with tools for:
- Creating new events
- Searching and filtering venues
- Managing bookings and timelines

### Venue Owner
Management portal for venue proprietors to:
- List and manage properties
- Accept/decline bookings
- Update availability

### Images
Centralized storage for all image assets used throughout the platform.

## Development

### File Organization
- HTML files for page structure
- JavaScript files for interactivity (landingPage.js)
- Images folder for all media assets

### Best Practices
- Keep HTML structure semantic
- Maintain responsive design principles
- Test across different browsers and devices
- Document any custom implementations

## Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Styling:** CSS (Responsive)
- **Architecture:** Client-side MVC pattern

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/Newfeature`)
3. Commit your changes (`git commit -m 'description of Newfeature'`)
4. Push to the branch (`git push origin feature/Newfeature`)
5. Open a Pull Request

## Support

For issues, questions, or suggestions, please open an issue on the [GitHub repository](https://github.com/Johnnie-kay/Havilla-web/issues).

---

- Repository created: June 2026
- Last updated: June 2 2026
