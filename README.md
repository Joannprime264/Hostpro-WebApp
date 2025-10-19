<div align="right">

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Ryan-infitech.Hostpro-WebApp)

</div>

# 🎓 Hostpro - Learning & Professional Development Platform

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node](https://img.shields.io/badge/node-%3E%3D20.0.0-brightgreen)
![Next.js](https://img.shields.io/badge/Next.js-13.5.1-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.2.2-blue)

**Hostpro** adalah platform pembelajaran online dan pengembangan profesional yang menyediakan kursus berkualitas, sistem booking untuk event, serta layanan mentor untuk membantu pengembangan karir dan skill profesional.

> 📢 **Repository Notice**: Repository ini adalah **preview-only** untuk keperluan informasi publik tentang platform Hostpro. Dokumentasi lengkap dan source code bersifat privat untuk menjaga keamanan dan integritas platform.

---

## 📋 Daftar Isi

- [Tentang Platform](#-tentang-platform)
- [Fitur Utama](#-fitur-utama)
- [Demo & Preview](#-demo--preview)
- [Tech Stack](#-tech-stack)
- [Arsitektur Sistem](#-arsitektur-sistem)
- [Database Schema](#-database-schema)
- [Keamanan & Privacy](#-keamanan--privacy)
- [Screenshots](#-screenshots)
- [FAQ](#-faq-frequently-asked-questions)
- [Roadmap](#-roadmap)
- [Acknowledgments](#-acknowledgments)
- [License](#-license)
- [Contact & Support](#-contact--support)

---

## 🎯 Tentang Platform

**Hostpro** adalah platform pembelajaran online dan pengembangan profesional yang komprehensif, dirancang untuk membantu individu meningkatkan keterampilan mereka melalui kursus berkualitas tinggi, mentoring personal, dan layanan booking event profesional.

### 🌐 Platform URLs

- **Production**: [https://hostpro.id](https://hostpro.id)
- **Preview/Testing**: [https://devhostpro.vercel.app](https://devhostpro.vercel.app)

### 🎓 Visi & Misi

**Visi**: Menjadi platform pembelajaran online terdepan yang mengintegrasikan pendidikan, mentoring, dan layanan profesional dalam satu ekosistem yang komprehensif.

**Misi**:

- Menyediakan akses pendidikan berkualitas untuk semua kalangan
- Menghubungkan learner dengan mentor profesional terbaik
- Memfasilitasi layanan event management yang profesional
- Menciptakan komunitas pembelajaran yang aktif dan supportif

---

## ✨ Fitur Utama

### 🎯 Platform Pembelajaran

- **Kursus Online Interaktif**

  - Video pembelajaran berkualitas HD
  - Modul pembelajaran terstruktur
  - Progress tracking otomatis
  - Sertifikat penyelesaian

- **Sistem Enrollment**

  - Pendaftaran kursus mudah
  - Payment gateway terintegrasi (Midtrans)
  - Akses lifetime setelah pembelian
  - Pembelajaran self-paced

- **Mentor System**
  - Profil mentor profesional
  - Rating & review system
  - Direct messaging dengan mentor
  - Live session scheduling

### 📅 Booking Management

- **Event Booking**

  - Master of Ceremony (MC) booking
  - Event Organizer (EO) services
  - Portfolio showcase
  - Real-time availability check

- **Admin Dashboard**
  - Booking management
  - Status tracking (Pending, Confirmed, Completed)
  - Client information management
  - Revenue analytics

### 💳 Payment Integration

- **Midtrans Integration**
  - Multiple payment methods (Bank Transfer, E-Wallet, Credit Card)
  - Secure payment processing
  - Automatic payment verification
  - Transaction history

### 👤 User Management

- **Multi-Role Authentication**

  - Role-based access control (SUPER_ADMIN, ADMIN, MENTOR, USER)
  - Email verification
  - Google OAuth integration
  - Password reset flow

- **User Profile**
  - Customizable profile
  - Social media links
  - Professional information
  - Activity history

### 💬 Real-time Communication

- **Live Chat System**
  - WebSocket dengan Socket.io
  - End-to-end encryption
  - Typing indicators
  - Read receipts
  - File sharing

### 📊 Analytics & Monitoring

- **Dashboard Analytics**

  - User statistics
  - Course enrollment trends
  - Revenue reports
  - Booking metrics

- **Live Monitoring**
  - Real-time user activity
  - Session tracking
  - Geographic insights
  - Device & browser analytics

### 📝 Content Management

- **Article System**

  - Blog/Article publishing
  - Rich text editor
  - SEO optimization
  - Comments & likes

- **Custom Pages**
  - Dynamic page builder
  - SEO-friendly URLs
  - Media management

### 🔔 Notification System

- **Multi-channel Notifications**
  - In-app notifications
  - Email notifications
  - Push notifications (planned)
  - Notification preferences

---

## 🎬 Demo & Preview

### 🌐 Live Platform

| Environment         | URL                                                            | Status     |
| ------------------- | -------------------------------------------------------------- | ---------- |
| **Production**      | [https://hostpro.id](https://hostpro.id)                       | 🟢 Live    |
| **Preview/Testing** | [https://devhostpro.vercel.app](https://devhostpro.vercel.app) | 🟡 Testing |

### 🔐 Demo Access (Preview Environment)

Untuk mencoba platform pada environment testing, gunakan kredensial berikut:

**Admin Dashboard Access**

```
Email    : admin01@gmail.com
Password : A-admin01
URL      : https://devhostpro.vercel.app/admin
```

> ⚠️ **Catatan**: Demo credentials hanya untuk testing environment. Jangan gunakan data sensitif atau personal.

### ✨ Apa yang Bisa Dicoba?

#### Sebagai Admin:

- ✅ Dashboard analytics & statistics
- ✅ User management & role assignment
- ✅ Course & content management
- ✅ Booking & transaction monitoring
- ✅ System configuration
- ✅ Live activity monitoring

#### Sebagai User (Registrasi Gratis):

- ✅ Browse courses & content
- ✅ Enroll dalam kursus
- ✅ Track learning progress
- ✅ Booking event services (MC/EO)
- ✅ Real-time chat dengan mentor
- ✅ Review & rating system

---

## 🛠 Tech Stack

### Frontend Technologies

| Technology                   | Version  | Description                       | Use Case                        |
| ---------------------------- | -------- | --------------------------------- | ------------------------------- |
| **Next.js**                  | 13.5.1   | React framework dengan App Router | SSR, SSG, Routing, API Routes   |
| **React**                    | 18.2.0   | UI library                        | Component-based UI              |
| **TypeScript**               | 5.2.2    | Type-safe JavaScript              | Type safety & better DX         |
| **Tailwind CSS**             | 3.3.3    | Utility-first CSS framework       | Styling & responsive design     |
| **Shadcn/ui**                | Latest   | Component library (Radix UI)      | Pre-built accessible components |
| **Radix UI**                 | Latest   | Unstyled UI primitives            | Accessible component foundation |
| **Socket.io Client**         | 4.8.1    | Real-time communication           | Live chat & notifications       |
| **React Hook Form**          | 7.53.0   | Form management                   | Form handling & validation      |
| **Zod**                      | 3.23.8   | Schema validation                 | Runtime type validation         |
| **SWR**                      | 2.3.6    | Data fetching & caching           | API data management             |
| **Axios**                    | Latest   | HTTP client                       | API requests                    |
| **Lucide React**             | 0.446.0  | Icon library                      | Modern icons                    |
| **date-fns**                 | 3.6.0    | Date utility library              | Date manipulation               |
| **React Icons**              | 5.5.0    | Icon collection                   | Additional icons                |
| **Sonner**                   | 1.5.0    | Toast notifications               | User feedback                   |
| **Next Themes**              | 0.3.0    | Theme management                  | Dark/Light mode                 |
| **Class Variance Authority** | 0.7.0    | CSS variants                      | Component styling               |
| **clsx**                     | 2.1.1    | Conditional classes               | Dynamic className               |
| **Tailwind Merge**           | 2.5.2    | Merge Tailwind classes            | Class conflict resolution       |
| **Recharts**                 | 2.15.4   | Chart library                     | Data visualization              |
| **Embla Carousel**           | 8.3.0    | Carousel component                | Image/content slider            |
| **React Day Picker**         | 8.10.1   | Date picker                       | Date selection                  |
| **Input OTP**                | 1.2.4    | OTP input component               | Verification codes              |
| **Validator**                | 13.15.15 | String validation                 | Input validation                |
| **Vaul**                     | 0.9.9    | Drawer component                  | Mobile-friendly drawers         |
| **cmdk**                     | 1.0.0    | Command menu                      | Command palette                 |

### Backend Technologies

| Technology              | Version | Description                   | Use Case                 |
| ----------------------- | ------- | ----------------------------- | ------------------------ |
| **Node.js**             | ≥20.0.0 | JavaScript runtime            | Server-side execution    |
| **Express.js**          | 5.1.0   | Web framework                 | REST API & routing       |
| **TypeScript**          | 5.9.3   | Type-safe JavaScript          | Type safety & better DX  |
| **Prisma**              | 6.17.1  | ORM & database toolkit        | Database management      |
| **PostgreSQL**          | Latest  | Relational database           | Primary data storage     |
| **Socket.io**           | 4.8.1   | WebSocket server              | Real-time communication  |
| **JWT**                 | 9.0.2   | Authentication                | Token-based auth         |
| **Bcrypt**              | 3.0.2   | Password hashing              | Secure password storage  |
| **Nodemailer**          | 7.0.6   | Email service                 | Email sending            |
| **Cloudinary**          | 2.7.0   | Media storage                 | Image/video management   |
| **Multer**              | 2.0.2   | File upload                   | Multipart form data      |
| **Helmet**              | 8.1.0   | Security middleware           | HTTP security headers    |
| **CORS**                | 2.8.5   | Cross-origin resource sharing | CORS configuration       |
| **Express Rate Limit**  | 8.1.0   | Rate limiting                 | API throttling           |
| **Class Validator**     | 0.14.2  | Validation decorators         | DTO validation           |
| **Class Transformer**   | 0.5.1   | Object transformation         | DTO transformation       |
| **Zod**                 | 4.1.12  | Schema validation             | Runtime validation       |
| **Winston**             | 3.18.3  | Logging library               | Application logging      |
| **Node Cron**           | 4.2.1   | Scheduled tasks               | Cron jobs                |
| **UUID**                | 13.0.0  | UUID generator                | Unique identifiers       |
| **Sanitize HTML**       | 2.17.0  | HTML sanitization             | XSS protection           |
| **DOMPurify**           | 3.1.6   | DOM sanitization              | Content sanitization     |
| **JSDOM**               | 24.1.0  | DOM implementation            | Server-side DOM          |
| **Axios**               | 1.12.2  | HTTP client                   | External API calls       |
| **File Type**           | 21.0.0  | File type detection           | MIME type validation     |
| **GeoIP Lite**          | 1.4.10  | IP geolocation                | Location tracking        |
| **UA Parser**           | 2.0.5   | User agent parsing            | Device detection         |
| **Streamifier**         | 0.1.1   | Stream conversion             | Buffer to stream         |
| **Google Auth Library** | 10.4.0  | Google OAuth                  | Google authentication    |
| **Resend**              | 6.1.3   | Email API                     | Modern email service     |
| **Supabase JS**         | 2.47.7  | Supabase client               | Database client          |
| **dotenv**              | 17.2.3  | Environment variables         | Configuration management |

### Database & Storage

| Service        | Purpose            | Description                      |
| -------------- | ------------------ | -------------------------------- |
| **PostgreSQL** | Primary Database   | Relational database via Supabase |
| **Prisma ORM** | Database Toolkit   | Type-safe database access        |
| **Supabase**   | Database Hosting   | Managed PostgreSQL + features    |
| **Cloudinary** | Media Storage      | Cloud-based media management     |
| **Redis**      | Caching (Optional) | In-memory data store             |

### External Services & APIs

| Service            | Purpose          | Integration                 |
| ------------------ | ---------------- | --------------------------- |
| **Midtrans**       | Payment Gateway  | Multiple payment methods    |
| **Google OAuth**   | Social Login     | OAuth 2.0 authentication    |
| **Gmail SMTP**     | Email Service    | Transactional emails        |
| **Cloudinary API** | Media Management | Upload, transform, deliver  |
| **Resend API**     | Email Delivery   | Modern email infrastructure |

### DevOps & Deployment

| Tool/Service       | Purpose          | Description                  |
| ------------------ | ---------------- | ---------------------------- |
| **Git**            | Version Control  | Source code management       |
| **GitHub**         | Code Repository  | Code hosting & collaboration |
| **Vercel**         | Frontend Hosting | Next.js deployment platform  |
| **Railway**        | Backend Hosting  | Node.js/Express deployment   |
| **Supabase**       | Database Hosting | PostgreSQL as a service      |
| **GitHub Actions** | CI/CD            | Automated workflows          |
| **ESLint**         | Code Linting     | Code quality enforcement     |
| **Prettier**       | Code Formatting  | Code style consistency       |
| **TypeScript**     | Type Checking    | Static type validation       |

### Development Tools

| Tool                       | Purpose              | Description                     |
| -------------------------- | -------------------- | ------------------------------- |
| **tsx**                    | TypeScript Execution | Run TS files directly           |
| **Prisma Studio**          | Database GUI         | Visual database editor          |
| **Postman/Thunder Client** | API Testing          | REST API testing                |
| **VS Code**                | Code Editor          | Primary development environment |
| **Prisma Migrate**         | Schema Migration     | Database version control        |

### Security & Monitoring

| Technology             | Purpose            | Implementation              |
| ---------------------- | ------------------ | --------------------------- |
| **JWT Tokens**         | Authentication     | Secure token-based auth     |
| **Bcrypt**             | Password Hashing   | One-way password encryption |
| **Helmet**             | HTTP Security      | Security headers            |
| **CORS**               | Cross-Origin       | Resource sharing control    |
| **Rate Limiting**      | DDoS Protection    | Request throttling          |
| **Input Validation**   | Data Sanitization  | Prevent injection attacks   |
| **HTTPS/SSL**          | Transport Security | Encrypted communication     |
| **Session Management** | Access Control     | User session tracking       |

---

## 🏗 Arsitektur Sistem

```
┌─────────────────────────────────────────────────────────────┐
│                        CLIENT LAYER                          │
├─────────────────────────────────────────────────────────────┤
│  Next.js App Router (SSR/SSG)                                │
│  ├── Public Pages (/, /courses, /about)                     │
│  ├── Auth Pages (/login, /register)                         │
│  ├── User Dashboard (/dashboard/*)                          │
│  ├── Admin Panel (/admin/*)                                 │
│  └── Mentor Portal (/mentor/*)                              │
└─────────────────────────────────────────────────────────────┘
                            ↕ HTTPS
┌─────────────────────────────────────────────────────────────┐
│                      API GATEWAY                             │
├─────────────────────────────────────────────────────────────┤
│  Express.js Server                                           │
│  ├── Authentication Middleware (JWT)                         │
│  ├── Authorization (RBAC)                                    │
│  ├── Rate Limiting                                           │
│  ├── Request Validation                                      │
│  └── Error Handling                                          │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                     SERVICE LAYER                            │
├─────────────────────────────────────────────────────────────┤
│  Business Logic & Controllers                                │
│  ├── Auth Service (Login, Register, OAuth)                  │
│  ├── Course Service (CRUD, Enrollment)                      │
│  ├── Booking Service (Event Management)                     │
│  ├── Payment Service (Midtrans Integration)                 │
│  ├── Chat Service (WebSocket)                               │
│  └── Notification Service (Email, In-app)                   │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                    DATA LAYER                                │
├─────────────────────────────────────────────────────────────┤
│  Prisma ORM                                                  │
│  ├── Query Optimization                                      │
│  ├── Transaction Management                                  │
│  └── Connection Pooling                                      │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                  EXTERNAL SERVICES                           │
├─────────────────────────────────────────────────────────────┤
│  ├── PostgreSQL (Supabase) - Primary Database               │
│  ├── Cloudinary - Media Storage & CDN                       │
│  ├── Midtrans - Payment Gateway                             │
│  ├── Gmail SMTP - Email Service                             │
│  └── Google OAuth - Social Authentication                   │
└─────────────────────────────────────────────────────────────┘
```

---

## 🗄 Database Schema

### Core Tables

- **users** - User accounts & authentication
- **profiles** - User profile information
- **sessions** - Active user sessions
- **courses** - Course catalog
- **modules** - Course modules
- **lessons** - Individual lessons
- **enrollments** - User course enrollments
- **lesson_progress** - Progress tracking
- **course_reviews** - Course ratings & reviews
- **bookings** - Event bookings
- **transactions** - Payment transactions
- **chat_rooms** - Chat conversations
- **chat_messages** - Chat messages (encrypted)
- **notifications** - User notifications
- **articles** - Blog/News articles
- **activity_logs** - User activity tracking

### ER Diagram

```
┌─────────────┐         ┌──────────────┐         ┌─────────────┐
│    User     │────────>│   Profile    │         │   Session   │
└─────────────┘         └──────────────┘         └─────────────┘
      │                                                   │
      │                                                   │
      ├──────────────────┬────────────────┬──────────────┤
      │                  │                │              │
      ▼                  ▼                ▼              ▼
┌─────────────┐   ┌─────────────┐  ┌────────────┐  ┌────────────┐
│ Enrollment  │   │   Booking   │  │Transaction │  │Notification│
└─────────────┘   └─────────────┘  └────────────┘  └────────────┘
      │                  │                │
      │                  │                │
      ▼                  │                │
┌─────────────┐          │                │
│   Course    │──────────┼────────────────┘
└─────────────┘          │
      │                  │
      │                  │
      ▼                  ▼
┌─────────────┐   ┌─────────────┐
│   Module    │   │   Payment   │
└─────────────┘   └─────────────┘
      │
      │
      ▼
┌─────────────┐
│   Lesson    │
└─────────────┘
```

### Key Relationships

- **User** has one **Profile**
- **User** has many **Sessions**
- **User** has many **Enrollments**
- **Course** has many **Modules**
- **Module** has many **Lessons**
- **Enrollment** tracks **Lesson Progress**
- **Booking** has one **Transaction**

---

## 🔒 Keamanan & Privacy

### Keamanan Data

Platform Hostpro menerapkan standar keamanan tertinggi untuk melindungi data pengguna:

- **🔐 Encryption**:
  - End-to-end encryption untuk chat messages
  - HTTPS/SSL untuk semua komunikasi
  - Password hashing dengan bcrypt
- **🛡️ Authentication**:

  - JWT-based authentication
  - Multi-factor authentication (planned)
  - Google OAuth integration
  - Session management & monitoring

- **🔒 Authorization**:

  - Role-based access control (RBAC)
  - Fine-grained permissions
  - API rate limiting
  - Request validation

- **📊 Monitoring**:
  - Real-time activity logging
  - Suspicious activity detection
  - Automated security alerts
  - Regular security audits

### Privacy Policy

Kami sangat serius dalam menjaga privasi pengguna:

- ✅ Data pengguna tidak akan dijual ke pihak ketiga
- ✅ Penggunaan data sesuai dengan kebijakan yang jelas
- ✅ User memiliki kontrol penuh atas data pribadi
- ✅ Compliant dengan regulasi perlindungan data
- ✅ Transparent data collection & usage

### Payment Security

- 💳 Payment gateway yang terverifikasi (Midtrans)
- 🔐 PCI DSS compliant
- 🛡️ Secure transaction processing
- 📧 Email confirmation untuk setiap transaksi
- 🔄 Automatic fraud detection

---

## � Screenshots

### Homepage

Platform landing page dengan informasi lengkap tentang layanan yang tersedia.

![Homepage Preview](docs/screenshots/homepage.png)

### Course Catalog

Jelajahi berbagai kursus dengan filtering berdasarkan kategori, level, dan rating.

![Course Catalog](docs/screenshots/courses.png)

### Learning Dashboard

Dashboard pembelajaran dengan progress tracking dan akses ke materi kursus.

![Learning Dashboard](docs/screenshots/dashboard.png)

### Admin Panel

Admin dashboard dengan analytics, user management, dan monitoring system.

![Admin Panel](docs/screenshots/admin.png)

### Booking System

Sistem booking untuk layanan MC dan Event Organizer.

![Booking System](docs/screenshots/booking.png)

### Real-time Chat

Live chat dengan end-to-end encryption untuk komunikasi dengan mentor.

![Chat System](docs/screenshots/chat.png)

---

## ❓ FAQ (Frequently Asked Questions)

### Tentang Platform

**Q: Apa itu Hostpro?**  
A: Hostpro adalah platform pembelajaran online yang mengintegrasikan kursus, mentoring, dan layanan event management profesional dalam satu ekosistem.

**Q: Apakah gratis untuk mendaftar?**  
A: Ya, registrasi di Hostpro sepenuhnya gratis. Anda hanya perlu membayar untuk kursus berbayar atau layanan booking yang Anda gunakan.

**Q: Apakah sertifikat yang diberikan resmi?**  
A: Ya, setiap kursus yang diselesaikan akan mendapatkan sertifikat digital yang dapat diverifikasi.

### Pembelajaran

**Q: Berapa lama akses kursus setelah pembelian?**  
A: Akses kursus bersifat lifetime. Anda dapat belajar kapan saja dengan kecepatan Anda sendiri.

**Q: Apakah bisa berkomunikasi langsung dengan mentor?**  
A: Ya, platform menyediakan fitur live chat untuk komunikasi langsung dengan mentor.

**Q: Bagaimana cara track progress pembelajaran?**  
A: System otomatis melacak progress Anda di setiap lesson dan menampilkannya di dashboard.

### Payment & Booking

**Q: Metode pembayaran apa saja yang diterima?**  
A: Kami menerima Bank Transfer, E-Wallet (GoPay, OVO, Dana), dan Credit Card melalui Midtrans.

**Q: Apakah pembayaran aman?**  
A: Ya, semua transaksi diproses melalui Midtrans yang telah terverifikasi dan PCI DSS compliant.

**Q: Bagaimana proses booking untuk layanan MC/EO?**  
A: Pilih layanan → Isi detail event → Submit booking → Konfirmasi admin → Payment → Booking confirmed.

### Teknis

**Q: Browser apa yang didukung?**  
A: Platform mendukung semua modern browsers (Chrome, Firefox, Safari, Edge) versi terbaru.

**Q: Apakah ada aplikasi mobile?**  
A: Saat ini platform berbasis web responsive. Aplikasi mobile native sedang dalam tahap development (Q1 2026).

**Q: Bagaimana jika lupa password?**  
A: Gunakan fitur "Forgot Password" di halaman login untuk reset password melalui email.

---

## 📄 License

Project ini dilisensikan di bawah **MIT License**.

Copyright (c) 2025 Hostpro - Infitech Development Team

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## 📞 Contact & Support

### 🌐 Platform

- **Website**: [https://hostpro.id](https://hostpro.id)
- **Email**: support@hostpro.id
- **Social Media**: Follow us for updates and news

### 👨‍💻 Developer Team

**Infitech Development Team**

- Email: dev@infitech.id
- GitHub: [@Ryan-infitech](https://github.com/Ryan-infitech)
- Website: [https://infitech.id](https://infitech.id)

### 🔗 Project Links

- **Repository**: [https://github.com/Ryan-infitech/Hostpro](https://github.com/Ryan-infitech/Hostpro)
- **Issues**: [Report bugs or request features](https://github.com/Ryan-infitech/Hostpro/issues)
- **Discussions**: [Join community discussions](https://github.com/Ryan-infitech/Hostpro/discussions)

### 💬 Community & Support

Butuh bantuan atau ada pertanyaan? Kami siap membantu!

- 📧 Email: support@hostpro.id
- 💬 Live Chat: Available di platform
- 📱 WhatsApp: +62 812-3456-7890

---

## 🙏 Acknowledgments

Terima kasih kepada:

- [Next.js](https://nextjs.org/) - React Framework
- [Express.js](https://expressjs.com/) - Node.js Framework
- [Prisma](https://www.prisma.io/) - Database ORM
- [Shadcn/ui](https://ui.shadcn.com/) - UI Components
- [Tailwind CSS](https://tailwindcss.com/) - CSS Framework
- [Supabase](https://supabase.com/) - Database Hosting
- [Vercel](https://vercel.com/) - Frontend Hosting
- [Railway](https://railway.app/) - Backend Hosting
- [Cloudinary](https://cloudinary.com/) - Media Management
- [Midtrans](https://midtrans.com/) - Payment Gateway

---

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/Ryan-infitech/Hostpro?style=social)
![GitHub forks](https://img.shields.io/github/forks/Ryan-infitech/Hostpro?style=social)
![GitHub issues](https://img.shields.io/github/issues/Ryan-infitech/Hostpro)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Ryan-infitech/Hostpro)

---

## 🗺 Roadmap

### Q4 2025

- [x] Core authentication system
- [x] Course management
- [x] Booking system
- [x] Payment integration
- [x] Real-time chat
- [x] Admin dashboard

### Q1 2026

- [ ] Mobile app (React Native)
- [ ] Advanced analytics
- [ ] AI-powered recommendations
- [ ] Video streaming optimization
- [ ] Multi-language support

### Q2 2026

- [ ] Live streaming classes
- [ ] Certificate automation
- [ ] Affiliate program
- [ ] Advanced reporting
- [ ] API for third-party integration

### Future

- [ ] Mobile apps (iOS/Android)
- [ ] AI chatbot support
- [ ] Blockchain certificates
- [ ] Subscription plans
- [ ] Marketplace integration

---

<div align="center">

## 🎉 Bergabung dengan Hostpro

**Mulai perjalanan pembelajaran Anda hari ini!**

[![Visit Website](https://img.shields.io/badge/🌐_Visit_Website-hostpro.id-blue?style=for-the-badge)](https://hostpro.id)
[![Try Demo](https://img.shields.io/badge/🧪_Try_Demo-devhostpro.vercel.app-green?style=for-the-badge)](https://devhostpro.vercel.app)
[![GitHub](https://img.shields.io/badge/⭐_Star_on_GitHub-Ryan--infitech/Hostpro-yellow?style=for-the-badge)](https://github.com/Ryan-infitech/Hostpro)

---

### 💡 Kenapa Memilih Hostpro?

| Feature                   | Benefit                                                 |
| ------------------------- | ------------------------------------------------------- |
| 🎓 **Kursus Berkualitas** | Materi pembelajaran terstruktur dari mentor profesional |
| 💰 **Harga Terjangkau**   | Investasi pendidikan dengan nilai terbaik               |
| ⏰ **Fleksibel**          | Belajar kapan saja, di mana saja sesuai jadwal Anda     |
| 🏆 **Sertifikat Resmi**   | Tingkatkan nilai CV dengan sertifikat terverifikasi     |
| 💬 **Mentor Support**     | Bantuan langsung dari mentor berpengalaman              |
| 📱 **User Friendly**      | Interface modern dan mudah digunakan                    |

---

### 🤝 Untuk Developer

Repository ini bersifat **preview-only** untuk menampilkan informasi platform kepada publik.

Tertarik untuk berkontribusi atau berkolaborasi?

- 📧 Email: dev@infitech.id
- 💼 LinkedIn: Connect with us
- 🐛 Issues: [Report bugs](https://github.com/Ryan-infitech/Hostpro/issues)

---

### ⭐ Support Project

Jika Anda menyukai project ini, berikan ⭐ star di GitHub!

© 2025 Hostpro. All rights reserved.

[⬆ Back to Top](#-hostpro---learning--professional-development-platform)

</div>
