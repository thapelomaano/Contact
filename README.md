# Contacts Manager App

This is a simple contacts management system built using:

- ASP.NET Core Web API (backend)
- Blazor WebAssembly (frontend)
- SQLite (database)

It supports CRUD operations for contacts.

---

## Features

- Create, Read, Update, and Delete (CRUD) contacts
- Blazor WebAssembly frontend with form validation
- API tested via Swagger or REST clients
- Responsive UI and styled tables/forms

---

## Project Structure

ContactAPI - ASP.NET Core Web API (.NET 7+)
ContactUI  Blazor WebAssembly frontend
contacts.db - SQLite DB (auto-created)

---

## ⚙️ Prerequisites

- [.NET 7 SDK](https://dotnet.microsoft.com/en-us/download)
- Visual Studio 2022+ or VS Code
- SQLite

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

git clone https://github.com/your-username/contact-manager.git
cd contact-manager

### 2. Run Api 
cd ContactAPI
dotnet ef database update   # Apply DB migrations
dotnet run

### 3. Run Frontend(Blazer)
cd ../ContactUI
dotnet run
