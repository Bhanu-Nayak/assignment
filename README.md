<a name="readme-top"></a>

<div align="center">
  <br/>

  <h3><b>PERN APP</b></h3>

</div>

<!-- PROJECT DESCRIPTION -->

# 📖 [PERN APP] <a name="about-project"></a>

**[Melody Verse]** is a full stack application, utilizing Node.js, Express.js, React.js, and PostgreSQL as the database. It includes features such as user signup with validation, JWT authentication, a paginated post list screen with infinite scroll, and responsive design using Tailwind CSS. The project aims to provide a visually appealing and consistent user experience under the MelodyVerse theme. Code submission includes API endpoints for user registration and post retrieval, along with JWT token generation and validation for user authentication

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://reactjs.org/">React.js</a></li>
    <li><a href="https://tailwindcss.com/">TailwindCss</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://expressjs.com/">Express.js</a></li>
    <li><a href="https://nodejs.org/en">Node.js</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **[User signup screen with validation, including optional fields and terms and conditions checkbox.]**
- **[Infinite scrolling post list screen with responsive design using Tailwind CSS.]**
- **[Secure API endpoints with input validation and protection against common attacks.]**
- **[Proper error handling and informative error messages.]**
- **[Secure JWT implementation for user authentication.]**
- **[Environment variable usage for sensitive information.]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Node.js and npm installed on your machine.
- A database server (MongoDB, PostgreSQL, MySQL, etc.) set up and running.

### Setup

Clone this repository :

```sh
  git clone https://github.com/Bhanu-Nayak/assignment
```

Install dependencies for the server:

```sh
  npm install

```

Install dependencies for the client:

```sh
  npm install
```

### Configuration

Set up your database connection:

- Create a .env file in the root directory.
- Add your database connection URI in the .env file:

```sh
DB_USER=your_username_here
DB_HOST=your_host_here
DB_DATABASE=your_database_name_here
DB_PASSWORD=your_password_here
DB_PORT=your_port_here

```

Set up JWT secret:

- Add a JWT secret in the .env file:

```sh
  JWT_SECRET=your_jwt_secret_here
```

To generate JWT key run bellow command on terminal :

```sh
  Node generateSecretKey.js
```

### Running the Application

To run the project, execute the following command:

Start the server:

```sh
  node server.js
```

Start the server:

```sh
  cd frontend
  npm start
```

Create a dummy User run:

```sh
  node setup.js
```

- It will create a dummy user with some random posts just go to login and click on demo

### Usage

Access the application at http://localhost:3001 in your web browser.
Sign up for a new account and start exploring!
