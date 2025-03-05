# Note-Taking App Back-End

This is a Node.js back-end application that provides a RESTful API for managing notes. It uses MongoDB Atlas as Database.

## Technologies Used:

- **Node.js**
- **Express.js**
- **Mongoose** for MongoDB integration

### Features:

- Retrieve all notes.
- Create a new note.
- Update an existing note.
- Delete a note.

### Getting Started:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/PolyPasc/notes-server.git
   ```

2. **Install Dependencies**:

   ```bash
   cd server
   npm install
   ```

3. **Start the Server**:

   ```bash
   node index.js
   ```

4. **Access the API**:
   The API is available at `http://localhost:${PORT}`. `PORt` of your chioce in `.env`.

---

### Make sure these are in your `.env`

- MongoDB Atlas URL and MongoDB Database-name
- Add you secret for JWT
- Add Cors origin
