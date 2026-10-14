# Food Ordering System – Frontend

A responsive Food Ordering System frontend built with React and Vite. This project integrates with a Django REST Framework backend to provide a complete food-ordering experience.

## Live Demo

**Frontend:** [Food Ordering System](https://food-ordering-system-123-8ah1kexf0-ishrat-talib.vercel.app/)

### Demo Login Credentials

Use the following credentials to test the application.

**Admin Sign In**

- Email: `admin2@gmail.com`
- Password: `admin123`

**Test User Sign In**

- Email: `sara@gmail.com`
- Password: `sara123`

## Technologies Used

- React
- JavaScript
- Vite
- HTML5
- CSS3
- React Router
- Redux Toolkit
- React Redux
- React Icons

## About the Project

This Food Ordering System is a full-stack web application developed using React for the frontend and Django REST Framework for the backend. Both applications are maintained in separate repositories and integrated through API communication.

### Project Repositories

- **Frontend Repository:** [Food-Ordering-System](https://github.com/Ishratalib/Food-Ordering-System)
- **Backend Repository:** [Backend-of-Food-ordering](https://github.com/Ishratalib/Backend-of-Food-ordering)

To run the complete project locally, refer to the README files in both repositories. They provide the setup instructions, dependencies, environment configuration, and commands required to run the frontend and backend on your local machine.

## Project Structure

[View Complete Frontend Project Structure](https://github.com/Ishratalib/Food-Ordering-System/blob/main/frontend-structure.txt)

## Features

- Restaurant and food browsing interfaces
- Component-based React architecture
- Backend API integration
- State management using Redux Toolkit
- Client-side navigation with React Router
- User authentication interface

## Backend Integration

The frontend communicates with the Django REST Framework backend.

**Backend URL:** https://ishratalib.pythonanywhere.com/

**Backend Repository:** [Backend-of-Food-ordering](https://github.com/Ishratalib/Backend-of-Food-ordering)

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Ishratalib/Food-Ordering-System.git
cd Food-Ordering-System
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the project root and add:

```env
VITE_API_BASE_URL=https://ishratalib.pythonanywhere.com
```

### 4. Run the Development Server

```bash
npm run dev
```

### 5. Build for Production

```bash
npm run build
```

## Deployment

- **Frontend:** Vercel
- **Backend:** PythonAnywhere

## Author

**Ishrat Talib**
