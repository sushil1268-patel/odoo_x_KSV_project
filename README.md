# 🏢 VendorBridge - Enterprise Procurement ERP System

![Version](https://img.shields.io/badge/version-4.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-stable-brightgreen)

A complete, production-ready Procurement & Vendor Management ERP system with role-based dashboards, real-time data persistence, and professional invoice generation. Built with pure HTML, CSS, and JavaScript - no backend required!

## ✨ Features

### 🎯 Core Functionality
- **Vendor Management** - Register, track, and manage vendor profiles with GST details
- **RFQ Management** - Create and manage Request for Quotations with budgets and deadlines
- **Quotation System** - Vendors can submit bids with pricing and delivery timelines
- **Quotation Comparison** - Side-by-side comparison to select the best vendor
- **Approval Workflow** - Multi-level approval system (MD/CEO final approval)
- **Purchase Orders** - Auto-generate POs from approved quotations
- **Invoice Generation** - Professional PDF invoices with GST calculations
- **Email Integration** - Send invoices directly to vendors
- **Activity Logs** - Complete audit trail of all actions
- **Reports & Analytics** - Exportable CSV reports with charts

### 👥 Role-Based Dashboards

| Role | Access Level | Dashboard Features |
|------|--------------|-------------------|
| **MD** | Full Control | Bar charts, Vendor metrics, Strategic reports, Complete system access |
| **CEO** | Executive View | Doughnut charts, Spend analysis, KPIs, Financial overview, Final approvals |
| **Procurement Officer** | Operational | Create RFQs, Manage vendors, Compare quotes, Generate POs |
| **Vendor** | Limited Access | View RFQs, Submit quotations, Track orders, Download invoices |

### 🎨 UI/UX Features
- Modern glass-morphism design
- Responsive layout (desktop & tablet)
- Smooth animations and transitions
- Interactive charts (Chart.js)
- Toast notifications
- Professional invoice templates

## 📋 Demo Credentials

### 👑 Management Team
| Role | Name | Email | Password |
|------|------|-------|----------|
| MD | Sushil Patel | `sushil@vendorbridge.com` | `sushil@MD123` |
| CEO | Prins Gajera | `prins@vendorbridge.com` | `prins@CEO123` |
| Procurement Officer | Karan Jethava | `karan@vendorbridge.com` | `karan@PO123` |

### 🏪 Vendor Partners
| Company | Email | Password |
|---------|-------|----------|
| TechNova Solutions | `tech@novasolutions.com` | `vendor123` |
| GlobalSoft Pvt Ltd | `global@soft.com` | `vendor123` |
| OfficeMart | `office@mart.com` | `vendor123` |

## 🚀 Installation

### Local Setup
1. **Clone the repository**
```bash
git clone https://github.com/yourusername/vendorbridge-erp.git
cd vendorbridge-erp
```

2. **Open the application**
```bash
# Simply open index.html in your browser
# OR use a local server
npx serve .
# or
python -m http.server 8000
```

3. **Start using**
   - Navigate to `http://localhost:8000`
   - Use demo credentials above
   - No database setup required!

### Deployment
Deploy to any static hosting service:
- **GitHub Pages** - Push to repository and enable Pages
- **Netlify** - Drag and drop the folder
- **Vercel** - `vercel --prod`
- **AWS S3** - Upload static files

## 🛠️ Tech Stack

- **HTML5** - Structure
- **CSS3** - Styling, animations, responsive design
- **JavaScript (ES6+)** - Logic, data management
- **Chart.js** - Interactive charts and graphs
- **html2pdf.js** - PDF invoice generation
- **Font Awesome 6** - Icons
- **Google Fonts (Inter)** - Typography

## 📊 Key Workflows

### Complete Procurement Cycle
```
1. Procurement Officer → Create RFQ
2. Vendors → Submit Quotations
3. Procurement Officer → Compare & Select
4. MD/CEO → Approve Purchase Order
5. System → Auto-generate Invoice
6. Procurement Officer → Download/Email Invoice
```

### Invoice Generation
- Professional PDF with company branding
- Automatic GST calculation (18%)
- Bill-to details from vendor profile
- Unique invoice numbers
- Download and email capabilities

## 🎯 Use Cases

- **Small to Medium Enterprises** - Complete procurement management
- **Educational Institutions** - Vendor and purchase management
- **Non-Profit Organizations** - Transparent procurement tracking
- **Startups** - Cost-effective ERP solution
- **Training/Demo** - Learn ERP workflows

## 🔐 Security Features

- Role-based access control
- Session management
- Password-protected logins
- Audit trail of all activities
- No sensitive data exposed to servers

### Modifying Invoice Template
Edit the `invoiceHTML` variable in `downloadInvoice()` function

## 📱 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 60+ | ✅ Full |
| Firefox | 60+ | ✅ Full |
| Safari | 12+ | ✅ Full |
| Edge | 79+ | ✅ Full |
| Opera | 50+ | ✅ Full |

## 🐛 Known Issues & Solutions

| Issue | Solution |
|-------|----------|
| localStorage full | Clear browser cache |
| PDF not downloading | Check browser permissions |
| Charts not loading | Update Chart.js CDN |
| Vendor login fails | Ensure email matches registered vendor |

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` file for more information.

## 📧 Contact

**Project Link:** [https://github.com/yourusername/vendorbridge-erp](https://github.com/yourusername/vendorbridge-erp)

**Demo:** [Live Demo URL](your-demo-link)

## 🙏 Acknowledgments

- Chart.js team for beautiful charts
- html2pdf.js for PDF generation
- Font Awesome for icons
- Google Fonts for Inter typeface

## 🎯 Roadmap

- [ ] Dark mode support
- [ ] Multi-language support
- [ ] Email notifications (SMTP integration)
- [ ] Advanced analytics dashboard
- [ ] Vendor rating system
- [ ] Contract management module
- [ ] Budget tracking
- [ ] Mobile app (React Native)
- [ ] API endpoints for integration
- [ ] Cloud sync capability

## 💡 Tips

1. **First Login** - Use MD credentials to see full system
2. **Test Workflow** - Create RFQ → Login as Vendor → Submit Quote → Login as MD → Approve
3. **Data Backup** - Export localStorage data regularly
4. **Customization** - Modify sample data in loadData() function

## ⚡ Quick Start Guide

```bash
# 1. Download the file
wget https://raw.githubusercontent.com/yourusername/vendorbridge-erp/main/index.html

# 2. Open in browser
open index.html

# 3. Login with any demo credential
# Email: sushil@vendorbridge.com
# Password: sushil@MD123

# 4. Start managing procurement!
```

---

**⭐ Star this repository if you find it useful!**

Built with ❤️ for modern enterprise procurement management
