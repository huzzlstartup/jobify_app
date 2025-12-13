# Jobify App 🚀

![Jobify App](https://img.shields.io/badge/Jobify_App-MERN_Full--Stack-blue)

Welcome to **Jobify App**, a job tracking application built using the MERN stack. This full-stack web application helps users manage their job applications efficiently, offering a seamless experience from application to hiring. 

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User Authentication**: Secure login and registration using JWT.
- **Job Tracking**: Add, edit, and delete job applications.
- **File Upload**: Upload resumes and cover letters using Cloudinary.
- **Responsive Design**: Works on all devices with a clean UI.
- **Date Management**: Track application dates with Day.js.

## Technologies Used

This project uses a variety of technologies to deliver a robust application. Key technologies include:

- **MERN Stack**: MongoDB, Express.js, React, Node.js
- **Bcryptjs**: For password hashing
- **Cloudinary**: For media storage
- **Cookie-Logger**: For cookie management
- **Day.js**: For date handling
- **Jsonwebtoken**: For user authentication
- **Mongoose**: For MongoDB object modeling
- **Multer**: For file uploads
- **Styled-components**: For styling React components
- **Vite-template**: For a fast development environment

## Getting Started

To get started with Jobify App, clone the repository and install the dependencies.

1. Clone the repository:

   ```bash
   git clone https://github.com/huzzlstartup/jobify_app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd jobify_app
   ```

3. Install dependencies for both client and server:

   ```bash
   npm install
   cd client
   npm install
   ```

4. Set up environment variables. Create a `.env` file in the root directory and add your configurations.

5. Start the application:

   ```bash
   npm run dev
   ```

## Usage

After starting the application, you can access it in your browser at `http://localhost:3000`. Here, you can create an account, log in, and start tracking your job applications.

## API Endpoints

### User Authentication

- **POST** `/api/auth/register`: Register a new user.
- **POST** `/api/auth/login`: Log in an existing user.

### Job Management

- **GET** `/api/jobs`: Get all job applications.
- **POST** `/api/jobs`: Add a new job application.
- **PUT** `/api/jobs/:id`: Update a job application.
- **DELETE** `/api/jobs/:id`: Delete a job application.

## Contributing

We welcome contributions! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, feel free to reach out to us. You can also check the [Releases](https://github.com/huzzlstartup/jobify_app/releases) section for updates.

---

Explore the [Releases](https://github.com/huzzlstartup/jobify_app/releases) for the latest version of Jobify App. Download and execute the latest files to get the most out of your job tracking experience! 

Happy job hunting! 🌟