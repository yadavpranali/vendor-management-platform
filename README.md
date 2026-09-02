# Vendor Management System

A comprehensive vendor management platform for managing supplier relationships, orders, and procurement processes.

## 📋 Overview

The Vendor Management System is a web-based application designed to streamline vendor relationships and procurement operations. It provides tools for managing vendor information, tracking orders, handling payments, and maintaining communication with suppliers.

## 🛠️ Tech Stack

- **Python** - Backend logic and server processing
- **Django/Flask** - Web framework
- **HTML** - Frontend structure
- **CSS** - Styling and responsive design

## 📊 Project Statistics

- Python: ~15.1 KB

## 🎯 Features

- 👥 Vendor Database Management
- 📦 Purchase Order System
- 💳 Payment Tracking
- 📊 Performance Metrics
- 📧 Communication Tools
- 📈 Reporting & Analytics
- ⭐ Vendor Ratings
- 🔐 Secure Access Control
- 📱 Mobile Responsive
- 🔔 Real-time Notifications

## 🚀 Getting Started

### Prerequisites
- Python 3.6+
- pip
- Virtual environment

### Installation

```bash
# Clone the repository
git clone https://github.com/yadavpranali/VendorManagement_system.git
cd VendorManagement_system

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Setup database
python manage.py migrate

# Create admin account
python manage.py createsuperuser

# Run development server
python manage.py runserver
```

## 📁 Project Structure

```
VendorManagement_system/
├── manage.py
├── requirements.txt
├── vendor_system/       # Main project
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── vendors/             # Vendor management
├── orders/              # Purchase orders
├── payments/            # Payment tracking
├── reports/             # Analytics & reports
├── templates/           # HTML templates
├── static/              # CSS, JS, images
└── media/               # Document uploads
```

## 🔧 Key Modules

### Vendor Management
- Create and maintain vendor profiles
- Contact information
- Performance history
- Document storage

### Purchase Orders
- Create POs
- Track order status
- Manage delivery
- Handle returns

### Payment Management
- Invoice processing
- Payment scheduling
- Transaction tracking
- Payment history

### Performance Analysis
- Vendor rating system
- On-time delivery metrics
- Quality assessment
- Cost analysis

### Reporting
- Vendor performance reports
- Order history
- Payment analytics
- Procurement trends

## 📝 Usage Guide

### For Procurement Team

1. **Add Vendors**
   - Enter vendor information
   - Set payment terms
   - Upload documents

2. **Create Purchase Orders**
   - Select vendor
   - Add items and quantities
   - Set delivery date
   - Confirm order

3. **Track Orders**
   - Monitor delivery status
   - Manage communication
   - Handle issues

4. **Process Payments**
   - Review invoices
   - Approve payments
   - Track transactions

### For Vendors

1. **Profile Setup**
   - Create account
   - Add company details
   - Submit documentation

2. **View Orders**
   - See assigned orders
   - Update delivery status
   - Communicate with buyer

3. **Submit Invoices**
   - Generate invoices
   - Track payment status

## 🗄️ Database Models

### Vendor Model
```
- Company name
- Contact information
- Address
- Payment terms
- Rating
- Status
```

### PurchaseOrder Model
```
- Vendor reference
- Order date
- Delivery date
- Items
- Total amount
- Status
```

### Payment Model
```
- Order reference
- Amount
- Payment date
- Method
- Status
```

## 📊 Dashboard Features

- Pending orders
- Upcoming payments
- Vendor performance
- Key metrics
- Recent activities

## 🛡️ Security Features

- ✅ User authentication
- ✅ Role-based access control
- ✅ Secure document storage
- ✅ Audit trails
- ✅ Data encryption
- ✅ HTTPS support

## 📧 Communication

- Email notifications
- Message system
- Status alerts
- Report delivery

## 📈 Analytics & Reports

- Vendor performance analysis
- Cost trends
- Delivery performance
- Payment analytics
- Procurement metrics

## 🤝 Contributing

1. Fork the repository
2. Create feature branch
3. Make improvements
4. Submit pull request

## ⚙️ Configuration

Update `settings.py` with:
- Database credentials
- Email settings
- Payment gateway
- Document paths

## ⚡ API Endpoints (if applicable)

```
GET    /api/vendors/              - List vendors
POST   /api/vendors/              - Create vendor
GET    /api/orders/               - List orders
POST   /api/orders/               - Create order
GET    /api/payments/             - Payment history
```

## 📧 Support

For issues or questions:
- Create GitHub issues
- Contact support team
- Check documentation

## 📄 License

See LICENSE file for details.

---

**Optimizing Your Vendor Management! 🤝**
