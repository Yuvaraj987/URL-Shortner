# URL-Shortner

A simple and efficient URL Shortener application. This project allows users to shorten long URLs, manage shortened links, and track usage statistics.

## Features

- Shorten long URLs with ease
- Redirect to original URLs using short codes
- Track usage statistics (clicks, creation date, etc.)
- RESTful API endpoints for integration
- Simple and intuitive interface

## Technologies Used

- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Frontend:** (Add details if applicable)
- **Other:** (List any additional libraries or frameworks)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14+ recommended)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Yuvaraj987/URL-Shortner.git
   cd URL-Shortner
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment variables:**  
   Create a `.env` file in the root directory and add the following:
   ```
   MONGODB_URI=your_mongodb_connection_string
   PORT=3000
   BASE_URL=http://localhost:3000
   ```

4. **Run the application:**
   ```bash
   npm start
   ```
   The server will be running at [http://localhost:3000](http://localhost:3000).

## API Endpoints

| Method | Endpoint           | Description             |
|--------|--------------------|-------------------------|
| POST   | /api/shorten       | Shorten a new URL       |
| GET    | /:shortCode        | Redirect to original URL|
| GET    | /api/stats/:code   | Get statistics for a code|

## Usage

1. Use the provided API to generate short URLs.
2. Share the short URL; clicking it will redirect to the original address.
3. Track stats for each short code via the API.

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License.

## Author

Developed by [Yuvaraj987](https://github.com/Yuvaraj987)

---
