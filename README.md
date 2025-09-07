# Blood Bank Management System

A comprehensive Django-based web application for managing blood donations, requests, and inventory in blood banks.

## 🏥 Overview

This Blood Bank Management System is a sophisticated web application built with Django that streamlines the entire process of blood donation and request management. The system provides distinct dashboards for administrators, donors, and patients with role-based access control.

## 🚀 Key Features

### Admin Panel
- Complete system oversight and management
- Approve/reject blood donation and request applications
- Manage donor and patient accounts
- Monitor real-time blood inventory across all blood groups
- Generate reports and view system statistics
- Organize blood camps and manage registrations
- Handle hospital and sponsor partnerships

### Donor Functionality
- Registration and profile management
- Blood donation requests with admin approval workflow
- Blood request capabilities for personal needs
- Downloadable PDF certificates for donations
- Donation and request history tracking
- Participation in blood camps

### Patient Functionality
- Easy registration and login
- Blood request submission
- Request status tracking
- Request history dashboard

## 🛠️ Technology Stack

- **Backend**: Django 4.2.16, Python
- **Database**: SQLite (default), PostgreSQL support
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 4.3.1
- **Libraries**: 
  - ReportLab 4.4.3 (PDF generation)
  - Pillow 11.3.0 (Image handling)
  - django-widget-tweaks 1.5.0 (Form styling)

## 📁 Project Structure

```
bloodbankmanagement/
├── blood/              # Main app for blood management
├── donor/              # Donor-specific functionality
├── patient/            # Patient-specific functionality
├── templates/          # HTML templates
├── static/             # CSS, JavaScript, images
└── manage.py           # Django management script
```

## 🎯 Getting Started

### Prerequisites
- Python 3.7+
- pip package manager

### Installation

1. Clone the repository:
   ```bash
   git clone <your-repository-url>
   cd blood-bank-management-system
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run database migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. Create a superuser (admin):
   ```bash
   python manage.py createsuperuser
   ```

5. Start the development server:
   ```bash
   python manage.py runserver
   ```

6. Access the application:
   - Main site: http://127.0.0.1:8000/
   - Admin panel: http://127.0.0.1:8000/admin/

## 🎨 UI/UX Features

- Modern, responsive design that works on all devices
- Dark/light theme support
- Intuitive navigation with role-based menus
- Interactive dashboards with statistics
- Professional healthcare-oriented interface

## 🔐 Security Features

- Django's built-in authentication system
- Role-based access control
- Form validation and sanitization
- CSRF protection

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **Asaad Siddiqui** - *Initial work* - [PixelDev](https://github.com/PixelDev)

## 🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## 📞 Support

For support, please open an issue in the repository or contact the maintainers.
