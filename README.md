# 📝 Flask Blog Project
A dynamic blog application built using Flask. Users can add, edit, and delete blog posts directly from the web interface. The application uses SQLite for database management, Bootstrap for styling, and CKEditor for blog content editing.
## 📋 Features
- Home Page (/): Displays all blog posts from the database.
- Post Detail Page (/post/<post_id>): View a detailed page of an individual blog post.
- Create New Post (/new-post): Add a new blog post using a form with CKEditor.
- Edit Post (/edit-post/<post_id>): Update an existing blog post's content.
- Delete Post (/delete/<post_id>): Remove a blog post permanently from the database.
- About Page (/about): Provides information about the blog.
- Contact Page (/contact): Includes contact details or a contact form.
## 🚀 Prerequisites
Make sure you have the following installed:
- Python 3.x
- Flask
- Flask-Bootstrap
- Flask-WTF
- Flask-CKEditor
## 📦 Installation
1. Clone the repository:
```bash
git clone <repository-url>  
cd <project-directory>  
```
2. Install dependencies:
On Windows:
```bash
python -m pip install -r requirements.txt
```
On MacOS/Linux:
```bash
pip3 install -r requirements.txt  
```
## 🛠️ How to Run
1. Start the Flask server:
```bash
python main.py  
```
2. Open your browser and navigate to:
```arduino
http://127.0.0.1:5002  
```
## 🖊️ Usage
- Add New Posts: Visit /new-post and use the form to create a new blog post.
- Edit Existing Posts: Navigate to /edit-post/<post_id> to update content.
- Delete Posts: Go to /delete/<post_id> to remove a post permanently.
- View All Posts: Check the homepage to see all published blog posts.
- Static Pages: Visit /about and /contact for additional blog information.
## 🗄️ Database Details
- Database: SQLite (posts.db)
- Table: BlogPost
- Columns:
  - id (Primary Key)
  - title
  - subtitle
  - date
  - body
  - author
  - img_url
## 🎨 Customization
- Update the HTML templates (index.html, post.html, etc.) to change the design.
- Modify main.py to add more routes or enhance functionality.
- Replace CKEditor with another editor if needed.
## 📜 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the license.
---

