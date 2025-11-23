🧾 Expenses Application — 3-Tier Architecture

A fully structured 3-Tier Expenses Management Application built using:

Frontend → NGINX (serving static UI)

Backend → Node.js (REST API for expenses)

Database → MySQL (persistent expense storage)

This architecture separates presentation, logic, and data layers, making the system easier to manage, secure, and scale.

📌 About

This project implements a 3-Tier Architecture for an Expenses Tracking Application. Each layer is isolated and runs independently, following modern cloud and DevOps design patterns:

1️⃣ Frontend (Nginx)

Serves static HTML/CSS/JS files

Communicates with backend API

Optimized for speed using NGINX caching and serving

2️⃣ Backend (Node.js)

Provides RESTful API endpoints

Handles business logic (add, update, delete, list expenses)

Connects securely to MySQL

Returns JSON responses

3️⃣ Database (MySQL)

Stores expenses, categories, users, etc.

Provides persistent and structured data storage

Supports relational queries

This separation ensures scalability, modularity, and ease of deployment.