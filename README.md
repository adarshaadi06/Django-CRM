# Django-CRM  

## 📌 Overview  
Django-CRM is a customer management system built with Django, allowing users to register, log in, and manage customer records efficiently. It features dynamic HTML pages, URL routing, and database interactions using MySQL.  

## 🚀 Features  
- ✅ User Registration & Authentication (Login, Logout)  
- ✅ Admin Dashboard for Customer Management  
- ✅ CRUD Operations: Add, Update, Delete Customer Records  
- ✅ MySQL Database Integration  
- ✅ Role-Based Access Control (Admin/User)  
- ✅ Pagination and Search Functionality  

## 🛠️ Tech Stack  
- **Backend**: Django (Python)  
- **Frontend**: HTML, CSS, Bootstrap  
- **Database**: MySQL  
- **Authentication**: Django’s built-in Auth System  

---

## 📂 Installation Guide  

### **Step 1: Clone the Repository**  
git clone https://github.com/adarshaadi06/Django-CRM.git
cd Django-CRM

### Step 2: Create a Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows

### Step 3: Install Dependencies
-pip install -r requirements.txt



## Step 4: Configure Database
-DATABASES = {
-    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'your_db_name',
        'USER': 'your_db_user',
        'PASSWORD': 'your_db_password',
        'HOST': 'localhost',
        'PORT': '3306',
-   }
-}

## Run migrations:

-python manage.py makemigrations
-python manage.py migrate

## Step 5: Create a Superuser

- python manage.py createsuperuser

## Step 6: Run the Server

-python manage.py runserver





