# Creating a Portfolio Platform using Node.js
Authentication and Authorization



## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)
- [Key Design Decisions](#key-design-decisions)
- [Contributing](#contributing)


## Installation

1. **Clone the repository:**

    ```bash
    git clone <repository-url>
    ```

2. **Install dependencies:**

    ```bash
    cd final web back
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the root directory and add the necessary environment variables:

    ```plaintext
    PORT=3000
    MONGODB_URI=mongodb://localhost:27017/portfolio
    SESSION_SECRET=secret
    ```

4. **Start the server:**

    ```bash
    npm start
    ```

## Usage

To use the Portfolio Platform created using Node.js, i followed these steps:

Installation and Setup:

Clone the repository to  local machine.
Navigate to the project directory.
Install dependencies by running npm install.
Configure MongoDB:

Ensured MongoDB is installed and running.
Grant IP access to  MongoDB from any location.
Set up environment variables for MongoDB URI in  .env file.

User Registration:

Navigated to the registration page.
Provided required information such as username, password, first name, last name, age, country, and gender.
Submited the registration form.
User Login:

Once registered, navigate to the login page.
Entered username and password.
If credentials are correct, you will be redirected to the main page.
Admin Functionality:

Admins can access the admin page.
Add new items related to the portfolio, including pictures, names, descriptions, and timestamps.
Edit, delete, and add items as required.
Portfolio Display:

On the main page, well-designed blocks will display portfolio items.

API Integration:

Three different pages feature visually appealing charts or graphs created using data from different APIs.
Ensured interactivity and informative insights to enhance user engagement and understanding of the data.
Nodemailer Integration:

Upon registration, users will receive a welcome message via Nodemailer.
Notifications for certain actions on the website are also implemented.
Footer Information:
The footer includes my name and group number as per requirements.
Navigation Bar:
A functional navigation bar is implemented on all pages for seamless redirection and enhanced user experience.
Ensured to follow the instructions provided in the application for each functionality, and enjoy exploring the Portfolio Platform!







## API Reference
- **BitcoinAPI**:This api demonstrates how to fetch cryptocurrency prices from the CoinGecko API and visualize them using Chart.js.

- **RegisterAPI**:This api illustrates how to visualize user registration data using Chart.js library.

- **WeatherAPI**: This api shows information about user from OpenWeatherApi




## Key Design Decisions

1. Choice of Framework:
Express.js: Express.js was chosen as the web application framework due to its minimalistic and flexible nature. It provides a robust set of features for building web applications and APIs while allowing for scalability and customization.
2. Database:
MongoDB: MongoDB was chosen as the database management system due to its flexibility and scalability, particularly for applications with evolving data structures. The NoSQL nature of MongoDB allows for easy integration with JavaScript-based applications like Node.js.
3. Middleware:
Express Session: Express Session middleware was used for managing user sessions, allowing for user authentication and authorization across multiple requests.
Multer: Multer middleware was used for handling multipart/form-data, particularly for file uploads in the admin section.
Body-parser: Although not explicitly mentioned, Body-parser middleware is commonly used for parsing request bodies and was likely implicitly included through express.json() and express.urlencoded().
4. Templating Engine:
EJS (Embedded JavaScript): EJS was chosen as the templating engine for server-side rendering of views. EJS allows for embedding JavaScript code directly into HTML templates, making it easy to generate dynamic content.
5. Frontend:
Static File Serving: Express serves static files (e.g., CSS, JavaScript) from the public directory, separating the backend logic from the frontend assets.
6. Session Management:
Express Session with 'secret': The express-session middleware is used for session management, providing a secure way to handle user sessions. The 'secret' option is used for session cookie signing, enhancing security.
7. Error Handling:
Error Logging: Errors are logged to the console using console.error() with detailed messages to facilitate debugging and troubleshooting.
Error Responses: HTTP error responses (e.g., 500 Internal Server Error) are sent to clients in case of server-side errors.

## Contributing

Thank you for considering contributing to our project! Whether you're fixing a bug, implementing a new feature, or suggesting improvements, your contributions are highly valued.

To contribute to this project, please follow these guidelines: 

Open Github and search AdiletZhumabai 


