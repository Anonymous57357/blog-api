# Blog API

## Overview
The **Blog API** is a backend service built with Node.js and Express, providing CRUD operations for blog posts, user authentication, and support for pagination and filtering of blog posts.

---

## Features

- **User Authentication**:
  - Register new users.
  - Login and receive a JWT token for secured access.
  - Middleware to protect private routes.

- **CRUD Operations**:
  - Create, read, update, and delete blog posts.
  - Each post is linked to a specific user.

- **Pagination and Filtering**:
  - Retrieve paginated blog posts.
  - Filter posts by author or title.

---

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: SQLite (for simplicity, switchable to mongodb)

---

## Installation and Usage

### Prerequisites
- Node.js installed on your system.
- mongoDB installed.

### Installation    
1. Clone the repository:
   ```bash
   git clone https://github.com/Anonymous57357/blog-api.git
   cd blog-api

