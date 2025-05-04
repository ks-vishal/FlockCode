# FlockCode

A real-time collaborative code editor that allows multiple users to edit code simultaneously with live updates. Built with Node.js, Socket.io, and React.

![Demo Screenshot](https://via.placeholder.com/800x400?text=Real-Time+Code+Editor+Demo) 
*Replace with actual screenshot*

## ✨ Features

- **Real-time collaboration** - Multiple users can edit simultaneously
- **Language support** - Syntax highlighting for popular programming languages
- **Cursor sharing** - See other participants' cursor positions
- **Room system** - Create persistent editing sessions
- **Live preview** - Instant updates as you type

## 🚀 Quick Start

### Prerequisites
- Node.js (v14+)
- npm (v6+) or yarn
- MongoDB (for data persistence)

### Installation
```bash
# Clone the repository
git clone https://github.com/ks-vishal/Real_Time_code_Editor.git
cd Real_Time_code_Editor

# Install dependencies
npm install

# Set up environment
echo "PORT=3001" > .env
echo "MONGO_URI=mongodb://localhost:27017/code-editor" >> .env

# Start the application
npm run dev
```
### Running the App
```bash
# Frontend (React)
npm start

# Backend (Node.js) - in separate terminal
cd server && npm start
```
## Access
Visit [http://localhost:3808](http://localhost:3808) in your browser.

## 🔧 Configuration

### Environment Variables
| Variable     | Description               | Default Value                |
|--------------|---------------------------|------------------------------|
| PORT         | Backend server port       | 3001                         |
| MONGO_URI    | MongoDB connection string | `mongodb://localhost:27017/code-editor` |

### Project Structure
```text
Real_Time_code_Editor/
├── client/               # React frontend application
│   ├── public/           # Static assets
│   ├── src/              # React source code
│   │   ├── components/   # Reusable UI components
│   │   ├── pages/        # Application pages
│   │   ├── styles/       # CSS/Styling files
│   │   └── App.js        # Main application component
│   └── package.json      # Frontend dependencies
│
├── server/               # Node.js backend server
│   ├── controllers/      # Business logic
│   ├── models/           # Database models
│   ├── routes/           # API routes
│   ├── utils/            # Utility functions
│   ├── app.js            # Express application setup
│   └── package.json      # Backend dependencies
│
├── .env                  # Environment variables
├── .gitignore            # Git ignore rules
├── package.json          # Root project configuration
└── README.md             # Project documentation
```
## 🤝 Contributing
- Fork the project

- Create your feature branch (git checkout -b feature/AmazingFeature)

- Commit your changes (git commit -m 'Add some AmazingFeature')

- Push to the branch (git push origin feature/AmazingFeature)

- Open a Pull Request

## 📜 License
Distributed under the MIT License. See LICENSE for more information.
