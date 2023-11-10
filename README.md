# 📚 StudyBud

StudyBud is not just another learning platform; it's your virtual study companion! 🚀 Built using Django, Django REST framework, and SQLite as the trusty sidekick database, StudyBud is here to make studying as enjoyable as a Discord chat. 🤓

## ✨ Features

- **User Authentication**: Students can create accounts, log in securely, and become part of the StudyBud community.

- **Chat Channels**: Dive into various chat channels tailored for different subjects or topics.

- **Real-Time Messaging**: Enjoy lightning-fast communication with fellow students through real-time messaging within channels.

- **Resource Sharing**: Share the love for learning by exchanging study materials, links, and resources seamlessly.

- **API Integration**: Harness the power of Django REST framework to interact with StudyBud programmatically.

## 🚀 Getting Started

Embark on your StudyBud journey by setting up the project on your local machine.

### 🛠️ Prerequisites

Ensure you have Python and pip installed. Create a virtual environment to manage dependencies.

```bash
python -m venv venv
```

Activate the virtual environment:

- On Windows:

```bash
venv\Scripts\activate
```

- On macOS and Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### 🗃️ Database Setup

Apply migrations to set up the SQLite database:

```bash
python manage.py migrate
```

### 🚀 Running the Server

Start the development server:

```bash
python manage.py runserver
```

Visit `http://localhost:8000` in your web browser to dive into the StudyBud experience.

## 🌐 Deployment

Catch StudyBud live on Render at [https://studybud-jgtq.onrender.com/](https://studybud-jgtq.onrender.com/).

## 🙌 Acknowledgments

A big shoutout to @DennisIvy for being an inspiration in the development journey! 🌟

---

Feel free to contribute and make StudyBud even more awesome! 🚀📚
