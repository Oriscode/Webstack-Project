# Webstack-Project - Social Media Blog
Welcome to the Webstack-Project repository! This project is a social media blog where users can create, retrieve, update, and delete posts. It utilizes FastAPI and PostgreSQL as its main technologies.

## Features
- User Authentication: Users are required to log in before they can interact with the blog's functionalities.
- Post Management: Users can create new posts, retrieve existing posts, update their own posts, and delete their posts.
- PostgreSQL Database: The project uses PostgreSQL to store user information and blog posts.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
```
git clone https://github.com/Oriscode/Webstack-Project.git
```
2. Navigate to the project directory:
```
cd Webstack-Project
```
3. Install the required dependencies. It is recommended to use a virtual environment:
```
python -m venv venv
source venv/bin/activate  # For Unix/Linux
venv\Scripts\activate  # For Windows
pip install -r requirements.txt
```
4. Configure the PostgreSQL database. Create a PostgreSQL database and update the necessary configuration settings in the config.py file.

5. Run the database migrations:
```
alembic upgrade head
```
6. Start the FastAPI server:
```
uvicorn app.main:app --reload
```
7. Access the application by visiting [FastAPI_Server] (http://localhost:8000) in your web browser.

## API Documentation
The project provides API endpoints for user authentication and blog post management. The API documentation can be accessed by visiting http://localhost:8000/docs when the server is running.

## Contributing
Contributions to the Webstack-Project are welcome! If you find any issues or have improvements to suggest, please open an issue or submit a pull request on the GitHub repository.

## License
This project is licensed under the MIT License.
