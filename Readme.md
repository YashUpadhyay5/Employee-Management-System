
# Employee Management System

A web-based Employee Management System built with React and Vite. This application allows administrators and employees to manage tasks, view dashboards, and handle authentication securely.

## Features
- User authentication (login)
- Admin and Employee dashboards
- Task management (create, accept, complete, fail tasks)
- Persistent login using local storage
- Responsive UI with Tailwind CSS

## Project Structure
```
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Auth/
│   │   ├── Dashboard/
│   │   ├── other/
│   │   └── TaskList/
│   ├── context/
│   ├── utils/
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
└── README.md
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm or yarn

### Installation
1. Clone the repository:
	```sh
	git clone <repository-url>
	cd Employee_Management_System-main
	```
2. Install dependencies:
	```sh
	npm install
	# or
	yarn install
	```

### Running the App
Start the development server:
```sh
npm run dev
# or
yarn dev
```
The app will be available at `http://localhost:5173` by default.

## Usage
- **Login:** Use your credentials to log in as an admin or employee.
- **Admin Dashboard:** Create and assign tasks, view all tasks and employees.
- **Employee Dashboard:** View assigned tasks, update task status.

## Technologies Used
- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

## Folder Details
- `src/components/Auth/`: Authentication components (e.g., Login)
- `src/components/Dashboard/`: Dashboards for admin and employees
- `src/components/TaskList/`: Task management components
- `src/context/`: Context providers (e.g., AuthProvider)
- `src/utils/`: Utility functions (e.g., localStorage helpers)

## License
This project is licensed under the MIT License.
