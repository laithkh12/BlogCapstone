# Flask Blog Project
This project is a simple blog application built using Flask. It fetches blog posts from an external API (npoint.io) and displays them on various pages. It also includes a dynamic routing feature to display individual blog posts based on their unique ID.
## Features
- **Home Page (/)**: Displays all blog posts fetched from the external API.
- **About Page (/about)**: A static page that provides information about the blog.
- **Contact Page (/contact)**: A static page with a contact form or contact details.
- **Post Detail Page (/post/<int:index>)**: Displays a single post based on its ID from the API
## Prerequisites
Make sure you have the following installed:
- Python 3.x
- Flask
- Requests
## Installation
1. Clone the repository:
```bash
git clone <repository-url>
cd <project-directory>
```
## How to Run
1. Start the Flask server:
```bash
python app.py
```
2. Open your browser and go to http://127.0.0.1:5001 to view the website.
## Usage
- The homepage will display all blog posts.
- The About page provides information about the project.
- The Contact page can include any necessary contact details or a form.
- To view a specific blog post, navigate to /post/<id> where <id> is the ID of the post you want to view.
## External API
The project fetches blog posts from this npoint.io API:
- API URL: https://api.npoint.io/c790b4d5cab58020d391
- The data returned from the API includes post details like id, title, subtitle, and body.
## Customization
- You can replace the npoint URL with your own API if you have a different source of blog posts.
- Modify the templates (index.html,post.html) to suit your design.
## License
This project is open-source and available under the MIT License.
---
