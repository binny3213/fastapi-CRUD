# 📚 FastAPI Book CRUD API

A simple REST API built with **FastAPI** to manage a collection of books.  
The project demonstrates how to use FastAPI to perform basic **CRUD** operations  
(Create, Read, Update, Delete) on an in-memory list of book records.

---

## 🚀 Features

- View all books
- Get books by title, author, or category
- Add a new book
- Update an existing book
- Delete a book by title
- Supports both path and query parameters

---

## 🧪 Endpoints Overview

| Method | Endpoint                                | Description                                 |
|--------|------------------------------------------|---------------------------------------------|
| GET    | `/books`                                 | Get all books                               |
| GET    | `/books/{book_title}`                    | Get book by title                           |
| GET    | `/books/?category=math`                  | Get books by category (query param)         |
| GET    | `/books/{book_author}/?category=math`    | Get books by author & category              |
| GET    | `/books/byauthor/{book_author}/`         | Get books by author                         |
| POST   | `/books/create_book`                     | Add a new book (via request body)           |
| PUT    | `/books/update_book`                     | Update book details (via request body)      |
| DELETE | `/books/delete_book/{book_title}`        | Delete book by title                        |

---


<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" **alt="Python" width="40" height="40"/>  

</div>
