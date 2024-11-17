# Library Management System - Full Stack Development  

**Developed By: Harshitha M R**  

## Project Overview  
The **Library Management System** is a full-stack web application that helps manage library operations, such as book cataloging, member management, and borrowing activities. It provides an efficient and user-friendly interface for librarians and members to streamline library operations.  

---  

## Features  

### Admin Features  
- Manage books (add, update, delete).  
- Manage library members.  
- View borrowing and return records.  

### User Features  
- Search for books by title or author.  
- View book availability.  
- Borrow and return books.  

---  

## Tech Stack  

### Frontend  
- **HTML/CSS**: To design and style the interface.  
- **JavaScript**: For interactive elements and dynamic updates.  

### Backend  
- **Django**: A Python-based web framework for server-side logic.  

### Database  
- **SQLite**: Default database for development.  

---  

## Installation and Setup  

### **1. Clone the Repository**  
```bash  
git clone https://github.com/your-repository-url/library-management-system.git  
cd library-management-system  
```  

### **2. Install Requirements**  
Use the following command to install all required dependencies:  
```bash  
pip install -r requirements.txt  
```  

### **3. Database Setup**  
Make the necessary database migrations:  
```bash  
python manage.py makemigrations  
python manage.py migrate  
```  

### **4. Create Admin Account**  
Create a superuser account to manage the system:  
```bash  
python manage.py createsuperuser  
```  

### **5. Run the Application**  
Start the development server with the following command:  
```bash  
python manage.py runserver  
```  

### **6. Access the Application**  
Open your browser and navigate to:  
- **Frontend**: `http://127.0.0.1:8000/`  
- **Admin Panel**: `http://127.0.0.1:8000/admin`  

---  

## Folder Structure  

```  
library-management-system/  
├── library/               # Django project files  
├── app_name/              # Application files (models, views, templates)  
├── static/                # CSS, JS, images, and other static files  
├── templates/             # HTML templates  
├── db.sqlite3             # Database file  
├── manage.py              # Django management script  
└── requirements.txt       # Dependencies  
```  

---  

## Contribution  
We welcome contributions to enhance this project! Follow these steps to contribute:  
1. Fork the repository.  
2. Create a new branch for your feature or bug fix.  
3. Commit your changes and push to the branch.  
4. Submit a pull request.  

---  


## Contact  
For any queries or feedback, reach out to **Harshitha M R**.  

---  

