# RADHIKA FABRIC - Online Fabric Store

An e-commerce web application designed for online selling and management of fabrics. Built with ASP.NET, C#, and SQL Server backend.

## 📋 Project Overview

RADHIKA FABRIC is a comprehensive fabric e-commerce platform that provides both customer-facing features and administrative controls for managing products, users, purchases, and feedback.

**Language Composition:**
- HTML: 44.6%
- ASP.NET: 41%
- C#: 14.4%

## ✨ Features

### Customer Features
- **Product Browsing** - Browse fabric products with detailed descriptions
- **Product Search & Filtering** - Easy navigation through product catalog
- **Shopping Cart** - Add and manage products in cart
- **User Registration & Login** - Secure user authentication
- **Order Management** - Track and manage purchases
- **Feedback System** - Submit and view product feedback
- **Contact & Support** - Get in touch with the business

### Admin Features
- **Product Management** - Add, edit, delete products
- **User Management** - Manage customer registrations and logins
- **Purchase Tracking** - Monitor all customer purchases
- **Feedback Monitoring** - Review and manage customer feedback
- **Inventory Control** - Manage product inventory

## 🏗️ Technology Stack

- **Frontend**: HTML, ASPX (ASP.NET)
- **Backend**: C#, ASP.NET
- **Database**: SQL Server (RADHIKA.mdf)
- **Configuration**: web.config

## 📁 Project Structure

```
RADHIKA-FABRIC/
├── Frontend Pages
│   ├── index.html              # Landing page
│   ├── about.html              # About us page
│   ├── contact.html            # Contact page
│   ├── faq.html                # FAQ page
│   ├── products.html           # Product listing
│   ├── product-detail.html     # Product details
│   └── sign-in.html / sign-up.html  # Authentication
│
├── ASP.NET Pages (Customer)
│   ├── home.aspx               # Dashboard
│   ├── product.aspx            # Product page
│   ├── addtocart.aspx          # Add to cart
│   ├── viewcart.aspx           # View cart
│   ├── registration.aspx       # User registration
│   ├── signin.aspx             # User login
│   ├── feedback.aspx           # Submit feedback
│   └── contact.aspx            # Contact form
│
├── Admin Pages
│   ├── productmaster.aspx      # Product management
│   ├── productinsert.aspx      # Add new product
│   ├── productedit.aspx        # Edit product
│   ├── productdelete.aspx      # Delete product
│   ├── registrationmaster.aspx # User management
│   ├── loginmaster.aspx        # Login management
│   ├── purchasemaster.aspx     # Purchase tracking
│   └── feedbackmaster.aspx     # Feedback management
│
├── Master Pages
│   ├── clientMasterPage.master       # Client layout
│   ├── adminMasterPage.master        # Admin layout
│   └── *.master.cs                   # Code-behind files
│
├── Code-Behind
│   └── *.aspx.cs                     # C# code-behind files
│
├── Database
│   ├── RADHIKA.mdf                   # SQL Server database
│   └── RADHIKA_Log.LDF               # Database log file
│
├── Configuration
│   └── web.config                    # Application configuration
│
└── Documentation
    └── *.docx                        # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Visual Studio 2015 or higher
- .NET Framework 4.5 or above
- SQL Server 2012 or higher
- IIS (Internet Information Services)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/shreya22456/RADHIKA-FABRIC.git
   cd RADHIKA-FABRIC
   ```

2. **Set Up Database**
   - Attach `RADHIKA.mdf` to your SQL Server instance
   - Configure connection string in `web.config`

3. **Configure IIS**
   - Create a new Application in IIS
   - Point to the project directory
   - Set application pool to .NET Framework v4.x

4. **Run the Application**
   - Open in Visual Studio
   - Build the solution
   - Run (F5 or Ctrl+F5)

## 📝 Key Pages

| Page | URL | Purpose |
|------|-----|---------|
| Home | `home.aspx` | Customer dashboard |
| Products | `product.aspx` | Product listing and details |
| Cart | `viewcart.aspx` | Shopping cart management |
| Register | `registration.aspx` | User registration |
| Login | `signin.aspx` | User authentication |
| Feedback | `feedback.aspx` | Customer feedback submission |
| Admin Products | `productmaster.aspx` | Admin product management |
| Admin Users | `registrationmaster.aspx` | Admin user management |

## 🔐 Security Features

- User authentication and authorization
- Secure login system
- Admin-only access to management pages
- Input validation and error handling

## 💾 Database Schema

The SQL Server database includes tables for:
- Users (Registration & Login)
- Products
- Shopping Cart
- Purchases
- Feedback

## 🛠️ Development

### Building the Project
```bash
# In Visual Studio
Build > Build Solution (Ctrl+Shift+B)
```

### Running Tests
- Test user registration and login
- Test product browsing and cart functionality
- Test admin management features

## 📚 Documentation

Additional documentation files are included:
- `2_title.docx` - Project title page
- `3_Certificate.docx` - Project certification
- `4_preface.docx` - Project preface
- `5_Index.docx` - Project index
- `6_final.docx` - Complete project documentation

## 👥 User Roles

### Customer
- Browse products
- Create account
- Add items to cart
- Make purchases
- Submit feedback
- View order history

### Administrator
- Manage all products
- Manage user accounts
- Track purchases
- Review feedback
- Manage inventory

## 📞 Support

For issues, questions, or feedback, please contact through:
- Contact form: `contact.aspx`
- Email: (Add your contact email)
- Issue tracker: GitHub Issues

## 📄 Template Information

This project uses an HTML template from Tooplate.com. The template can be modified for personal or commercial use, but redistribution of the original template files is not permitted.

## 📅 Project Timeline

- **Created**: March 27, 2025
- **Last Updated**: March 27, 2025
- **Status**: Active

## 📜 License

Please refer to the repository for license information or contact the repository owner.

## 👨‍💻 Author

- **GitHub**: [@shreya22456](https://github.com/shreya22456)

---

**Happy Fabric Shopping! 🧵**
