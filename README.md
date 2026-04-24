# 🏷️ Auction Alley
### A Django-Based Online Auction Web Application


**Auction Alley** is a full-featured online auction web application built with Django. Users can register, list items for auction, place bids, manage their dashboard, and track auction activity — all from a clean, responsive web interface.

---

## 📁 Project Structure

```
Auction-Alley/
│
├── AuctionAlley/          # Core Django project config (settings, urls, wsgi)
├── Dashboard/             # Auction listings, bidding logic, main features
├── User/                  # User registration, login, profile management
├── templates/             # HTML templates for all pages
├── images/                # Uploaded item images & static assets
├── house_papers/          # Supporting documents / static files
├── db.sqlite3             # SQLite database
├── manage.py              # Django management entry point
└── .gitignore
```

---

## ✨ Features

- **User Authentication** — Register, log in, and log out securely
- **Create Auction Listings** — Post items with title, description, starting bid, and image
- **Live Bidding** — Place bids on active listings; highest bidder wins
- **User Dashboard** — View and manage your own listings and bids
- **Auction Management** — Sellers can close their own auctions at any time
- **Image Support** — Upload product images for listings
- **Admin Panel** — Django's built-in admin interface for full site management
- **SQLite Database** — Lightweight, file-based database for easy local setup

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Django |
| Frontend | HTML, CSS, Django Templates |
| Database | SQLite3 |
| Admin | Django Admin Interface |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip

### 1. Clone the Repository

```bash
git clone https://github.com/Hr-D-LuffY/Auction-Alley.git
cd Auction-Alley
```

### 2. Create a Virtual Environment

```bash
# Create
python -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Activate (Mac/Linux)
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install django
```

> If a `requirements.txt` is present, use:
> ```bash
> pip install -r requirements.txt
> ```

### 4. Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser (Admin Access)

```bash
python manage.py createsuperuser
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

Now open your browser and go to:
```
http://127.0.0.1:8000/
```

Admin panel:
```
http://127.0.0.1:8000/admin/
```

---

## 📖 How to Use

### As a Regular User
1. **Register** a new account or log in
2. Go to **Dashboard** to see all active auction listings
3. Click on any listing to **view details and place a bid**
4. To sell — create a **new listing** with your item details and starting price
5. Close your own auction when ready — the highest bidder wins

### As an Admin
1. Log in at `/admin/` with your superuser credentials
2. View, edit, or delete any listings, bids, or user accounts
3. Monitor all site activity from the admin dashboard

---

## 🗃️ Database

This project uses **SQLite3** (`db.sqlite3`) which is included in the repo for convenience. No separate database setup is needed for local development.



## 👥 Contributors

| GitHub |
| [@arponbiswasanik](https://github.com/arponbiswasanik) | 
| [@Hr-D-LuffY](https://github.com/Hr-D-LuffY) | 
| [@error-makerr](https://github.com/error-makerr) | 

---


