# Web-Development-Evaluation-Task-Realtime-Product-Dashboard
Web Development Evaluation Task: Realtime Product Dashboard



# Realtime Product Dashboard
A web-based Product Dashboard built using **vanilla JavaScript**, **Firebase Realtime Database**, and **DummyJSON API**.
This app allows you to:- View live products from an external API- Add your own products to Firebase- Edit or delete your products in real-time- Sort, filter, and search all products- Save UI preferences using localStorage
---
## Features
### Dashboard (DummyJSON API)- Fetches product data from `https://dummyjson.com/products`- Shows products in card layout (title, description, image, price)- Supports:  - Sorting (by price or name)  - Filtering (by category)  - Pagination (dynamic)- State (sort, filter, page) persists using `localStorage`
### Add Product (Firebase)- Add products via a form- Fields: Title, Description, Price, Thumbnail URL- Data is stored in Firebase Realtime Database using `POST`
### View Products from Firebase- Separate section to view user-added products- Data fetched from Firebase using `GET`
### Edit and Delete (Firebase)- Edit product inline and update in Firebase (`PATCH`)- Delete product from Firebase (`DELETE`)
### Search Functionality- Real-time search filter for product titles

## Live Demo
> [ View Live Project Here]https://github.com/Tarunbhardwaj027/Web-Development-Evaluation-Task-Realtime-Product-Dashboard/tree/main




 Folder Structure
├── index.html
├── style.css
├── script.js
├── README.md


 Technologies Used

HTML5
CSS3
JavaScript (Vanilla)
Firebase Realtime Database
DummyJSON REST API
LocalStorage



Let me know if you'd like help customizing it for your GitHub username or Firebase link, or if you want the full project files (`HTML + JS + CSS`) ready to upload.

