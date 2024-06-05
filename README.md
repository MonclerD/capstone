# Manu by Mau

## Overview
This repository contains the source code for a web application built with Flask. The app is designed to create and manage children's stories, utilizing OpenAI's API for generating and moderating content.

## Features
- **User authentication (registration and login)**
- **Story creation with content moderation**
- **Image generation for stories**
- **Viewing and managing created stories**

## Installation
1. **Clone the repository:**
    ```sh
    git clone https://github.com/MonclerD/Bitirme4/tree/main/Bitirme4
    ```
2. **Navigate to the project directory:**
    ```sh
    cd LikeThat/Bitirme4
    ```
3. **Install the required dependencies:**
    ```sh
    pip install Flask requests openai werkzeug
    ```

## Initial Setup
1. **Initialize the database:**
    ```sh
    python app.py
    ```
    This will create the necessary SQLite database (`users.db`) and tables for the application.

2. **Configure your environment variables:**
    - Replace `'your_secret_key'` in `app.py` with your secret key.
    - Replace `'open_ai_api'` with your OpenAI API key.

## Usage
1. **Run the application:**
    ```sh
    flask run
    ```
2. **Access the application** by navigating to `http://127.0.0.1:5000/` in your web browser.

## Directory Structure
- `app.py`: Main application file
- `static/`: Static files (CSS, JS, images)
- `templates/`: HTML templates
- `users.db`: SQLite database file

## Routes
- `/` - Home page
- `/login` - Login page
- `/register` - Registration page
- `/about` - About page
- `/create` - Create a new story
- `/books` - View your books
- `/read_book/<int:book_id>` - Read a specific book
- `/logout` - Logout

## License
This project is licensed under the MIT License.
