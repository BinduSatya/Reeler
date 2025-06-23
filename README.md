# Reeler Project

## Overview
Reeler is a Node.js application that utilizes Mongoose to connect to a MongoDB database. The application is designed to manage database connections efficiently by caching the connection to avoid multiple instances during its lifecycle.

## Features
- Establishes a connection to MongoDB using Mongoose.
- Caches the database connection for improved performance.
- Configurable through environment variables.

## Setup Instructions

### Prerequisites
- Node.js (version 14 or higher)
- MongoDB instance (local or cloud)

### Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd Reeler
   ```
3. Install the dependencies:
   ```
   npm install
   ```

### Configuration
1. Create a `.env.local` file in the root directory of the project.
2. Add your MongoDB connection string:
   ```
   MONGODB_URI=<your-mongodb-connection-string>
   ```

### Usage
To start the application, run:
```
npm start
```

## License
This project is licensed under the MIT License.