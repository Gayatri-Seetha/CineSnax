# 🍿 CineSnax - Smart Snack Counter for Cinemas

CineSnax is a lightweight, offline-friendly web-based application designed to help cinema snack counters manage orders, track stock, and monitor earnings efficiently. This tool is ideal for staff to quickly process food orders, generate bills, and maintain inventory without requiring a backend server.


## 🚀 Features

* ✅ Order Billing – Generate instant bills for selected snacks and drinks with GST included.
* 📦 Stock Management – Add, update, or reset current stock levels via a staff dashboard.
* 📊 Earnings Tracking – Auto-calculate and display daily and monthly earnings.
* 🧾 Order History – View past orders with detailed bill links.
* 🔒 LocalStorage Based – All data is stored in the browser using localStorage.
* 🧹 Reset Control – One-click reset of all stored data including stock, earnings, and orders. It is controlled only by me.

# 📂 Project Structure
<pre>
📁 CineSnax-Kiosk
├── index.html           # Customer/Staff login page
├── customer.html        # Customer ordering interface
├── bill.html            # Bill summary with price breakdown
├── staff.html           # Staff dashboard (manage stock, view earnings)
├── orders.html          # Order history (view past orders, earnings)
├── reset.html           # Reset confirmation page (clear all local data)
├── Images               # Product images (popcorn, fries, beverages, etc.)
└── README.md            # Project documentation (description, usage, credits)
</pre>


📦 Tech Stack

* HTML5
* CSS3 (with Google Fonts - Poppins)
* JavaScript (Vanilla JS + localStorage API)

# 🛠️ How to Use

1. Open **`index.html`** in your browser.
2. Select snack items and quantity, enter customer name and mobile.
3. Submit to generate the bill (`bill.html`) and store order details.
4. Staff can:

   * View all orders in `orders.html`
   * Manage stock in `staff.html`

> **Note:** All data is saved in the browser. Refreshing will keep data, but clearing browser storage or cache will remove it.

# 📌 Known Limitations

* Not connected to a real backend or database.
* No authentication (designed for use in a trusted local environment).
* Works only in the browser where the orders were placed (localStorage-based).


# 👩‍💻 Developed By

**Sri Gayatri Seetha**

B.Tech CSE | Student | Aspiring Software Developer

