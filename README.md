# Simple Signup & Signin API 🚀

Hey! 👋 This is a small Node.js + Express project I made while learning backend stuff.  
It’s basically a super simple **signup** and **signin** API that stores users in memory (no database yet 😅).  

## 📌 What it does
- Lets you **signup** with a username and password
- Lets you **signin** with the same username and password
- If you login correctly, it gives you a random **token**
- All data is stored in memory (so it will reset when you restart the server)

## 🛠 How to run it
1. Make sure you have **Node.js** installed
2. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
3. Go into the project folder:
    - cd your-repo-name
4. Install the dependencies:
    - npm install express
5. Start the server:
    - node index.js
6. Open Postman, Thunder Client, or any API testing tool and try:
    - POST http://localhost:3000/signup
    - POST http://localhost:3000/signin