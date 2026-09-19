# 📚 PustakSetu

### *Buy • Sell • Exchange • Give • Donate • Reuse*

> **PustakSetu is a digital platform for buying, selling, exchanging, giving away, and donating used educational resources.**

PustakSetu connects **students, sellers, donors, teachers, and NGOs** through a single platform so that useful educational resources can be reused instead of being wasted.

---

## 🎯 Vision

> **"Har useful educational resource ko waste hone se bachakar kisi aur learner tak pahunchana."**

PustakSetu aims to create a circular educational ecosystem:

```text
BUY
 ↓
READ
 ↓
REUSE
 ↓
EXCHANGE
 ↓
DONATE
 ↓
REACH ANOTHER LEARNER
```

---

# 🚀 Key Features

## 📚 1. Buy & Sell

Users can list and purchase second-hand educational resources.

### Seller can:

* Add books/resources
* Upload images
* Add title, author and ISBN
* Select edition
* Add original price
* Set selling price
* Select condition
* Add location
* Add description
* Manage listings

### Buyer can:

* Search resources
* Filter resources
* View resource details
* Contact seller
* Place orders
* Track orders
* Review transactions

---

## 🔄 2. Book Exchange

Users can exchange their books instead of selling them.

Example:

```text
My Book:
BCA DBMS

I Want:
BCA Operating System

        ↓

Exchange Request

        ↓

Accept / Reject
```

---

## 🎁 3. Free Books / Give Away

Users can list resources for free.

Available options:

```text
SELL
EXCHANGE
GIVE FREE
DONATE TO NGO
```

This allows students who cannot afford books to access educational resources.

---

# ❤️ 4. NGO Donation System

Donors can donate educational resources directly to verified NGOs.

### Donation Flow

```text
DONOR
  ↓
Select Resource
  ↓
Choose "Donate to NGO"
  ↓
NGO Matching
  ↓
NGO Request
  ↓
Donor Approval
  ↓
Donation Pickup / Delivery
  ↓
Donation Completed
```

NGOs can maintain their complete donation history.

---

# 🤝 5. Smart Donation Matching

NGOs can post their educational requirements.

Example:

```text
Class 6 Mathematics     → 30 Books
Class 8 Science         → 20 Books
English Grammar         → 15 Books
```

The system finds matching available resources and donors.

### Matching Flow

```text
NGO REQUIREMENT
       ↓
MATCHING ENGINE
       ↓
AVAILABLE RESOURCES
       ↓
DONORS
       ↓
NGO
```

---

# 🔎 6. Student Book Request

Students can request books that are currently unavailable.

Example:

```text
Required:
BCA 2nd Semester DBMS

Budget:
₹300

Condition:
Any
```

When a matching resource becomes available, the student can receive a notification.

---

# 🔖 7. Wishlist

Users can save resources for later.

### Features:

* Add/remove wishlist items
* Track availability
* Track price changes
* Get notification when matching resources are listed

---

# 💰 8. Smart Price Recommendation

The platform can recommend a suitable resale price based on:

* Original price
* Book condition
* Book age
* Edition
* Demand
* Other listing information

Example:

```text
Original Price: ₹600
Condition: Good
Age: 2 Years

Recommended Range:
₹150 - ₹220
```

> The recommended price is an assistance feature; the seller retains control over the final price.

---

# ⭐ 9. Book Condition System

Standardized resource conditions:

```text
🟢 Like New
🟢 Excellent
🟡 Good
🟠 Acceptable
🔴 Poor
```

Sellers can upload multiple photos to provide transparency about the resource's actual condition.

---

# 📍 10. Nearby Resources

Users can discover resources based on distance.

```text
Within 2 KM
Within 5 KM
Within 10 KM
```

This can support:

* Local pickup
* Local exchange
* Lower delivery costs
* Nearby donations

---

# 📦 11. Book Bundles

Sellers can combine multiple books into a single bundle.

Example:

```text
BCA 1st Semester Bundle

6 Books

Original Value: ₹2400
Bundle Price: ₹1000
```

Bundles can also be donated to NGOs or educational organizations.

---

# 🎓 12. User Verification

The platform can support verification for:

* Students
* Sellers
* NGOs

Verified accounts can receive badges such as:

```text
✓ Verified Student
✓ Verified Seller
✓ Verified NGO
```

This improves platform trust and helps reduce fraudulent activity.

---

# 🔗 13. QR Code & Unique Book ID

Every listed resource can receive a unique PustakSetu ID.

Example:

```text
PS-BK-000123
```

A QR code can point to the resource's public information page.

Possible information:

* Resource details
* Current status
* Reuse count
* Donation history
* Book journey

---

# ♻️ 14. Book Journey

PustakSetu can track the reuse journey of a resource.

Example:

```text
Rahul
  ↓
Bought Book
  ↓
Amit
  ↓
Used for 1 Year
  ↓
Donated
  ↓
NGO
  ↓
Student
```

Example platform message:

> ♻️ This book has been reused 4 times.

This feature highlights the social and environmental impact of reuse.

---

# 💝 15. Adopt / Sponsor a Student

Users can sponsor educational resources for students.

Example:

```text
Sponsor Class 10 Student

Required: ₹850
Funded:   ₹500
Remaining: ₹350
```

Sponsors can contribute toward books or educational resource bundles.

---

# 📖 16. Future Educational Resources

PustakSetu will initially focus on books.

Future categories can include:

```text
📚 Books
📝 Notes
📄 Study Material
✏️ Stationery
🎒 Bags
👕 School/College Uniforms
🧮 Calculators
🎓 Educational Kits
💻 Used Laptops
📱 Tablets
🔌 Educational Devices
```

---

# 👥 User Roles

| Role                  | Responsibilities                                                  |
| --------------------- | ----------------------------------------------------------------- |
| 👨‍🎓 Student / Buyer | Search, buy, exchange, request, wishlist                          |
| 👤 Seller             | List resources, set prices, manage listings                       |
| ❤️ Donor              | Donate or give away resources                                     |
| 🏢 NGO                | Post requirements, request and receive donations                  |
| 🛡️ Admin             | Verification, moderation, users, listings and platform management |

---

# 🏗️ System Architecture

```text
                         PUSTAKSETU
                              │
              ┌───────────────┼───────────────┐
              │               │               │
           STUDENTS         DONORS           NGOs
              │               │               │
              └───────────────┼───────────────┘
                              │
                       APPLICATION
                              │
       ┌─────────────┬────────┼────────┬─────────────┐
       │             │        │        │             │
    BUY/SELL      EXCHANGE   DONATE   REQUEST    WISHLIST
       │             │        │        │             │
       └─────────────┴────────┼────────┴─────────────┘
                              │
                       AI / MATCHING
                              │
                           BACKEND
                              │
                           DATABASE
                              │
                         ADMIN PANEL
                              │
                         DEVOPS / CLOUD
                              │
                         PRODUCTION
```

---

# 👨‍💻 Team & Responsibilities

## 🔧 Nikhil — Backend Developer

### Primary Responsibility

Design, develop and maintain the backend architecture and APIs.

### Tasks

* Backend architecture
* REST APIs
* Database integration
* Authentication
* Authorization
* User management APIs
* Book/resource APIs
* Buy/Sell APIs
* Order APIs
* Exchange APIs
* Donation APIs
* NGO APIs
* Book request APIs
* Wishlist APIs
* Notification APIs
* Review/rating APIs
* Admin APIs
* Input validation
* Error handling
* Backend security
* API documentation

### Suggested Backend Stack

```text
Node.js
Express.js
MongoDB / PostgreSQL
JWT / Session Authentication
REST API
```

---

# 🎨 Tejas — Frontend Developer

### Primary Responsibility

Design and develop the complete user-facing interface.

### Tasks

* UI/UX implementation
* Landing page
* Login/Register
* Browse Resources
* Search
* Filters
* Resource Details
* Buy/Sell UI
* Exchange UI
* Donation UI
* NGO interface
* Student Dashboard
* Seller Dashboard
* Donor Dashboard
* Admin Dashboard
* Wishlist
* Book Requests
* Notifications
* Profile
* Responsive design
* Accessibility
* Frontend API integration

### Suggested Frontend Stack

```text
HTML
CSS
JavaScript / TypeScript
React.js
Tailwind CSS / CSS
```

---

# 🤖☁️ You — AI + DevOps + Cloud

### Primary Responsibility

Build the intelligent features and manage deployment, automation, infrastructure and production environment.

## 🤖 AI Responsibilities

### 1. Smart Price Recommendation

Analyze resource information and provide a suggested resale price.

### 2. Smart Donation Matching

Match:

```text
NGO Requirements
       ↕
Available Resources
       ↕
Donors
```

### 3. Resource Recommendation

Recommend books/resources based on:

* User interests
* Search history
* Wishlist
* Category
* Previous interactions

### 4. Intelligent Search

Improve search using:

* Keywords
* Categories
* Authors
* ISBN
* Similar resources

### 5. Future AI Assistant

Possible assistant:

> "Mujhe BCA 2nd semester ki books ₹500 ke andar chahiye."

The assistant can help find suitable listings.

---

# ⚙️ DevOps Responsibilities

* Git/GitHub workflow
* Branch strategy
* Pull request workflow
* Dockerization
* Environment variables
* CI/CD pipeline
* Automated testing pipeline
* Build automation
* Deployment automation
* Logging
* Monitoring
* Error tracking
* Backup strategy
* Basic security
* Production configuration

---

# ☁️ Cloud Responsibilities

* Backend deployment
* Frontend deployment
* Database hosting
* Image/resource storage
* Domain configuration
* SSL/HTTPS
* Environment configuration
* Scaling
* Cloud monitoring
* Production infrastructure

### Possible Cloud Stack

```text
Cloud Provider
      ↓
Frontend Hosting
      ↓
Backend Server
      ↓
Database
      ↓
Object/File Storage
      ↓
Monitoring
```

The exact cloud provider can be selected during implementation based on project requirements and budget.

---

# 🔄 Team Development Workflow

```text
                 GitHub Repository
                         │
          ┌──────────────┼──────────────┐
          │              │              │
       Tejas          Nikhil           You
      Frontend       Backend       AI/DevOps/Cloud
          │              │              │
          └──────────────┼──────────────┘
                         │
                    Pull Request
                         ↓
                       Review
                         ↓
                      Testing
                         ↓
                     CI Pipeline
                         ↓
                     Build/Test
                         ↓
                    CD Pipeline
                         ↓
                     Deployment
                         ↓
                     Production
```

---

# 🌿 Suggested Git Branch Structure

```text
main
│
├── develop
│
├── feature/frontend
├── feature/backend
├── feature/ai
├── feature/devops
├── feature/cloud
│
└── hotfix
```

### Basic Workflow

```text
Create Branch
     ↓
Develop Feature
     ↓
Commit
     ↓
Push
     ↓
Pull Request
     ↓
Code Review
     ↓
Testing
     ↓
Merge
     ↓
CI/CD
     ↓
Deploy
```

---

# 🗄️ Database Modules

## Users

```text
User ID
Name
Email
Phone
Password Hash
Role
Location
Verification Status
Created At
```

## Resources

```text
Resource ID
Title
Category
Author
ISBN
Edition
Description
Condition
Original Price
Selling Price
Images
Location
Owner
Status
Created At
```

## Orders

```text
Order ID
Buyer
Seller
Resource
Price
Order Status
Payment Status
Created At
```

## Exchange

```text
Exchange ID
Owner
Offered Resource
Requested Resource
Request Status
Created At
```

## Donations

```text
Donation ID
Donor
NGO
Resource
Quantity
Donation Status
Created At
```

## NGOs

```text
NGO ID
NGO Name
Registration Details
Contact
Location
Verification Status
```

## NGO Requirements

```text
Requirement ID
NGO
Resource Category
Resource
Quantity
Priority
Status
```

## Wishlist

```text
Wishlist ID
User
Resource
Created At
```

## Book Requests

```text
Request ID
Student
Required Resource
Budget
Condition
Status
Created At
```

## Notifications

```text
Notification ID
User
Message
Type
Read/Unread
Created At
```

## Reviews

```text
Review ID
User
Target User
Order
Rating
Review
Created At
```

## Reports

```text
Report ID
Reporter
Reported User/Listing
Reason
Status
Created At
```

---

# 📱 Main Application Modules

## Public

```text
Home
Browse Resources
Search
Categories
NGOs
How It Works
About
Contact
```

## Student Dashboard

```text
Profile
Browse
My Orders
My Exchanges
My Requests
Wishlist
My Donations
Notifications
Chat
```

## Seller Dashboard

```text
Profile
Add Resource
My Listings
Orders
Exchange Requests
Messages
Reviews
```

## Donor Dashboard

```text
Donate Resource
My Donations
Donation Status
Donation History
NGO Requests
```

## NGO Dashboard

```text
NGO Profile
Requirements
Available Donations
Donation Requests
Received Resources
Donation History
Beneficiary Records
```

## Admin Dashboard

```text
Analytics
Users
Resources
Orders
Exchanges
Donations
NGOs
Verification
Reports
Complaints
Moderation
System Settings
```

---

# 🔐 Security Requirements

PustakSetu should implement:

* Secure authentication
* Password hashing
* JWT/session security
* Role-based access control
* Input validation
* API authorization
* Rate limiting
* Secure file uploads
* File type validation
* Environment variables for secrets
* HTTPS
* Database access controls
* Admin authorization
* Protection against common web vulnerabilities

---

# 📊 Admin Analytics

Admin dashboard can display:

```text
Total Users
Total Resources
Books Sold
Books Exchanged
Books Donated
Active NGOs
Completed Donations
Active Listings
Pending Requests
Reuse Count
```

Possible impact metrics:

```text
📚 Resources Reused
❤️ Resources Donated
♻️ Total Reuse Count
🏢 NGOs Connected
👨‍🎓 Students Helped
```

---

# 🧪 Testing

Testing should cover:

### Frontend

* UI testing
* Responsive testing
* Form validation
* User flows

### Backend

* API testing
* Authentication testing
* Authorization testing
* Database testing
* Error handling

### AI

* Recommendation testing
* Matching accuracy testing
* Edge cases
* Invalid input handling

### DevOps

* Build testing
* Deployment testing
* CI/CD testing
* Container testing

---

# 📈 Development Roadmap

## Phase 1 — Foundation

```text
✓ Project setup
✓ GitHub repository
✓ Database design
✓ Frontend setup
✓ Backend setup
✓ Authentication
✓ User roles
```

## Phase 2 — Core Marketplace

```text
✓ Add resources
✓ Browse resources
✓ Search
✓ Filters
✓ Resource details
✓ Buy/Sell
✓ Orders
```

## Phase 3 — Community Features

```text
✓ Exchange
✓ Free Books
✓ Wishlist
✓ Book Requests
✓ Reviews
✓ Nearby Resources
```

## Phase 4 — NGO & Donation

```text
✓ NGO registration
✓ NGO verification
✓ Donation system
✓ NGO requirements
✓ Donation requests
✓ Smart donation matching
✓ Donation history
```

## Phase 5 — AI

```text
✓ Price recommendation
✓ Resource recommendation
✓ Intelligent search
✓ Donation matching
✓ AI assistant
```

## Phase 6 — Advanced Features

```text
✓ QR Book ID
✓ Book Journey
✓ Reuse Counter
✓ Student Sponsorship
✓ Book Bundles
```

## Phase 7 — DevOps & Cloud

```text
✓ Docker
✓ CI/CD
✓ Cloud deployment
✓ Database hosting
✓ Storage
✓ Domain
✓ SSL
✓ Monitoring
✓ Logging
```

---

# 🌍 Future Scope

PustakSetu can evolve from a used-book platform into a complete **Educational Resource Reuse Ecosystem**.

```text
Books
  ↓
Notes
  ↓
Stationery
  ↓
Uniforms
  ↓
Educational Kits
  ↓
Calculators
  ↓
Laptops
  ↓
Tablets
  ↓
Other Educational Devices
```

The platform can eventually support schools, colleges, NGOs, libraries, student communities and educational organizations.

---

# 🧑‍💻 Project Team

| Member      | Role                          |
| ----------- | ----------------------------- |
| **Nikhil**  | Backend Developer             |
| **Tejas**   | Frontend Developer            |
| **Shikhar** | AI Developer + DevOps + Cloud |

---

# 🛠️ Proposed Technology Stack

```text
Frontend:
React.js
HTML5
CSS3
JavaScript / TypeScript

Backend:
Node.js
Express.js

Database:
MongoDB / PostgreSQL

AI:
Python
Machine Learning / Recommendation System
AI APIs where required

DevOps:
Git
GitHub
Docker
GitHub Actions
CI/CD

Cloud:
Cloud Hosting
Managed Database
Object Storage
Monitoring

Security:
JWT / Session Authentication
RBAC
HTTPS
Input Validation
Rate Limiting
```

---

# 📂 Proposed Repository Structure

```text
pustaksetu/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── layouts/
│       ├── services/
│       ├── hooks/
│       ├── utils/
│       └── assets/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── middleware/
│   │   ├── services/
│   │   ├── utils/
│   │   └── config/
│   └── tests/
│
├── ai/
│   ├── price-recommendation/
│   ├── donation-matching/
│   ├── recommendations/
│   └── search/
│
├── devops/
│   ├── docker/
│   ├── github-actions/
│   ├── deployment/
│   └── monitoring/
│
├── docs/
│   ├── architecture/
│   ├── api/
│   ├── database/
│   └── project-documentation/
│
├── .gitignore
├── docker-compose.yml
├── README.md
└── LICENSE
```

---

# 🤝 Contribution Guidelines

1. Create a feature branch.
2. Follow the assigned module responsibility.
3. Write clean and maintainable code.
4. Test the feature locally.
5. Commit with a meaningful message.
6. Push the branch.
7. Create a Pull Request.
8. Review and test before merging.

### Commit Examples

```text
feat: add book listing API
feat: create NGO donation dashboard
feat: implement exchange system
feat: add smart donation matching
fix: resolve authentication issue
docs: update API documentation
ci: configure GitHub Actions
```

---

# 📜 Project Status

🚧 **Currently in Development**

PustakSetu is being developed as a collaborative project with separate responsibilities for frontend, backend, AI, DevOps and Cloud.

---

# 🌱 PustakSetu

### **Buy. Sell. Exchange. Donate. Reuse.**

> **One resource can help more than one learner.**

