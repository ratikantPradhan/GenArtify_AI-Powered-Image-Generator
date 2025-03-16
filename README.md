# AI Powered Image Generator

## Project Abstract
The **AI Powered Image Generator** aims to automate the creative process by transforming user-provided text into visually appealing images using AI-powered algorithms. Designed as a web application, the project enhances user experience through a responsive interface, secure backend, and seamless payment integration, making it an ideal solution for designers, marketers, and content creators.  

## Technologies Used
The application is built using the **MERN stack**:
- **Frontend**: React.js and Tailwind CSS for responsive design.
- **Backend**: Node.js and Express.js for API development.
- **Database**: MongoDB for secure and efficient data storage.
- **Payment Gateway**: Razorpay for managing premium feature payments.
- **Development Tools**: Visual Studio Code, GitHub, Postman, and W3C Validators.

## Features and Modules
- **Authentication Module**: Secure user registration, login, and password recovery.
- **Text Input Module**: Accepts user text for image generation.
- **Image Generation Module**: Converts text into high-quality images using AI.
- **Payment Module**: Handles premium features via Razorpay.
- **Dashboard Module**: Displays user-generated image history and settings.
- **Admin Panel**: Enables user and transaction management with analytics tools.

## Development Process
The project follows a structured workflow:
1. Setting up the MERN stack environment.
2. Designing the user interface with Tailwind CSS.
3. Implementing backend APIs and MongoDB integration.
4. Configuring Razorpay for payment functionality.
5. Integrating AI APIs for text-to-image conversion.
6. Developing a user-friendly dashboard for history and customization.
7. Conducting rigorous testing and deploying the application.

## Advantages
- Provides customizable templates for personalized visuals.
- Cost-effective alternative to professional design services.
- Automates image creation, saving time and effort.
- Premium features for pro plans.
- Accessible for non-designers to create professional images.
- Accelerates workflows for marketers and content creators.

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- MongoDB (v4.4 or higher)
- npm (v6 or higher)
- Git

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/ratikantPradhan/GenArtify_AI-Powered-Image-Generator
```

### 2. Backend Setup

```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create environment file
cp .env.example .env

# Start development server
npm run dev
```

### 3. Frontend Setup
```bash
# Navigate to client directory
cd client

# Install dependencies
npm install

# Start development server
npm run dev
```

## Environment Variables Setup

### Backend (.env file)
Create a `.env` file in the `backend` directory with the following structure:

```env
MONGODB_URI = " "

JWT_SECRET = " "

CLIPDROP_API = " "

RAZORPAY_KEY_ID = " "

RAZORPAY_KEY_SECRET = " "

CURRENCY = " "
```
### frontend (.env file)
Create a `.env` file in the `client` directory with the following structure:

```env
VITE_BACKEND_URL = " "

VITE_RAZORPAY_KEY_ID = " "

# 5267 3181 8797 5449
```

## Development

### Backend Development Server
```bash
cd backend
npm run dev
```

### Frontend Development Server
```bash
cd client
npm run dev
```


## Conclusion
This project leverages cutting-edge technology to address the needs of modern content creators. The **AI Powered Image Generator** provides a scalable, responsive, and secure platform for generating custom visuals, streamlining the creative process, and offering advanced tools to users.  

## Contact

For any queries or collaborations, feel free to reach out to us:

- **Sambit Kumar Sahoo** - [GitHub](https://github.com/your-github) | [LinkedIn](https://linkedin.com/in/your-linkedin)
- **Ratikanta Pradhan** - [GitHub](https://github.com/ratikantaPradhan) | [LinkedIn](https://linkedin.com/in/your-linkedin)
- **Sunami SwayamPrava Mohanty** - [GitHub](https://github.com/your-github) | [LinkedIn](https://linkedin.com/in/your-linkedin)
- **Atul Anshuman Sahoo** - [GitHub](https://github.com/your-github) | [LinkedIn](https://linkedin.com/in/your-linkedin)
- **Dharmaraj Pradhan** - [GitHub](https://github.com/your-github) | [LinkedIn](https://linkedin.com/in/your-linkedin)
