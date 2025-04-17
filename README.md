# ChapterVerse: A Web-Based Bookstore Implemented with MERN Stack

ChapterVerse is an intuitive and scalable online bookstore built using the MERN (MongoDB, Express.js, React, Node.js) stack. It offers a user-friendly interface for customers to explore, purchase, and manage books online while providing administrators with complete control over book inventory, order management, and customer support.

---

## 📌 Table of Contents
- [Features](#features)
- [System Architecture](#system-architecture)
- [Workflow Diagram](#workflow-diagram)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## ✨ Features

- User Registration and Secure Login (JWT-based)
- Browse & Search Books by title, category, author
- AI-powered book recommendations
- Cart and secure checkout system
- Admin panel for inventory & order management
- Chatbot for FAQs, book suggestions & support
- Order tracking and confirmation system
- Clean and responsive UI/UX

---

## 🧩 System Architecture

The platform is based on a client-server architecture where React handles the front-end, Node.js/Express manages the server-side logic, and MongoDB is used for data storage.

![System Architecture](./assets/system_architecture.png)

---

## 🔁 Workflow Diagram

The following flowchart explains the entire flow from user registration to order tracking and admin functionalities.

![User Workflow](./assets/user_workflow.png)

---

## 🧑‍💻 Tech Stack

| Technology | Description                     |
|------------|---------------------------------|
| React      | Frontend UI framework           |
| Node.js    | Backend runtime environment     |
| Express.js | Web application framework       |
| MongoDB    | NoSQL database                  |
| JWT        | Secure authentication           |
| Razorpay / Stripe | Payment integration    |

---

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/chapterverse.git
``` 
2. Navigate to the root directory:

``` bash
cd chapterverse
```
3. Install server dependencies:

```bash

cd backend
npm install
```
4. Install client dependencies:

```bash

cd ../frontend
npm install
```
5. Setup environment variables (.env) in both folders

6. Start the application:

```bash

# Start backend
cd backend
npm start

# In new terminal, start frontend
cd frontend
npm start

```

--- 

## 🚀 Usage

1. Register/Login as a user or admin

2. Search and filter books

3. Add to cart, place orders, and track them

4. Admin can manage books & orders via dashboard

5. Chatbot for support and suggestions

   ---

## 🖼️ Screenshots

![Homepage](./assets/homepage.png)
![Add To Cart](./assets/addtocart.png)
![Login](./assets/login.png)

---


## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License
This project is licensed under the MIT License.
---


## Built with 💙 by Ritik Maurya


---


