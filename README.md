# Prescripto

Prescripto is a healthcare management platform that connects users with trusted doctors for appointments and consultations. The platform provides a seamless experience for booking appointments, accessing medical information, and managing healthcare needs.

## Features

- Browse and book appointments with trusted doctors
- View doctor profiles and specialties
- Manage user profiles and appointments
- Responsive design for both desktop and mobile devices

## Project Structure

The project is divided into two main parts: `frontend` and `backend`.

### Frontend

The frontend is built using React and Vite. It includes components for displaying doctor information, booking appointments, and managing user profiles.

### Backend

The backend is built using Express.js and MongoDB. It provides APIs for managing doctor and appointment data.

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- MongoDB

### Installation

1. Clone the repository:

```sh
git clone https://github.com/yourusername/prescripto.git
cd prescripto

Install dependencies for both frontend and backend:
cd frontend
npm install
cd ../backend
npm install

Create a .env file in the backend directory with the following content:
MONGODB_URI='mongodb://<username>:<password>@<hostname>/'
PORT=4000

Running the Project
Start the backend server:
cd backend
npm run server

Start the frontend development server:
cd frontend
npm run dev
