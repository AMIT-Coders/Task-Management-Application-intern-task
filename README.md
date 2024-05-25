
# Task Management Application

## Project Description

This project is a Task Management Application developed to demonstrate proficiency in full stack web development. The application allows users to create, read, update, and delete (CRUD) tasks. It features a frontend built with React.js, styled using Tailwind CSS, and a backend using Node.js and MongoDB. Additionally, the application handles API requests and implements server-side rendering with Next.js. Proper code documentation is provided.

## Features

1. **User Interface:**
   - User-friendly interface with HTML, CSS, and Tailwind CSS.
   - Responsive design.

2. **Task Management:**
   - Add new tasks.
   - View a list of all tasks.
   - Edit existing tasks.
   - Delete tasks.

3. **API Handling:**
   - API requests handled using vanilla JavaScript.
   - Fetch tasks from the backend and display on the frontend.
   - CRUD operations using POST, GET, PUT, and DELETE methods.

4. **Frontend:**
   - React.js for building frontend components.
   - Next.js for server-side rendering.

5. **Backend:**
   - Node.js server setup.
   - API endpoints for tasks.
   - MongoDB database to store tasks.

6. **Code Documentation:**
   - Clear documentation of the codebase.
   - Setup instructions and inline comments.

## Installation and Setup

### Prerequisites

- Node.js
- MongoDB
- Git

### Steps

1. **Clone the repository:**
```
   git clone https://github.com/AMIT-Coders/Task-Management-Application-intern-task
   cd Task-Management-Application-intern-task
```

2. **Install dependencies:**

```
  npm install
```

3. **Set up MongoDB:**
   - Ensure MongoDB is running on your local machine.
   - Create a `.env` file in the root directory and add the following:
```
    MONGODB_URI=mongodb://localhost:27017/taskmanagement
```

4. **Run the development server:**
```
npm run dev
```

5. **Open your browser and visit:**
```
http://localhost:3000
```

## Project Structure
```
task-management-app/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   └── (React components)
│   │
│   ├── pages/
│   │   ├── api/
│   │   │   └── tasks.js (API routes)
│   │   └── index.js (Next.js pages)
│   │
│   ├── styles/
│   │   └── globals.css
│   │
│   ├── utils/
│   │   └── (Utility functions)
│   │
│   └── app.js (Main application file)
│
├── .env
├── .gitignore
├── package.json
├── README.md
└── server.js (Node.js server setup)
```

## API Endpoints

- **GET /api/tasks**: Fetch all tasks.
- **POST /api/tasks**: Add a new task.
- **PUT /api/tasks/:id**: Update a task.
- **DELETE /api/tasks/:id**: Delete a task.

## Technologies Used

- **Frontend:**
  - HTML
  - CSS
  - Tailwind CSS
  - JavaScript (Vanilla)
  - React.js
  - Next.js

- **Backend:**
  - Node.js
  - MongoDB

## Evaluation Criteria

1. **Functionality:**
   - All CRUD operations performed correctly.
   - API handling implemented correctly.

2. **Code Quality:**
   - Well-organized and readable code.
   - Best practices followed.

3. **UI/UX:**
   - User-friendly and visually appealing interface.
   - Responsive design.

4. **Technical Skills:**
   - Proficiency in HTML, CSS, Tailwind CSS, and JavaScript.
   - Competence in React.js and Next.js.
   - Ability to set up and manage a Node.js server and MongoDB database.

5. **Documentation:**
   - Clear and comprehensive documentation.
   - Setup instructions easy to follow.

6. **Problem-Solving:**
   - Effective resolution of challenges encountered during development.

## Submission

- **GitHub Repository:**
  - Submit your project via this GitHub repository.
  - Include a `README.md` file with setup instructions and any other relevant documentation.

## Timeline

- You have **8 days** to complete this project.

## Contact

For any questions or clarifications, please contact Mohamed at mohamed.ibrahim@amitcoders.org

---

Good luck! We look forward to reviewing your submission and discussing your work in more detail.
