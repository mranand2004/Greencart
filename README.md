# 🚀 AI-Powered Resume Builder (MERN Stack)


AI-Powered Resume Builder is a full-stack web application that enables users to create, customize, preview, and manage professional resumes using modern templates and AI-assisted content generation.  
The project is built using the **MERN stack**, focusing on scalability, security, and an intuitive user experience.

---

## 🚀 Features

- User authentication and authorization (JWT-based)
- Create, edit, and manage multiple resumes
- AI-generated professional summaries and content
- Live resume preview while editing
- Multiple modern resume templates
- Custom color and layout selection
- Profile image upload support
- Secure backend APIs
- Responsive UI for all devices

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Redux Toolkit
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

### Other Tools & Services
- OpenAI / AI API (Resume content generation)
- ImageKit (Image storage)
- Multer (File uploads)
- Git & GitHub

---

## 📂 Project Structure

<img width="1870" height="8192" alt="Decision Options Flow Model" src="https://github.com/user-attachments/assets/7e39c1d7-a20b-4975-ae06-ed6b39c85b15" />

---

## 🔐 Environment Variables

For security reasons, `.env` files are **not included** in the repository.

Create a `.env` file inside the **server** folder and add the following:


<img width="1870" height="8192" alt="Project Structure Diagram" src="https://github.com/user-attachments/assets/7e39c1d7-a20b-4975-ae06-ed6b39c85b15" />



```env
# Server Configuration
PORT=5000
NODE_ENV=development

# MongoDB Configuration
MONGO_URI=your_mongodb_connection_string

# JWT Authentication
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRE=7d

# AI Configuration
AI_API_KEY=your_ai_api_key

# ImageKit Configuration
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
