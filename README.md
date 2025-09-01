## Setup Instructions

### 1. Clone Repositories

Clone both client and server repositories:

```bash
# Clone 
https://github.com/Roshankiller123/Exam_Portal.git

---

### 2. Setup Server

```bash
cd Exam_Portal_Server
npm install
```

- Create a `.env` file inside `Exam_Portal_Server/`:

  ```env
  PORT=5000
  MONGO_URI=your_mongodb_connection_string
  ```

- Start the server:
  ```bash
  npm start
  ```
  Server should now run on `http://localhost:5000`.

---

### 3. Setup Client

```bash
cd Exam_Portal_Client
npm install
```

- Create a `.env` file inside `Quiz_App_Client/`:

  ```env
  VITE_API_URL=http://localhost:5000
  ```

- Start the client:
  ```bash
  npm run dev
  ```

Client should now run on `http://localhost:5173`.

---

