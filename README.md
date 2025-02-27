# 🍹 JuiceBar

**JuiceBar** is a full-featured e-commerce website designed for ordering drinks online. It provides separate user interfaces for customers and the owner, allowing seamless order management and product administration.

---

## ✨ Features

### **User Interface (Customer Panel)**
- **Navigation Bar**: Includes Home, Orders, Signup, Cart, and Profile.
- **Home Page**:  
  - Displays available drink collections.  
  - Each collection redirects to its respective category page.  
  - Featured **offers section** and a promotional video.
- **Product Pages**:  
  - Each drink collection (e.g., Milkshakes) has a dedicated page.  
  - "Add to Cart" functionality for each item.
- **Cart Page**:  
  - Displays selected items with options to increase, decrease, or remove items.  
  - Shows details like item count, discounts, shipping charges, and total price.  
  - "Place Order" button redirects to the **Orders Page**.
- **Orders Page**:  
  - Displays previously placed orders with details like product name, price, quantity, and order time.  
  - A confirmation email is sent from `juicebarassist@gmail.com` to `juicebarhq@gmail.com` containing order details.
- **User Authentication**:  
  - **Login/Register** system.  
  - Profile section displaying username and email if logged in.  
  - Forgot Password functionality:  
    - User receives an OTP via email.  
    - After verification, they can reset their password.
- **Responsive Footer**: Includes contact details.

---

### **Owner Interface (Admin Panel)**
- **Dashboard for managing products and categories**.
- **Perform CRUD operations** on products:
  - Add, Update, Delete, and View products.
- Changes in the **Owner UI reflect automatically in the User UI**.

---

## 🔧 Tech Stack
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Authentication**: Django Authentication System
- **Email Service**: SMTP (for sending order confirmations and password reset emails)

---

## 🚀 Installation & Setup

### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/JuiceBar.git
cd JuiceBar
```

### **2. Set Up Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate   # For MacOS/Linux
venv\Scripts\activate      # For Windows
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Apply Migrations**
```bash
python manage.py migrate
```

### **5. Create Superuser (For Owner Dashboard Access)**
```bash
python manage.py createsuperuser
```

### **6. Run the Server**
```bash
python manage.py runserver
```
Now, visit `http://127.0.0.1:8000/` in your browser. 🎉  

---

## 📧 Contact
For any queries or issues, feel free to contact **juicebarhq@gmail.com**.
