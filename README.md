# Arkiv - A File Library System

A full-stack web application for managing, storing, and accessing a collection of PDF files. This project includes user authentication, a file explorer, and search functionality.

## Features

- **User Authentication** (Register/Login)
- **File Explorer** (View and navigate stored files)
- **Search Functionality** (Find files quickly)
- **PDF Preview** (Preview files without downloading)
- **Secure API** with authentication middleware

## Tech Stack

### Backend
- **Node.js** + **Express**
- **SQLite** (or any database for user authentication & file metadata)
- **JWT** for authentication
- **Multer** for file handling

### Frontend
- **React.js**
- **Redux** for state management
- **React Router** for navigation

## Project Structure

```
file-library-main/
│── backend/ 
│ ├── data/         # PDF files & resources 
│ ├── middleware/   # Authentication middleware 
│ ├── routes/       # API endpoints (auth & files) 
│ ├── server.js     # Main server entry point 
│── frontend/ 
│ ├── src/ 
│ │ ├── components/ # React components (UI) 
│ │ ├── redux/      # State management with Redux 
│ │ ├── utils/      # Utility functions (API calls) 
│── README.md       # Project documentation 
```

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/tonyliuzj/arkiv.git
```
```sh
cd arkiv
```
### 2. Backend Setup

```sh
cd backend
```
```sh
npm install
```
```sh
npm start
```
### 3. Frontend Setup

```sh
cd ../frontend
```
```sh
npm install
```
```sh
npm start
```

## API Endpoints

| Method | Endpoint           | Description             |
|--------|-------------------|-------------------------|
| POST   | /api/auth/register | Register a new user     |
| POST   | /api/auth/login    | User login              |
| GET    | /api/files         | Fetch all files         |
| GET    | /api/files/:id     | Get a specific file     |

## Future Enhancements

- Drag & Drop File Uploads
- User Role Management
- Dark Mode Support
- More File Formats (Images, Docs, etc.)

## License
This project is open-source under the MIT License.

## Acknowledgments
ChatGPT 4-o for Frontend and CSS