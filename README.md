# Book Recommender System

## Overview
This project is a **Book Recommender System** that suggests books to users based on both popularity and collaborative filtering methods. It provides personalized recommendations based on user inputs such as book titles or authors. The system is designed with a user-friendly interface and is deployed using Flask and Gunicorn.

**Live Demo**: [Book Recommender System](https://book-recommender-system-i36e.onrender.com/)

## Features
- **Book Recommendations**: Provides personalized book recommendations based on user input (title or author).
- **Collaborative Filtering**: Recommends books based on similar user preferences and past interactions.
- **Popularity-Based Filtering**: Recommends books based on overall popularity among users.
- **Responsive UI**: Designed using Bootstrap to ensure smooth user interaction and experience.
- **Deployed on Render**: The application is deployed with high availability and minimal downtime.

## Technologies Used
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, Bootstrap, Font Awesome
- **Database**: CSV-based dataset for book information
- **Web Server**: Gunicorn
- **Deployment**: Render

## Installation Instructions
Follow these steps to run the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/YourUsername/book-recommender-system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd book-recommender-system
    ```
3. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5. Run the application:
    ```bash
    python app.py
    ```
6. Open your browser and go to:
    ```
    http://127.0.0.1:5000/
    ```

## Usage
1. Enter a book title or author in the search bar.
2. Click on "Get Recommendations" to see a list of recommended books.
3. Browse through the recommendations, which include book titles and author details.

## Project Structure
```bash
.
├── app.py              # Main Flask app file
├── static/             # CSS, JavaScript, images, and other static files
├── templates/          # HTML templates
├── data/               # Dataset files
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
