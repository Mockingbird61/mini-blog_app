# 📝 Mini Blog Application (PHP + MySQL)

A simple full-stack blog application that allows users to create and delete posts.  
Built using **PHP**, **MySQL**, **HTML**, and **CSS**.

## 🚀 Features
- Add new blog posts  
- Delete posts  
- List all posts  
- MySQL database integration  
- Simple CRUD system  
- Clean UI  

## 🛠️ Technologies Used
- PHP  
- MySQL (phpMyAdmin)  
- HTML5  
- CSS3  

## 🗄️ Database Setup
Create a database named **blog_db**, then run:

```sql
CREATE TABLE posts (
  id INT AUTO_INCREMENT PRIMARY KEY,
  title VARCHAR(255) NOT NULL,
  content TEXT NOT NULL,
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
