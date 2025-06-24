# 🧑‍💻 Personal Blog - Django Full Stack Project

A full-stack personal blog application built using **Django**, with a clean and responsive front end using **HTML** and **CSS**. This project showcases my personal blog posts, allows visitors to leave comments, and bookmark posts to read later.


## 🌟 Key Features

- 📝 Only admin can create & manage blog posts
- 💬 Visitors can comment on posts
- 📌 "Read Later" bookmarking functionality for users
- 🔒 Admin panel for full control
- 🌐 Clean and mobile-friendly UI
- 📄 Organized templates and static files for frontend


## 🗂️ Project Structure

my_site/<br>
├── blog/ &nbsp;&nbsp;&nbsp;&nbsp;# Django app with views, models, templates, static files<br>
│   ├── templates/blog/ &nbsp;&nbsp;&nbsp;&nbsp;# HTML files<br>
│   ├── static/blog/    &nbsp;&nbsp;&nbsp;&nbsp;# CSS files<br>
├── my_site/            &nbsp;&nbsp;&nbsp;&nbsp;# Main Django project settings<br>
├── static              &nbsp;&nbsp;&nbsp;&nbsp;# Common CSS file<br>
├── templates           &nbsp;&nbsp;&nbsp;&nbsp;# Common HTML file<br>
├── uploads/<br>
│   ├── posts/          &nbsp;&nbsp;&nbsp;&nbsp;# Contains images<br>
├── manage.py<br>
├── requirements.txt<br>


## 🚀 Getting Started

### 1️⃣ Clone the Repository

>git clone https://github.com/shubhamsahu125/my_site.git<br>
>cd my_site

### 2️⃣ Set Up Virtual Environment (Recommended)

>python -m venv venv
#### Windows
>venv\Scripts\activate
#### macOS/Linux
>source venv/bin/activate

### 3️⃣ Install Dependencies

>pip install -r requirements.txt

### 4️⃣ Apply Migrations

>python manage.py migrate

### 5️⃣ Create Admin User

>python manage.py createsuperuser

### 6️⃣ Run the Server

>python manage.py runserver

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.


## 🔐 Admin Panel

- URL: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)
- Use the superuser credentials created earlier.


## 🧪 Features in Detail

| Feature            | Description                                                          |
|--------------------|----------------------------------------------------------------------|
| Admin Posts        | Only admin can add/edit/delete posts from admin panel                |
| User Comments      | Anyone can view posts and leave comments                             |
| Read Later         | Users can mark posts to read later (stored in session/cookies or DB) |
| Frontend Styling   | Built with HTML5 + CSS3 (fully responsive layout)                    |


## 💻 Tech Stack

- **Backend**: Django
- **Frontend**: HTML, CSS
- **Database**: SQLite
- **Others**: Django Admin, Template Tags, Forms


## 📸 Screenshots

Include screenshots of:
- Homepage with posts   
![Home Page](https://github.com/user-attachments/assets/949a74c3-4334-43a5-96e4-4d0009d57a11)   
- Single blog post with comments   
![Single Blog Post](https://github.com/user-attachments/assets/17e606c8-6990-449a-9259-559c88b51a69)   
![Comment Section](https://github.com/user-attachments/assets/95bcd56b-2d9d-4240-85fe-df78a368fec0)
- All Posts   
![All Posts](https://github.com/user-attachments/assets/b8da6e9b-abe5-4b68-a4de-323e5755ed25)   
- Stored Posts ('Read Later' Feature)   
![Read Later](https://github.com/user-attachments/assets/a9ba9987-79a1-49a3-a125-f5f8d5f1a710)   


## 👤 Author

**Shubham Sahu**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubham-sahu-568737192/)  
[![GitHub](https://img.shields.io/badge/GitHub-Profile-informational?style=flat&logo=github&logoColor=white&color=181717)](https://github.com/shubhamsahu125)   
Python Developer | Backend Specialist in Django & DRF
