# 🔑 Last Lock Team 1 - Locked-In

## 📝 About

The **Locked-In Backend** serves as the core for processing and identifying room data efficiently. This project is aimed at creating a scalable and reliable backend architecture for handling room-related data. This service is optimized for room identification and processing, providing efficient data handling and API integration, eventually automating geospatial data with computer vision.

---

## ✨ Features

- 🌍 GeoJson Conversion
- 🏠 Room Identification
- 🗄️ Database Integration
- 🚀 Optimized Processes For Faster Execution

---

## 🛠️ Tech Stack

### 💻 Programming Language
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

### 🧩 Frameworks/Libraries
- ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
- ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
- ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

---

### 🗄️ Database
- ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

---

### ☁️ Other Tools
- ![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
- ![Uvicorn](https://img.shields.io/badge/Uvicorn-FF69B4?style=for-the-badge)

## 📦 Dependencies

This project relies on the following key dependencies:

| Dependency           | Purpose                                                   |
|-----------------------|-----------------------------------------------------------|
| **FastAPI**          | Framework for building APIs.                              |
| **Uvicorn**          | ASGI server for running FastAPI applications.             |
| **python-multipart** | For handling file uploads.                                |
| **PyMongo**          | MongoDB client for database operations.                   |
| **Cloudinary**       | Cloud-based image storage and management.                 |
| **python-dotenv**    | Environment variable management.                          |
| **OpenCV**           | Image processing and computer vision tasks.              |
| **NumPy**            | Numerical operations and array handling.                 |
| **scikit-image**     | Advanced image processing and manipulation.               |
| **PyTesseract**      | Optical character recognition (OCR) capabilities.         |
| **SciPy**            | Scientific computing and advanced numerical methods.      |

---

## ⚙️ Setup

Follow these steps to set up the project locally:

### Prerequisites
- Python 3.8 or later installed on your system
- Node.js and npm for the React frontend
- MongoDB instance (local or cloud)
- Cloudinary account for image management

---

### Backend Setup

1. **Navigate to Backend Directory**:
   ```bash
   cd backend
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # For MacOS/Linux
   env\Scripts\activate     # For Windows
   ```

3. **Install Backend Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**: 
   Create a `.env` file in the backend directory and add the following:
   ```bash
   MONGO_URI="your_mongodb_uri"
   CLOUDINARY_CLOUD_NAME="your_cloudinary_name"
   CLOUDINARY_API_KEY="your_cloudinary_key"
   CLOUDINARY_API_SECRET="your_cloudinary_secret_key"
   ```

5. **Run the Backend Server**:
   ```bash
   uvicorn main:app --reload
   ```
   The backend will be available at `http://127.0.0.1:8000`

### Frontend Setup

1. **Navigate to Frontend Directory**:
   ```bash
   cd frontend
   ```

2. **Install Frontend Dependencies**:
   ```bash
   npm install
   ```

3. **Start the Frontend Development Server**:
   ```bash
   npm start
   ```
   The frontend will be available at `http://localhost:3000`

---


## 👥 Contributors

| Name                   | Email                       |
|------------------------|-----------------------------|
| **Adelia Han**         | [han293@wisc.edu](mailto:han293@wisc.edu) |
| **Arian Abbaszadeh**   | [abbaszadeh@wisc.edu](mailto:abbaszadeh@wisc.edu) |
| **Asish Das**          | [das38@wisc.edu](mailto:das38@wisc.edu) |
| **Simarjit Singh Pannu** | [pannu2@wisc.edu](mailto:pannu2@wisc.edu) |
| **Tina Li**            | [tli442@wisc.edu](mailto:tli442@wisc.edu) |
