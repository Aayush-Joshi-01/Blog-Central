# Blog Central - A Django Blog Website

Blog Central is a simple and elegant blog website built using Python Django. It allows users to read and write blog posts. The user interface is designed with basic yet attractive HTML and internal CSS. This README file provides instructions for setting up and running the website.

## Features

- User-friendly interface with HTML and internal CSS.
- User registration and login functionality.
- Ability to add, edit, and delete blog posts.
- View and comment on blog posts.
- User authentication for enhanced security.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python (version 3.6 or higher)
- Django (version 3.0 or higher)

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Aayush-Joshi-01/Blog-Central.git
   ```

2. Change into the project directory:

   ```bash
   cd blog-central
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Apply the database migrations:

   ```bash
   python manage.py migrate
   ```

7. Create a superuser account to manage the admin panel:

   ```bash
   python manage.py createsuperuser
   ```

   Follow the prompts to create a superuser account.

8. Run the development server:

   ```bash
   python manage.py runserver
   ```

   The website will be accessible at `http://127.0.0.1:8000/`.

9. Access the admin panel:

   - Navigate to `http://127.0.0.1:8000/admin/`
   - Log in with the superuser account you created earlier.

10. You can start adding blog posts from the admin panel or create a user account on the website to add posts through the user interface.

## Usage

1. Register a new user account on the website.

2. Log in using your credentials.

3. Once logged in, you can:

   - View existing blog posts.
   - Add new blog posts.
   - Edit and delete your own blog posts.
   - Comment on blog posts.

4. To access the admin panel, visit `http://127.0.0.1:8000/admin/` and log in with your superuser account. From the admin panel, you can manage users, blog posts, and comments.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The project uses Django for the web framework.
- HTML and internal CSS have been used for the user interface.

## Contact Information

If you have any questions or need assistance, please feel free to contact us at [aayushjoshi.dev@gmail.com](mailto:aayushjoshi.dev@gmail.com).

Thank you for using Blog Central! Happy blogging!