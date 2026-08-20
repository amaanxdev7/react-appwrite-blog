# Blogify

A full-stack blog application built with **React** (frontend) and **Appwrite** (backend-as-a-service) for authentication, database, and storage.

## ✨ Features

- User authentication (sign up, login, logout)
- Create, edit, and delete blog posts
- Rich text editor for writing posts
- Image upload and storage via Appwrite
- Responsive design

## 🛠️ Tech Stack

- **Frontend:** React, Vite
- **Backend:** Appwrite (Auth, Database, Storage)
- **Styling:** CSS / Tailwind (update based on what you are using)

## 🚀 Getting Started

### Prerequisites

- Node.js installed
- An Appwrite account/project set up

### Installation

1. Clone the repo
```bash
   git clone https://github.com/amaanxdev7/react-appwrite-blog.git
   cd react-appwrite-blog
```

2. Install dependencies
```bash
   npm install
```

3. Create a `.env` file in the root directory and add your Appwrite credentials
```env
   VITE_APPWRITE_URL=your_appwrite_endpoint
   VITE_APPWRITE_PROJECT_ID=your_project_id
   VITE_APPWRITE_DATABASE_ID=your_database_id
   VITE_APPWRITE_COLLECTION_ID=your_collection_id
   VITE_APPWRITE_BUCKET_ID=your_bucket_id
```

4. Run the development server
```bash
   npm run dev
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).