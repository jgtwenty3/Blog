# Blog

Blog
This is the beginning of a minimalistic blog/social media application built using no Javascript, only Python and HMTL. It allows users to create, read, and delete blog posts as well as add, and delete comments to those posts. I want to style it differently, but it's functioning well at the moment. 

Features
User authentication: Users can sign up, log in, and log out securely.
Responsive design: The application is designed to be accessible and usable across various devices and screen sizes.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/jgtwenty3/Blog.git
Navigate into the project directory:

bash
Copy code
cd Blog
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
Activate the virtual environment:

On Windows:
bash
Copy code
venv\Scripts\activate
On macOS and Linux:
bash
Copy code
source venv/bin/activate
Install the required dependencies:

bash
Copy code
pip install

Set up the database:

bash
Copy code
flask db init
flask db migrate
flask db upgrade
Run the application:

bash
Copy code
flask run
Open your web browser and go to http://localhost:5000 to access the application.

Usage
Sign up for an account if you don't have one.
Log in using your credentials.
Create, read, or delete blog posts from the dashboard.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

If you have any questions or suggestions, feel free to contact me:

Email:justinguerrerowork@gmail.com
