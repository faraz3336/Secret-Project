# 🔐 Secret App - API Edition

This is a fun backend project built while following [Angela Yu's Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/). The goal of this project is to understand how **APIs** work and how to make **server-side API requests** using **Axios** in a Node.js + Express.js app.

---

## 📌 Features

- 🔁 Fetches random secrets from [App Brewery's Secret API](https://secrets-api.appbrewery.com/)
- 💬 Displays a random secret when you hover over an image
- 🧑 Shows the user who submitted the secret
- 📄 Uses EJS templating and Express for rendering and routing
- 🔐 Demonstrates API key-based authentication

---

## 🛠️ Technologies Used

- Node.js
- Express.js
- Axios
- EJS
- CSS

---

## 📚 What I Learned

- How REST APIs work
- Using Axios to make API requests from the backend
- Working with JSON responses
- API authentication using headers
- Rendering dynamic data with EJS
- Handling routes in Express

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/faraz3336/Secret-Project.git
cd Secret-Project
```
## 2. Install dependencies
```bash
npm install
```
## 3. Add .env file
Create a .env file in the root directory and add your API key like this:
```bash
API_KEY=your_appbrewery_api_key_here
```
##4. Run the app
```bash
node app.js
```
Open your browser and visit: http://localhost:3000
## 📂 Project Structure
```bash
Secret-Project/
├── public/
│   └── styles.css
├── views/
│   └── home.ejs
├── .env
├── app.js
└── package.json
```
📸 Preview
## Demo

![Demo Screenshot](./Secret-Project.png)  
*(Replace with your actual screenshot if available)*

💡 Inspiration
This project was inspired by the App Brewery’s teaching style — learning by building real, hands-on apps. This one really helped me grasp how to interact with external APIs from the server side.

🔗 Live Demo (Optional)
Add a live hosted link here if deployed

🧠 Author
Faraz Bin Tariq
Full Stack Web Developer | AI Enthusiast
LinkedIn • GitHub

📜 License
This project is licensed under the MIT License.
