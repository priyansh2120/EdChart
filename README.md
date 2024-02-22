# EdChart - Social Media App

EdChart is a social media application built to connect users, share posts, and engage in meaningful conversations. This project is developed using React for the frontend and Node.js with Express for the backend.

## Features

- User authentication and authorization
- Posting and sharing updates
- Messaging feature for private conversations
- Dark mode support
- Responsive design for both desktop and mobile devices

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB database (you can use MongoDB Atlas or a local instance)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/priyansh2120/Edchart.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Edchart
   ```

3. Install dependencies for both the client and server:

   ```bash
   # Install client dependencies
   cd client
   npm install

   # Install server dependencies
   cd ../server
   npm install
   ```

4. Set up environment variables:

   Create a `.env` file in the `server` directory with the following content:

   ```env
   MONGO_URL=YOUR_MONGODB_CONNECTION_STRING
   PORT=YOUR_SERVER_PORT
   ```

   Replace `YOUR_MONGODB_CONNECTION_STRING` with your MongoDB connection string and `YOUR_SERVER_PORT` with the desired server port.

### Running the App

1. Start the server:

   ```bash
   # Inside the server directory
   node index.js
   ```

2. Start the client:

   ```bash
   # Inside the client directory
   npm start
   ```

   The app should now be running locally. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access EdChart.

## Contributing

Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md) when making pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or issues, please open a GitHub issue or contact the project maintainers:

- [Priyansh Kumar](https://github.com/priyansh2120)

