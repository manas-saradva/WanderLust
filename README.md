# WanderLust

WanderLust is a web application designed to connect travelers with exciting destinations and allow users to share their travel experiences. This project is built using Node.js, Express.js, MongoDB, and EJS for server-side rendering.

The live version of the website is available here: [WanderLust Live](https://wanderlust-7z85.onrender.com/listings).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Live Demo](#live-demo)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

WanderLust aims to simplify the travel experience by providing users with a platform to explore destinations, post listings, and connect with fellow travelers. Users can create, view, and interact with travel-related listings. This platform is optimized for both desktop and mobile users, ensuring a seamless experience.

## Features

- **User Authentication**: Secure login and registration functionality.
- **Listing Management**: Users can create, view, edit, and delete travel listings.
- **Image Uploads**: Integration with Cloudinary for managing media uploads.
- **Responsive Design**: Optimized for mobile and desktop users.
- **Interactive Map Integration**: Display listings with map-based visualization (if applicable).

## Live Demo

Experience WanderLust in action: [WanderLust Live](https://wanderlust-7z85.onrender.com/listings)

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/manas-saradva/WanderLust.git
   cd WanderLust
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     DATABASE_URL=your_database_url
     SESSION_SECRET=your_session_secret
     CLOUDINARY_CLOUD_NAME=your_cloud_name
     CLOUDINARY_API_KEY=your_api_key
     CLOUDINARY_API_SECRET=your_api_secret
     ```
   - Replace `your_database_url`, `your_session_secret`, `your_cloud_name`, `your_api_key`, and `your_api_secret` with your actual configuration details.

4. **Start the application**:
   ```bash
   npm start
   ```
   The application will run on `http://localhost:3000` by default.

## Usage

1. **Homepage**: Explore travel listings or search for specific destinations.
2. **User Accounts**: Register or log in to create and manage your listings.
3. **Create Listings**: Add a new travel destination with images and details.
4. **Edit/Delete Listings**: Manage your existing listings directly from your account dashboard.

## Project Structure

```
WanderLust/
├── controllers/
├── init/
├── models/
├── public/
│   ├── css/
│   ├── images/
│   └── js/
├── routes/
├── utils/
├── views/
│   ├── partials/
│   └── layouts/
├── .gitignore
├── app.js
├── cloudConfig.js
├── middleware.js
├── package-lock.json
├── package.json
└── schema.js
```

- `controllers/`: Contains the application logic for handling requests and responses.
- `init/`: Initialization scripts or configurations.
- `models/`: Database schemas and models.
- `public/`: Static assets like CSS, images, and JavaScript files.
- `routes/`: Application routes for handling user actions.
- `utils/`: Helper functions and utilities.
- `views/`: EJS templates for rendering HTML.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `app.js`: Main application file.
- `cloudConfig.js`: Configuration for cloud services like Cloudinary.
- `middleware.js`: Custom middleware functions.
- `package.json`: Project metadata and dependencies.
- `schema.js`: Database schema definitions.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

Please ensure your code follows the project's coding standards and includes appropriate tests.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this software in accordance with the license terms.
