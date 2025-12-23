# Node.js CRUD REST API

Project ini merupakan REST API sederhana menggunakan Node.js dan Express.js
dengan fitur CRUD (Create, Read, Update, Delete) untuk tabel:
- users
- categories
- products

Project ini dibuat untuk memenuhi Tugas Praktikum Node.js & Express.js — CRUD API.

---

## Teknologi
- Node.js
- Express.js
- MySQL
- mysql2
- dotenv
- Postman

---

## Struktur Project
crud/
├── server.js
├── package.json
├── config/
│   └── db.js
├── controllers/
│   ├── userController.js
│   ├── categoryController.js
│   └── productController.js
└── routes/
    ├── userRoutes.js
    ├── categoryRoutes.js
    └── productRoutes.js

---

## Endpoint API

USERS  
GET    /users  
GET    /users/:id  
POST   /users  
PUT    /users/:id  
DELETE /users/:id  

CATEGORIES  
GET    /categories  
GET    /categories/:id  
POST   /categories  
PUT    /categories/:id  
DELETE /categories/:id  

PRODUCTS  
GET    /products  
GET    /products/:id  
POST   /products  
PUT    /products/:id  
DELETE /products/:id  

---

## Contoh Request Postman

POST User  
URL: http://localhost:3000/users  
Body (JSON):
{
  "name": "Budi",
  "email": "budi@mail.com",
  "password": "123456"
}

POST Category  
URL: http://localhost:3000/categories  
Body (JSON):
{
  "name": "Minuman"
}

POST Product  
URL: http://localhost:3000/products  
Body (JSON):
{
  "category_id": 1,
  "name": "Es Teh",
  "price": 5000
}

---

## Dokumentasi
Screenshot hasil pengujian API menggunakan Postman disertakan pada repository
sebagai bukti bahwa seluruh endpoint CRUD berjalan dengan baik.

---

## Author
Nama  : Vaena Miftakhur Risko
NIM : 24090100  
Prodi : Teknik Informatika  
Semester : 3
