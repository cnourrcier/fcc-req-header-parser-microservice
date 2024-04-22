# Request Header Parser Microservice

## Description

This project is a Node.js web application designed to provide information about the user's IP address, preferred language, and browser software. It exposes a simple API endpoint `/api/whoami` which returns JSON data containing this information.

## Installation

1. Clone the repository to your local machine.
2. Install dependencies by running `npm install`.
3. Optional: Create a `.env` file in the root directory and add a `PORT` environment variable.
4. Start the server by running `node index.js` or `npm start`.

## Usage

After starting the server, you can access the application through a web browser or make requests to the `/api/whoami` endpoint using tools like Thunder Client or Hoppscotch.io.

## Endpoints

- `/api/whoami`: Returns JSON data containing the user's IP address, preferred language, and browser software.

## Credits

This project is part of the Back End Development and APIs Certification from [freeCodeCamp](https://www.freecodecamp.org/).

## Dependencies

- `dotenv`: Loads environment variables from a `.env` file into `process.env`.
- `express`: Web framework for Node.js.
- `cors`: Middleware for enabling Cross-Origin Resource Sharing (CORS).

## Configuration

- `PORT`: Port number on which the server will listen. Defaults to `3000` if not specified.

## License

This project is licensed under the [BSD 3-Clause License](LICENSE).
