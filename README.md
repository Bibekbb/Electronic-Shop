

# Sasto Pasal - Electronic Shop

**Sasto Pasal** is a modern, full-featured electronic e-commerce web application built with Django. The platform provides a complete online shopping experience for electronics, from browsing products to secure checkout.

![E-commerce Platform](https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)
*A modern online shopping interface*

## ✨ Features

- **User Authentication & Profiles**: Secure user registration, login, and personalized dashboards.
- **Product Catalog**: Browse electronics by categories with detailed product views, images, and specifications.
- **Shopping Cart**: Add, update, and remove items before checkout.
- **Order Management**: Place orders, view order history, and track order status.
- **Admin Dashboard**: Full-featured backend for managing products, orders, users, and inventory.
- **Responsive Design**: Accessible on desktop, tablet, and mobile devices.

## 🏗️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Backend Framework** | Django (Python) |
| **Database** | SQLite (Development) |
| **Frontend** | HTML, CSS, JavaScript, Django Templates |
| **Authentication** | Django's built-in authentication system |
| **Version Control** | Git & GitHub |

## 📁 Project Structure

```
Electronic-Shop/
│
├── sastopasal/              # Main Django project directory
│   ├── __init__.py
│   ├── settings.py          # Project settings
│   ├── urls.py              # Main URL routing
│   └── wsgi.py              # WSGI configuration
│
├── shop/                    # Main Django application
│   ├── migrations/          # Database migrations
│   ├── templates/           # HTML templates
│   ├── static/              # CSS, JS, images
│   ├── models.py            # Database models
│   ├── views.py             # Application logic
│   ├── urls.py              # App URL routing
│   └── admin.py             # Admin panel configuration
│
├── db.sqlite3               # SQLite database file
├── manage.py                # Django's command-line utility
├── main.py                  # Additional application script
└── requirements.txt         # Python dependencies (to be created)
```

![Django Architecture](https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)
*Python Django backend architecture*

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Bibekbb/Electronic-Shop.git
   cd Electronic-Shop
   ```

2. **Create and activate a virtual environment**
   ```bash
   # On Windows
   python -m venv venv
   venv\Scripts\activate
   
   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install django
   # Add other dependencies as needed
   ```

4. **Set up the database**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (for admin access)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

7. **Access the application**
   - Open your browser and go to `http://127.0.0.1:8000/`
   - Admin panel: `http://127.0.0.1:8000/admin/`

## 📸 Application Screenshots

### Home Page
![Home Page](https://images.unsplash.com/photo-1472851294608-062f824d29cc?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

### Product Listing
![Products](https://images.unsplash.com/photo-1546868871-7041f2a55e12?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

### Shopping Cart
![Shopping Cart](https://images.unsplash.com/photo-1607082348824-0a96f2a4b9da?ixlib=rb-4.0.3&auto=format&fit=crop&w-800&q=80)

## 🔧 Key Components

### Database Models
The application likely includes models for:
- **User** (extending Django's built-in User model)
- **Product** (with fields like name, description, price, category, image)
- **Order** (linking users to products with order details)
- **Cart** (for temporary storage of selected items)
- **Category** (for organizing products)

### Main Views
- `HomeView` - Display featured products and categories
- `ProductListView` - Show all products with filtering options
- `ProductDetailView` - Detailed view of individual products
- `CartView` - Manage shopping cart items
- `CheckoutView` - Process orders and payments
- `OrderHistoryView` - Display user's past orders

## 🤝 Contributing

Contributions are welcome! To contribute to Sasto Pasal:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code follows Django best practices and includes appropriate tests.

## 🐛 Troubleshooting

### Common Issues

1. **Database migration errors**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

2. **Static files not loading**
   ```bash
   python manage.py collectstatic
   ```

3. **Port already in use**
   ```bash
   python manage.py runserver 8001  # Use a different port
   ```


## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Project Maintainer**: Bibekbb  
**GitHub**: [https://github.com/Bibekbb](https://github.com/Bibekbb)  
**Repository**: [https://github.com/Bibekbb/Electronic-Shop](https://github.com/Bibekbb/Electronic-Shop)

---

<div align="center">
  
### ⭐ If you find this project useful, please give it a star on GitHub!
  
*Last Updated: December 2024*
</div>

---
