# Library Management System

A full-stack web application for managing library operations, built with Flask and MongoDB Atlas.

## Features

- **Dashboard** — Live counts of books, borrowers, and issued books
- **Book Management** — Add, view, update, and delete books
- **Issue & Return** — Track book lending and returns per borrower
- **Issue Reporting** — Log and track book condition issues

## Tech Stack

- **Backend:** Python, Flask
- **Database:** MongoDB Atlas
- **Frontend:** HTML, CSS, Bootstrap
- **Auth/Sessions:** Flask flash messaging

## Getting Started

### Prerequisites

- Python 3.8+
- A [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account (free tier works)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/PiyushaKadam07/Library-Management-System.git
   cd Library-Management-System
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate      # Mac/Linux
   venv\Scripts\activate         # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   Edit `.env` and fill in your MongoDB URI and a secret key:
   ```
   MONGO_URI=mongodb+srv://<username>:<password>@cluster0.xxxxx.mongodb.net/?retryWrites=true&w=majority
   SECRET_KEY=your_random_secret_key_here
   ```

5. **Run the app**
   ```bash
   python app.py
   ```
   Open your browser at `http://localhost:5000`

## Project Structure

```
Library-Management-System/
├── app.py               # Main Flask application
├── requirements.txt     # Python dependencies
├── .env.example         # Environment variable template
├── .gitignore
├── static/              # CSS and static assets
└── templates/           # HTML templates
```

## Author

**Piyusha Kadam** — [github.com/PiyushaKadam07](https://github.com/PiyushaKadam07)
