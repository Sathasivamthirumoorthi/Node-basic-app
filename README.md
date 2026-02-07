# Express Backend Application

A simple Node.js web server project that helps you learn how to build a backend using Express.js.

## What Does This Project Do?

This is a beginner-friendly project that shows you how to:

- Start a web server
- Handle web requests
- Send responses to visitors

Think of it like a simple restaurant - when someone visits, you respond with a welcome message!

## Project Structure

Here's what each file does:

```
express-backend/
├── index.js           # The main file - your server code goes here
├── package.json       # A file that lists what your project needs to work
├── node_modules/      # Folder with downloaded tools (created automatically)
└── README.md          # This instruction file
```

## Getting Started - Step by Step

### Step 1: Check if Node.js is Installed

Before you start, make sure you have Node.js installed on your computer.

**What is Node.js?**
Node.js lets you write server code in JavaScript.

**Check if it's installed:**
Open your terminal/command prompt and type:

```bash
node --version
npm --version
```

You should see version numbers. If you don't, download Node.js from: https://nodejs.org/

### Step 2: Download the Project Files

Go to the project folder in your terminal:

```bash
cd express-backend
```

### Step 3: Install Required Tools

Run this command to download and install everything your project needs:

```bash
npm install
```

This downloads two important tools:

- **express** - Helps you create a web server
- **nodemon** - Automatically restarts your server when you make changes

### Step 4: Start Your Server

Choose one of these commands:

**For learning and testing (recommended):**

```bash
npm run dev
```

This will restart automatically when you change your code - great for learning!

**For regular use:**

```bash
npm start
```

## Your First Server

Once you run the server, you should see a message like:

```
Server running on http://localhost:3000
```

This means your server is working!

### What is "localhost:3000"?

- **localhost** = Your own computer
- **3000** = A "door" (port) that your server listens on

### Test Your Server

Open your web browser and go to:

```
http://localhost:3000
```

You should see: **"Hello from Node.js + Express 🚀"**

Congratulations! You just made your first web server! 🎉

## What Each Tool Does

| Tool        | What It Does                                            |
| ----------- | ------------------------------------------------------- |
| **express** | Helps you build a web server                            |
| **nodemon** | Watches your code and restarts the server automatically |
| **npm**     | Tool to download and manage tools                       |

## Quick Commands Reference

| Command                    | What It Does                            |
| -------------------------- | --------------------------------------- |
| `npm run dev`              | Start server (restarts on code changes) |
| `npm start`                | Start server normally                   |
| `npm install package-name` | Download a new tool                     |

## What's Next? (Learning Ideas)

Once this works, try these:

1. Add a new page route (like `/about`)
2. Send different messages to different pages
3. Try changing the welcome message
4. Add more complex features

## Troubleshooting

**Server won't start?**

- Make sure Node.js is installed
- Make sure you're in the correct folder
- Try: `npm install` again

**Getting error messages?**

- Read the error carefully
- Check you typed the command correctly
- Search online for the error message

## Learning Tips for Beginners

✅ Play around with the code - don't be afraid to break it and fix it!
✅ Change the message and see what happens
✅ Read the `index.js` file to understand how it works
✅ Write comments in your code to explain what it does

## Need Help?

- Read the error messages carefully
- Check the official Express.js guide: https://expressjs.com/
- Ask your instructor or classmates

---

Happy coding! Keep learning and building! 🚀
