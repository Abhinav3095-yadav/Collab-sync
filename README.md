# Collab-sync
# 🚀 CollabSync – Real-Time Collaborative Document Sync Engine

**CollabSync** is a real-time collaborative document editing platform inspired by Google Docs. It allows multiple authenticated users to work on the same document simultaneously while keeping everyone's changes synchronized.

The project uses WebSocket-based communication and an operation-based synchronization mechanism to handle concurrent editing efficiently. Instead of repeatedly sending the entire document, it processes individual INSERT, DELETE, and REVERT operations.

One of its key features is **Operational Transformation (OT)**, which helps resolve editing conflicts when multiple users modify the same document at the same time.

### ✨ Key Features

- **User Authentication:** Secure registration and login using JWT and BCrypt password hashing.
- **Real-Time Collaboration:** Multiple users can edit a document simultaneously.
- **Operational Transformation:** Handles concurrent editing operations and resolves conflicts.
- **Offline Synchronization:** Preserves offline changes and synchronizes them after reconnection.
- **Document Management:** Create, view, and manage collaborative documents.
- **Version History:** Track document changes and retrieve previous versions.
- **Document Revert:** Restore a document to an earlier version.
- **WebSocket Communication:** Enables real-time updates between connected users.
- **Conflict Prevention:** Uses document-level locking and version tracking to prevent stale updates.
- **Responsive Frontend:** React-based user interface with collaborator and connection status indicators.

### 🛠️ Technologies Used

- Java 17
- Spring Boot
- React.js
- JavaScript
- MongoDB Atlas
- WebSocket
- Spring Security
- JWT Authentication
- BCrypt
- Maven
- Vite
- Docker
- Render

### 🎯 Project Objective

The main objective of CollabSync is to develop a reliable collaborative editing system that allows multiple users to work together without losing updates or overwriting each other's changes.

### 🌐 Live Demo

https://collab-sync-68rm.onrender.com/index.html
