# 📝 Flask Blog Project

A dynamic blog application built using Flask. Users can register, log in, and add, edit, and delete blog posts. The app includes a commenting system for registered users and an admin-only dashboard for managing posts.

## 📋 Features
- **Home Page (`/`)**: Displays all blog posts from the database.
- **Post Detail Page (`/post/<post_id>`)**: View individual blog posts with comments.
- **Create New Post (`/new-post`)**: Add a new blog post (admin only).
- **Edit Post (`/edit-post/<post_id>`)**: Update blog post content (admin only).
- **Delete Post (`/delete/<post_id>`)**: Permanently remove a post (admin only).
- **User Registration and Login**:
  - Register as a new user.
  - Log in to comment on posts.
- **Static Pages**:
  - `/about`: Information about the blog.
  - `/contact`: Contact form or details.

## 🛠️ Technologies Used
- **Flask**: Web framework.
- **Flask-Bootstrap**: Frontend styling.
- **Flask-CKEditor**: WYSIWYG editor for creating rich-text content.
- **Flask-Login**: User authentication and management.
- **SQLAlchemy**: Database ORM.
- **SQLite**: Backend database.

## 🚀 Prerequisites
Make sure you have the following installed:
- Python 3.x
- Flask and other dependencies (listed in `requirements.txt`)

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
    ```
2. Install dependencies:
```bash
python -m pip install -r requirements.txt
```
3. Initialize the database:
```bash
python main.py
```
This will create a posts.db SQLite database.
## 🛠️ How to Run
1. Start the Flask server:
```bash
python main.py
```
2. Open your browser and navigate to:
```plaintext
http://127.0.0.1:5001
```
## 🖊️ Usage
- Add New Posts: Admin users can visit /new-post to create a new post.
- Edit Posts: Admin users can update posts at /edit-post/<post_id>.
- Delete Posts: Admin users can remove posts at /delete/<post_id>.
- Commenting: Registered users can add comments on post detail pages.
## 🗄️ Database Details
- Database: SQLite (posts.db)
- Tables:
  - users: Stores user data (email, password, name).
  - blog_posts: Stores blog post data (title, subtitle, body, etc.).
  - comments: Stores comments on posts.
## 🎨 Customization
- Templates: Modify HTML templates (e.g., index.html, post.html) for design changes.
- Routes: Enhance functionality by updating main.py.
- Styling: Use a different Bootstrap theme or CSS framework for a unique look.
## 📜 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the license.
