# **Node.js REST API Project**

## **Professional Backend System**  
A production-ready REST API built with Node.js, Express, and MongoDB, implementing modern backend development practices.

### 🔥 **Key Features**
- **Full CRUD Operations** with RESTful endpoints
- **JWT Authentication** with secure token handling
- **MongoDB Integration** using Mongoose ODM
- **TypeScript Support** for type-safe development
- **Middleware Pipeline** for request processing
- **Error Handling** with custom error classes
- **API Documentation** included

## 🛠 **Technical Stack**
| Component | Technology |
|-----------|------------|
| Runtime | Node.js 20 |
| Framework | Express.js |
| Database | MongoDB |
| ODM | Mongoose |
| Language | TypeScript |
| Testing | Jest |

## 📂 **Project Structure**
```
src/
├── controllers/    # Business logic
├── models/         # MongoDB schemas
├── routes/         # API endpoints
├── middleware/     # Custom middleware
├── utils/          # Helpers & config
├── types/          # TypeScript interfaces
└── app.ts          # Server entry point
```

## 🚀 **Getting Started**

### **Prerequisites**
- Node.js 18+
- MongoDB Atlas account or local instance
- Postman for API testing

### **Installation**
```bash
# Clone repository
git clone https://github.com/your-username/nodejs-api.git

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env
```

### **Running the Project**
```bash
# Development mode
npm run dev

# Production build
npm run build && npm start
```

## 📝 **API Documentation**
| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/auth/register` | POST | User registration |
| `/api/auth/login` | POST | User login |
| `/api/users` | GET | Get all users |
| `/api/users/:id` | GET | Get user by ID |
| `/api/users/:id` | PUT | Update user |
| `/api/users/:id` | DELETE | Delete user |

## 🔒 **Security Features**
- Password hashing with bcrypt
- JWT token authentication
- Rate limiting
- Request validation
- Helmet security headers

## 📜 **License**
MIT License - Free for personal and commercial use

---

**Note**: This project demonstrates professional Node.js backend development skills suitable for student portfolios and real-world applications. The clean architecture and modern practices make it production-ready while maintaining educational value.
