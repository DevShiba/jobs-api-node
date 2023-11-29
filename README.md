
# Jobs API

This API aims to enable the creation of job entries for situations where you've been rejected, are in an interview process, or the application status is pending. However, to use this feature, you'll need to create an account. If you already have an account, simply log in. By doing so, you'll notice that you can perform CRUD operations as outlined in this documentation. This includes creating, updating, deleting, and viewing one or multiple job entries that have been created.

For this project, I utilized the following technologies and libraries:

- bcryptjs: Helps encrypt passwords using the bcrypt hash algorithm for secure password storage.

- cors: Allows configuring Cross-Origin Resource Sharing policies in web applications for sharing resources across different origins.

- express: A Node.js web framework that simplifies API and web application development by managing routes, middlewares, and other functionalities.


- helmet: Enhances Express application security by setting various HTTP headers, providing protection against known vulnerabilities.

- joi: A data validation library for JavaScript that streamlines input data validation, such as HTTP requests.

- jsonwebtoken: Enables the generation and verification of JSON Web Tokens (JWT) for authentication and authorization in web applications.

- mongoose: An object modeling library for MongoDB in Node.js that simplifies interactions with MongoDB databases.

- swagger-ui-express: Creates an interactive web interface for API documentation using the OpenAPI (formerly Swagger) standard in Express applications.

- yamljs: Converts YAML files into JavaScript objects and vice versa, allowing manipulation of YAML-formatted data in Node.js applications."
## Swagger

![Doc](https://i.imgur.com/pRsXjE7.png)

Link: https://jobs-api-yp9p.onrender.com/api-docs/

## Running Locally

Clone the project

```bash
  git clone https://github.com/DevShiba/jobs-api-node
```

Navigate to the project directory

```bash
  cd jobs-api-node
```

Install the dependencies

```bash
  npm install
```

Start the server

```bash
  npm start
```

