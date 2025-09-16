# 🎬 Movie Recommendation App

A simple web application that recommends movies based on user input.  
Frontend built with **React + Vite**, backend powered by **Appwrite.io** (Database + API).

---

## 🚀 Features
- Search for a movie and get similar recommendations  
- Clean and responsive UI  
- Uses **Appwrite Database** to store and fetch movie data  
- No authentication required — fast and simple access  

---

## 🛠️ Tech Stack
- **Frontend:** React, Vite, JavaScript, CSS  
- **Backend:** Appwrite.io (Database, API)  

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aadi-0411/Movie-Recommendation-App.git
   cd Movie-Recommendation-App


2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set environment variables**
   Create a `.env` file in the project root:

   ```bash
   VITE_APPWRITE_PROJECT_ID=your_project_id
   VITE_APPWRITE_DATABASE_ID=your_database_id
   VITE_APPWRITE_COLLECTION_ID=your_collection_id
   VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
   ```

4. **Run the app locally**

   ```bash
   npm run dev
   ```

   The app will be available at:

   ```
   http://localhost:5173/
   ```

---

## 📂 Project Structure

```
Movie-Recommendation-App/
│-- src/
│   │-- components/     # UI components
│   │-- pages/          # App pages
│   │-- services/       # Appwrite client setup
│   └-- App.jsx         # Main app
│-- public/             # Static assets
│-- .env                # Environment variables
│-- package.json        # Dependencies
│-- vite.config.js      # Vite config
│-- README.md           # Documentation
```

---

## 🌐 Deployment

* **Frontend:** Deploy easily on [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/)
* **Backend:** Hosted on [Appwrite Cloud](https://cloud.appwrite.io/)

  * Just update your `.env` file with the correct project and database IDs.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

---


