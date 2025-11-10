<div align="center">
  <h1>📝 Modern To-Do List Application</h1>
  
  [![Node.js Version](https://img.shields.io/badge/node-%3E%3D14.0.0-brightgreen)](https://nodejs.org/)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
  [![GitHub stars](https://img.shields.io/github/stars/yourusername/To-Do-List-Application?style=social)](https://github.com/yourusername/To-Do-List-Application/stargazers)
  
  A feature-rich, responsive To-Do List application built with Node.js, Express, and MongoDB. The application includes priority levels, categories, due dates, and filtering capabilities.
  
  [![Demo](https://img.shields.io/badge/🚀-Live_Demo-2ea44f?style=for-the-badge)](https://your-demo-url.vercel.app)
  [![Documentation](https://img.shields.io/badge/📚-Documentation-blue?style=for-the-badge)](#documentation)
  [![Report Bug](https://img.shields.io/badge/🐞-Report_Bug-red?style=for-the-badge)](#reporting-issues)
  [![Request Feature](https://img.shields.io/badge/💡-Request_Feature-ff69b4?style=for-the-badge)](#requesting-features)
</div>

## 🚀 Features

- **Task Management**: Add, edit, delete, and mark tasks as complete
- **Priority Levels**: Set tasks as High, Medium, or Low priority
- **Categories**: Organize tasks by custom categories
- **Due Dates**: Set and track task deadlines
- **Filtering**: Filter tasks by status (All/Active/Completed) and category
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Updates**: Changes are reflected immediately
- **Fallback Storage**: Automatically falls back to in-memory storage if MongoDB is not available

## 🛠️ Tech Stack

### Frontend
- **EJS** - Templating engine
- **CSS3** - Styling
- **Font Awesome** - Icons

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **MongoDB** - Database (with in-memory fallback)
- **Mongoose** - ODM for MongoDB

### Development Tools
- **Nodemon** - Development server
- **dotenv** - Environment management
- **npm** - Package manager

## 🚀 Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
- MongoDB (optional, for persistent storage)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd To-Do-List-Application
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory with the following content:
   ```
   MONGODB_URI=mongodb://localhost:27017/todolist
   PORT=3000
   NODE_ENV=development
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## ⚙️ Configuration

### Environment Variables

- `PORT`: The port on which the application will run (default: 3000)
- `MONGODB_URI`: MongoDB connection string (default: in-memory storage)
- `NODE_ENV`: Application environment (development/production)

## 📦 Dependencies

- **Express.js**: Web application framework
- **Mongoose**: MongoDB object modeling
- **EJS**: Templating engine
- **dotenv**: Environment variable management
- **body-parser**: Parse incoming request bodies
- **uuid**: Generate unique IDs for tasks

## 📱 Usage

1. **Adding a Task**
   - Enter task description in the input field
   - Set priority (Low/Medium/High)
   - Add an optional category and due date
   - Click "Add Task" or press Enter

2. **Managing Tasks**
   - Click the circle to mark as complete/incomplete
   - Click the edit icon to modify a task
   - Click the trash icon to delete a task

3. **Filtering**
   - Use the status filter to show All/Active/Completed tasks
   - Filter by category using the category dropdown

## 📄 License

MIT

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Reporting Issues

If you find a bug or have a feature request, please open an issue on GitHub.

## 🙏 Acknowledgments

- [Node.js](https://nodejs.org/) - JavaScript runtime
- [Express](https://expressjs.com/) - Web framework
- [MongoDB](https://www.mongodb.com/) - Database
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling
- [Font Awesome](https://fontawesome.com/) - Icons
- [Shields.io](https://shields.io/) - Badges

## 📊 Project Status

[![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/To-Do-List-Application)](https://github.com/yourusername/To-Do-List-Application/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/To-Do-List-Application)](https://github.com/yourusername/To-Do-List-Application/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/yourusername/To-Do-List-Application)](https://github.com/yourusername/To-Do-List-Application/pulls)

## 🌟 Show Your Support

Give a ⭐️ if this project helped you!

## 👩‍💻 Author

<div align="center">
  <img src="https://img.shields.io/badge/Author-Manideepika-4B0082?style=for-the-badge&logo=github" alt="Author">
  <br><br>
  <a href="https://github.com/manideepika31" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/mani-deepika-kesanakurthi-0764ba347/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:manideepika@example.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</div>

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.
#
