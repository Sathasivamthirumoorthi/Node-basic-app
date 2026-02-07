# Express Backend Application

A simple Node.js web server using Express.js - Perfect for beginners!

---

## ✅ Requirements

**Node.js - version 18 or below**

### Check if Node.js is Already Installed

Open your terminal and run:

```bash
node -v
npm -v
```

You should see version numbers.

### If Not Installed

Download Node.js from: https://nodejs.org/en/download

---

## 🚀 Quick Setup (3 Steps)

### Step 1: Install Dependencies

```bash
npm install
```

### Step 2: Start the Server

```bash
npm run dev
```

### Step 3: Open Your Browser

Go to: `http://localhost:3000`

You should see: **"Hello from Node.js + Express 🚀"**

---

## 📝 Your Server Code (index.js)

This is the main server file:

```javascript
const express = require("express");
const app = express();

const PORT = 3000;

// Middleware
app.use(express.json());

// Route
app.get("/", (req, res) => {
  res.send("Hello from Node.js + Express 🚀");
});

// Start server
app.listen(PORT, () => {
  console.log(`Server running on http://localhost:${PORT}`);
});
```

---

## 📚 Commands

| Command       | What It Does                                      |
| ------------- | ------------------------------------------------- |
| `npm run dev` | Start server (auto-restarts when you change code) |
| `npm start`   | Start server normally                             |
| `npm install` | Download required tools                           |

---

## 🎯 What Happens?

1. You run `npm run dev`
2. Server starts on port 3000
3. When you visit `http://localhost:3000`, the server responds with a message
4. That's it! You have a working web server! 🎉

---

Happy coding! 🚀
