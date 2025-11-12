🧾 TaskManager

TaskManager is a full-stack web application designed to help users efficiently manage their daily tasks and boost productivity. It allows users to create, organize, track, and prioritize tasks through an intuitive interface with secure authentication and persistent data storage.

---

🚀 Features

- ✅ **User Authentication** – Secure registration and login using JWT.
- 🗂️ **Task Management** – Create, read, update, and delete tasks easily.
- ⏰ **Status Tracking** – Mark tasks as pending, in progress, or completed.
- 🔍 **Filter & Search** – Quickly find tasks using filters and search queries.
- 📅 **Due Date Management** – Set and view task deadlines.
- 🧠 **User-Friendly UI** – Clean and responsive front-end built with modern web technologies.
- 💾 **Database Integration** – Persistent data storage using MongoDB.

---

🏗️ Tech Stack

**Frontend**
- HTML5, CSS3, JavaScript (ES6+)
- React.js (or plain JS if used)
- Bootstrap / Tailwind CSS for styling

**Backend**
- Node.js with Express.js
- RESTful API architecture
- JWT for authentication and authorization

**Database**
- MongoDB Atlas (Cloud Database)
- Mongoose ORM for schema management

---

⚙️ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/PavanDeep76/TaskManager.git
cd TaskManager
2️⃣ Install Dependencies
Backend
cd server
npm install
Frontend
cd client
npm install
3️⃣ Environment Configuration
Create a .env file inside the server folder and add the following:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
4️⃣ Run the Application
Backend
cd server
npm start

Frontend
cd client
npm start

The application will run on:

Frontend → http://localhost:3000

Backend → http://localhost:5000

🧩 Folder Structure
bash
Copy code
TaskManager/
│
├── client/               # Frontend code
│   ├── public/
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── pages/        # Page-level components
│   │   ├── services/     # API calls
│   │   └── App.js
│   └── package.json
│
├── server/               # Backend code
│   ├── config/           # Database connection & config files
│   ├── controllers/      # Route handlers
│   ├── middleware/       # Auth middleware
│   ├── models/           # Mongoose schemas
│   ├── routes/           # API endpoints
│   ├── .env
│   └── server.js
│
└── README.md
🧠 API Endpoints
Authentication
Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Login user & generate token

Tasks
Method	Endpoint	Description
GET	/api/tasks	Get all tasks
POST	/api/tasks	Create new task
PUT	/api/tasks/:id	Update task details
DELETE	/api/tasks/:id	Delete a task

🧾 Example .env File
env
Copy code
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/TaskManager
JWT_SECRET=mySecretKey
💡 Future Enhancements
📊 Add task analytics dashboard

📱 Implement mobile-friendly Progressive Web App (PWA) features

🧑‍🤝‍🧑 Team collaboration and shared workspaces

🔔 Email or SMS reminders for due tasks

👨‍💻 Developed By
Pavan Deep Pedamarla
📧 pavandeep707@gmail.com
🔗 www.linkedin.com/in/pavan-deep-pedamarla-756692273
💻 https://github.com/PavanDeep76

🪪 License
This project is licensed under the MIT License.
Feel free to use and modify it for personal or educational purposes.
