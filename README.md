
-----

### Message Board App

A simple, full-stack message board application built with **Django**. This project uses Django's built-in features to allow users to create, view, and delete messages stored in a local SQLite database.

-----

### ✨ Features

  * **Anonymous Posting:** Create and share messages without needing to register or log in.
  * **Message Management:** View all messages on a single page and delete them.
  * **Data Persistence:** All messages are stored and managed by Django's ORM and a built-in SQLite database.
  * **Admin Panel:** Utilizes Django's powerful admin interface for easy data management.

-----

### 💻 Tech Stack

  * **Django:** The core backend framework, providing an ORM, routing, and an admin panel.
  * **SQLite:** The default, file-based database for development.
  * **HTML, CSS & JavaScript:** For the frontend templates and user interaction.

-----

### ⚙️ Getting Started

Follow these steps to get a local copy of the project running.

#### **1. Clone the repository**

```bash
git clone https://github.com/sujith-ox/message-board.git
cd message-board
```

#### **2. Set up the project**

First, create a virtual environment to manage dependencies:

```bash
python -m venv venv
```

Activate the environment:

  * On Windows: `venv\Scripts\activate`
  * On macOS/Linux: `source venv/bin/activate`

Next, install the required packages.

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt` file, you can install just Django: `pip install django`.

#### **3. Apply migrations**

Django automatically handles database setup with its migration system.

```bash
python manage.py migrate
```

#### **4. Run the development server**

```bash
python manage.py runserver
```

The application will be available at `http://localhost:8000`.

-----

### 📄 License

This project is licensed under the **MIT License**.
