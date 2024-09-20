# Eccentric - E-Commerce Website

**Live Demo**: [Eccentric](https://alokgarg003.github.io/eccentric/)

## Project Overview

**Eccentric** is a modern eCommerce website that provides a seamless platform for users to browse and purchase electronic gadgets online. This project showcases a dynamic, responsive e-commerce experience using **HTML5**, **CSS**, and **JavaScript**, with interactive elements such as shopping cart management and smooth checkout processes. The website is designed to be intuitive, with clear navigation and a focus on user experience.

---

## Table of Contents

1. [Key Features](#key-features)
2. [Technologies Used](#technologies-used)
3. [Installation & Setup](#installation--setup)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Additional Information](#additional-information)
7. [Future Enhancements](#future-enhancements)
8. [Contributing](#contributing)

---

## Key Features

1. **Responsive Navigation Bar**:
   - Provides quick access to pages like Home, Products, Categories, About Us, Contact, and Cart.
   - Includes a search bar for easy product searches by name or ID.
   
2. **Product Browsing and Filtering**:
   - Users can browse products by category or search for specific items, enabling efficient exploration of electronics.

3. **Interactive Shopping Cart**:
   - Add items to the cart with the option to adjust quantities or remove products.
   - Real-time cart updates with price calculations and VAT inclusion.

4. **Smooth Checkout Process**:
   - Clean and simple checkout page that summarizes cart items and total costs.

5. **Order Confirmation Page**:
   - Provides users with a confirmation message post-purchase, displaying order details.

6. **User-Friendly Footer**:
   - Includes links to About, Offers, Contact Us, Support (FAQs, Terms & Conditions, Privacy Policy, etc.), and a “Back to top” button for easy navigation.

---

## Technologies Used

- **HTML5**:  
  Used for structuring the site and creating a clean, semantic layout.
  
- **CSS (Bootstrap & Custom CSS)**:  
  Bootstrap ensures responsive design, while custom CSS enhances the overall aesthetics and interactivity.
  
- **JavaScript (with jQuery and Popper.js)**:  
  Provides dynamic functionality like handling cart operations and interactive animations, making the shopping experience smoother.

- **Font Awesome**:  
  Icon library used for improving the visual design of buttons, navigation, and other elements.

---

## Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/alokgarg003/eccentric.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd eccentric
   ```

3. **Open the `index.html` File in a Browser**:
   Open the `index.html` file in any modern browser to run the e-commerce website locally.

---

## Usage

1. **Explore Products**:  
   Browse the product categories or use the search bar to find specific electronic items.

2. **Shopping Cart**:  
   Add desired products to your shopping cart, adjust quantities, and view the total price including VAT.

3. **Checkout**:  
   Once satisfied with the cart, proceed to the checkout page for a clean order summary and complete the purchase.

4. **Order Confirmation**:  
   Upon successful checkout, view the order confirmation page with a success message and order details.

---

## Project Structure

```plaintext
eccentric/
│
├── assets/                    # Contains static assets (images, styles)
│   ├── images/                # Product and UI images
│   └── css/                   # Stylesheets
│       └── style.css          # Main stylesheet
│
├── js/                        # JavaScript functionality
│   └── app.js                 # Handles cart logic, product interactions
│
├── README.md                  # Project documentation
├── index.html                 # Homepage
├── cart.html                  # Shopping cart page
├── checkout.html              # Checkout page
├── order_confirmation.html    # Post-purchase confirmation
├── category.html              # Product categories
├── product.html               # All products listing
├── product_detail.html        # Detailed view for a product
├── about.html                 # About Us page
├── contact.html               # Contact page
└── search.html                # Search results page
```

---

## Additional Information

### Shopping Cart Page

This page includes the following:
- A **cart section** displaying products added to the cart, including images, prices, and options to adjust quantities or remove items.
- A detailed **order summary** showing the total cost, including VAT, with a "Go to Checkout" button for final purchase.
- Bootstrap ensures the design is responsive and works well on mobile devices.

### Product Browsing Template

The homepage provides:
- A **carousel** for promotional content.
- Categories to browse products.
- A **Latest Products** section showcasing new arrivals.
- Highlighted features of the site, including free shipping, secure payment, and 24/7 support.

### Order Confirmation Page

Displays a confirmation message after successful purchase, with order details and a return link to the homepage.

### Use of jQuery and Popper.js

- **jQuery** simplifies DOM manipulation, making it easy to update cart contents dynamically.
- **Popper.js** ensures proper positioning of dropdowns, tooltips, and popovers, improving user interaction and experience.

---

## Future Enhancements

1. **User Authentication**:  
   Implement a user login/registration system for personalized shopping experiences and order tracking.

2. **Backend Integration**:  
   Incorporate a backend for handling user accounts, order history, and managing product inventory.

3. **Payment Gateway**:  
   Integrate popular payment gateways like PayPal and Stripe for a complete checkout experience.

4. **Mobile App Development**:  
   Expand the platform with a dedicated mobile application for on-the-go shopping.

---

## Contributing

Contributions to **Eccentric** are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

---



Enjoy exploring the **Eccentric** e-commerce platform! If you have any feedback or suggestions, please feel free to open an issue in the repository.
