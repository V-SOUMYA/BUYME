# BUYME – Online Shoe Auction Platform 👟

BUYME is a full-stack web application designed for hosting and managing online auctions specifically for shoes. The platform supports multiple user roles including buyers, sellers, customer representatives, and administrators, each with tailored functionalities. Built using **HTML, CSS, JavaScript**, and **MySQL, Node.js, Express.js**, the application is locally hosted and provides a responsive, real-time auction experience.

---

## Features

### 1. User Authentication
- **Signup Page**: Users can register by providing their full name, email, password, and selecting a role (buyer/seller).
- **Login Page**: Authenticates users using email and password. Role-based redirection is implemented.

---

### 2. Buyer Functionality
- **Landing Page**: Clean parallax design with an engaging UI.
- **Start Bidding**: Buyers can view:
  - Ongoing Auctions
  - Completed Auctions
- **Auction Detail Page**:
  - Product photo and detailed description
  - Categories (e.g., Men's, Sneakers, Heels, etc.)
  - Current and previous top 2 bids
- **Profile Section**:
  - Reset password
  - Delete account
  - View/Delete bid history
- **Contact Section**:
  - Social media links
  - Address information
  - Query submission form

---

### 3. Seller Functionality
- Upon login, sellers have access to:
  - **Add Item**: Input all product details including brand, size, material, etc.
  - **Manage Listings**: View, edit, delete products or create auctions.
  - **View Bids**:
    - Ongoing Auctions: Shows current highest bidder.
    - Completed Auctions: Displays final winner and bid details.

---

### 4. Customer Representative
- Preconfigured in SQL with direct login access.
- Can view and respond to queries submitted via the Contact form.
- Responses are reflected on the buyer’s user page.

**Login Credentials**:  
`Email`: rep@gmail.com  
`Password`: 1234

---

### 5. Admin Dashboard
- Centralized control panel for platform administration.
- **Features**:
  - **Dashboard (admin_dashboard.html)**:
    - Quick access cards to different tools.
  - **User Management** (`userlist.html`):
    - View and delete registered users.
  - **Product Management** (`shoelist.html`):
    - Edit/delete all listings.
  - **Bid Tracking** (`viewbids.html`):
    - Ongoing vs. completed auctions
    - Bidding history
    - Winner identification
  - **Auction Monitoring** (`auction.html`)
  - **Sales Analysis** (`sales_report.html`):
    - Total earnings
    - Best-selling items
    - Top buyers

**Admin Login**:  
`Email`: admin@gmail.com  
`Password`: 1234

---

## Tech Stack

| Layer       | Technology               |
|-------------|--------------------------|
| Frontend    | HTML, CSS, JavaScript    |
| Backend     | Node.js / Express (optional custom server) |
| Database    | MySQL                    |
| Hosting     | Localhost (Web + SQL)    |
| Fonts       | Google Fonts             |

---

## Database Design

- Users Table (includes roles)
- Product Listings Table
- Auctions Table
- Bids Table
- Queries Table
- Responses Table

(Relational schema with foreign key constraints)

---


