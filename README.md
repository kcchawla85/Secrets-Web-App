# Secrets Website - Anonymous Secret Sharing


https://github.com/kcchawla85/Secrets-Web-App/assets/73349039/4482a19d-d082-46c3-98e0-6207650172cc

## Overview

Secrets Website is a web application that allows users to authenticate themselves using Google OAuth 2.0 and share their secrets anonymously. The application is built using Node.js, Express, MongoDB, Passport, Mongoose, and EJS.

## Features

- Google OAuth 2.0 authentication to log in securely.
- Anonymous secret sharing - Users can share their secrets without revealing their identities.
- Securely stores secrets in a MongoDB database.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/Secrets-Web-App.git
cd Secrets-Web-App
```

2. Install the dependencies:

```bash
npm install
```

3. Create a `.env` file in the root directory and add your Google OAuth 2.0 credentials:

```
CLIENT_ID=your-google-client-id
CLIENT_SECRET=your-google-client-secret
```

4. Start the server:

```bash
npm start
```

5. Open your browser and navigate to `http://localhost:3000` to access the Secrets Website.

## Dependencies

The application relies on the following major dependencies:

- Node.js
- Express
- MongoDB
- Passport
- Mongoose
- EJS

## Folder Structure

The project structure is organized as follows:

```
secrets-website/
|-- config/
|   |-- passport-setup.js
|-- models/
|   |-- secret.js
|   |-- user.js
|-- public/
|   |-- css/
|   |   |-- styles.css
|   |-- js/
|   |   |-- script.js
|   |-- images/
|   |   |-- logo.png
|-- views/
|   |-- partials/
|   |   |-- header.ejs
|   |   |-- footer.ejs
|   |-- home.ejs
|   |-- login.ejs
|   |-- submit.ejs
|-- .env
|-- app.js
|-- package.json
|-- README.md
|-- server.js
```

## Usage

1. Visit the homepage of the Secrets Website.
2. Click on the "Login with Google" button to authenticate using your Google account.
3. Once logged in, you can share your secrets anonymously on the "Submit Secret" page.
4. View and enjoy reading secrets shared by other users on the homepage.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please create a pull request.

## License

This project is licensed under the [MIT License]

## Acknowledgments

- The project was inspired by the concept of anonymous secret-sharing websites.
- Thanks to the developers of Node.js, Express, MongoDB, Passport, Mongoose, and EJS for providing excellent tools for web development.

---

Thank you for using Secrets Website! We hope you enjoy sharing and reading secrets while maintaining anonymity. Happy secret-sharing!
