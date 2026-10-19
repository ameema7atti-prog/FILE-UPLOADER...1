# File Uploader (Syntecxhub Internship - Week 2)

An API built with **Node.js**, **Express**, **Multer**, and **MongoDB GridFS** to handle binary file uploads, stream file downloads, and secure file deletions[cite: 5, 8].

This project is part of the **Syntecxhub Web Development Internship Program**[cite: 1, 5].

---

## 🚀 Features
- **File Uploads**: Handles multipart/form-data uploads using Multer and GridFS storage drivers[cite: 8].
- **Database Storage**: Stores large files directly within MongoDB collections safely[cite: 8].
- **File Retrieval & Streaming**: Fetch metadata lists or stream files directly via name endpoints[cite: 8].
- **File Deletion**: Securely remove files using their GridFS identifier[cite: 8].
- **Validation**: Built-in file size constraints and error handling[cite: 8].

---

## 📌 API Endpoints Overview

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **POST** | `/api/upload` | Upload a single file (`multipart/form-data`)[cite: 8] |
| **GET** | `/api/files` | Retrieve metadata of all uploaded files[cite: 8] |
| **GET** | `/api/files/:filename` | Stream/download a file by its filename[cite: 8] |
| **DELETE** | `/api/files/:id` | Delete a file from MongoDB GridFS by its ID[cite: 8] |

---

## ⚙️ Setup & Local Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/Syntecxhub_File_Uploader.git](https://github.com/your-username/Syntecxhub_File_Uploader.git)
   cd Syntecxhub_File_Uploader
