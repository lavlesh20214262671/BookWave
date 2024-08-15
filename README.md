
# BookWave

A full-stack book management application with separate frontend and backend components.

Created by **Lavlesh Kumar Bais**.

## Project Structure

```bash
BookWave/
│
├── Backend/                 # Express.js backend
│   ├── controller/          # Controllers for books and users
│   ├── model/               # Models for books and users
│   ├── route/               # Routes for book API
│   ├── .env                 # Environment variables
│   ├── index.js             # Entry point for the backend server
│   └── package.json         # Backend dependencies
│
├── Frontend/                # React.js frontend
│   ├── public/              # Public assets (images, etc.)
│   ├── src/                 # Frontend source files
│   │   ├── components/      # Reusable components
│   │   ├── courses/         # Course-related components
│   │   ├── context/         # Context for auth providers
│   │   ├── App.jsx          # Main App component
│   │   ├── main.jsx         # Main entry point for React
│   ├── index.html           # Main HTML file
│   └── package.json         # Frontend dependencies
```

## Frontend

### Built With

- React.js
- Tailwind CSS
- Vite

### Installation

1. Navigate to the frontend directory:

   ```bash
   cd Frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Access the application at `http://localhost:4001`.

## Backend

### Built With

- Node.js
- Express.js
- MongoDB

### Installation

1. Navigate to the backend directory:

   ```bash
   cd Backend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file with the following content:

   ```bash
   MONGODB_URI=local_mongo_db_connection_string
   PORT=5173
   ```

4. Start the backend server:

   ```bash
   npm start
   ```

5. The server will run at `http://localhost:5173`.

## API Endpoints

### Books

- `GET /books`: Get a list of all books
- `POST /books`: Add a new book
- `PUT /books/:id`: Update a book by ID
- `DELETE /books/:id`: Delete a book by ID

### Users

- `POST /users/login`: User login
- `POST /users/register`: User registration

## License

This project is licensed under the MIT License.

