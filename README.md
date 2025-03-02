# Post API Project

This is a RESTful API for managing posts in a simple blogging application. The API allows users to create, read, update, and delete posts. It is built using Flask, SQLAlchemy, and PostgreSQL.

## Features

- User authentication via JWT
- Create, read, update, and delete posts
- Relational database model with `User` and `Post` entities
- Data validation and error handling
- Secure password hashing

## Technologies

- **Flask**: A lightweight Python web framework.
- **SQLAlchemy**: ORM for database interaction.
- **PostgreSQL**: Relational database to store user and post data.
- **Flask-JWT-Extended**: JWT-based authentication for secure endpoints.
- **Flask-CORS**: Handle cross-origin requests.

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/filmonalem/post_api_python.git
cd post_api_python
