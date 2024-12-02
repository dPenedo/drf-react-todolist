# Django Rest Framework + React To-Do List App

A full-stack To-Do List application built with **Django Rest Framework (DRF)** and **React**. It includes API documentation, a responsive user interface styled with **Tailwind CSS**, and real-time notifications powered by **React Hot Toast**.

## Features

- **Backend**:
  - RESTful API built using DRF.
  - Self-documenting API available at `/tasks/docs/`.
  - Fully supports CRUD operations for tasks.
- **Frontend**:
  - Built with React and styled using Tailwind CSS.
  - Real-time feedback with Hot Toast notifications.
- **Key Functionalities**:
  - Create, read, update, and delete tasks.
  - Mark tasks as complete/incomplete.
  - Intuitive user interface.

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js 14+
- npm or yarn

### Backend Setup

1. Clone the repository:

```bash
   git clone https://github.com/yourusername/todolist-app.git
   cd todolist-app
```


2. Set up a virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

3. Apply migrations and start sever:

```python
python manage.py migrate
python manage.py runserver
```
3. Access the API documentation at `http://localhost:8000/tasks/docs/`.


### Frontend Setup

1. Navigate to the frontend directory `client/`:

```bash
cd client/
```
2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

4. Access the app at `http://localhost:3000`.


