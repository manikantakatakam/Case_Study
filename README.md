# Testing Scenarios for Online Bookstore Application
## User Authentication:
### Preconditions:
- Online Bookstore application is accessible.
- No existing user account with the test credentials.
### Scenario 1: User Registration
**Objective:** To verify users can create accounts successfully.

**Test Steps:**
1. Navigate to the registration page.
2. Enter valid registration information (username, email, password).
3. Submit the registration form.
4. Check for a confirmation message indicating successful registration.

**Expected Results:** 
- User should be able to register successfully.

---

### Scenario 2: User Login
**Objective:** To verify users can log in with their credentials.

**Test Steps:**
1. Navigate to the login page.
2. Enter valid login credentials.
3. Submit the login form.
4. Verify user is redirected to the homepage/dashboard.

**Expected Results:** 
- User should be able to log in successfully.

---

### Scenario 3: Password Reset
**Objective:** To verify users can reset their passwords.

**Test Steps:**
1. Navigate to the password reset page.
2. Enter the email associated with the account.
3. Check email for password reset link.
4. Click on the password reset link and follow instructions.
5. Set a new password.
6. Attempt to log in with the new password.

**Expected Results:** 
- User should be able to reset password and log in with the new password.

---

## Book Catalog:
### Preconditions:
- Online Bookstore application is accessible.
### Scenario 1: Browsing Catalog
**Objective:** To verify users can browse the catalog of available books.

**Test Steps:**
1. Navigate to the book catalog page.
2. Verify that books are displayed with details such as title, author, price, and availability.

**Expected Results:** 
- Users should be able to see a list of available books with relevant details.

---

### Scenario 2: Searching for Books
**Objective:** To verify users can search for books by title or author.

**Test Steps:**
1. Enter a book title or author name in the search bar.
2. Submit the search query.
3. Verify that relevant books are displayed based on the search criteria.

**Expected Results:** 
- Users should be able to find books by searching with title or author.

---

## Shopping Cart:
### Preconditions:
- Online Bookstore application is accessible.
### Scenario 1: Adding Items to Cart
**Objective:** To verify users can add books to their shopping cart.

**Test Steps:**
1. Click on the "Add to Cart" button for a book.
2. Verify that the book is added to the shopping cart.

**Expected Results:** 
- Book should be added to the shopping cart successfully.

---

### Scenario 2: Removing Items from Cart
**Objective:** To verify users can remove items from their shopping cart.

**Test Steps:**
1. Navigate to the shopping cart page.
2. Click on the "Remove" button for a book.
3. Verify that the book is removed from the shopping cart.

**Expected Results:** 
- Book should be removed from the shopping cart successfully.

---

### Scenario 2: Updating items
**Objective:** To verify users can increase or decrease quanntity in their shopping cart.

**Test Steps:**
1. Navigate to the shopping cart page.
2. Click on the plus button to increase quantity.
3. Verify that the quantity is updated.

**Expected Results:** 
- Quantity of books in cart should be updated as user's selection.

---

## Checkout:
### Preconditions:
- Online Bookstore application is accessible.
### Scenario 1: Proceeding to Checkout
**Objective:** To verify users can proceed to checkout.

**Test Steps:**
1. Navigate to the checkout page.
2. Verify that the selected items are displayed along with the total price.
3. Enter shipping information.
4. Click on the "Proceed to Checkout" button.

**Expected Results:** 
- User should be able to proceed to checkout successfully.

---

### Scenario 2: Total Order Amount Calculation
**Objective:** To verify the system calculates the total order amount correctly.

**Test Steps:**
1. Add multiple items to the shopping cart.
2. Proceed to checkout.
3. Verify that the total order amount is calculated accurately.

**Expected Results:** 
- Total order amount should be calculated correctly based on the selected items' prices.

---

## Order Confirmation:
### Preconditions:
- Online Bookstore application is accessible.
- Make sure that users mail is actively working.
### Scenario 1: Order Confirmation Email
**Objective:** To verify users receive an order confirmation email after a successful purchase.

**Test Steps:**
1. Complete a successful purchase.
2. Check the registered email inbox for an order confirmation email.

**Expected Results:** 
- User should receive an order confirmation email after a successful purchase.

---

### Scenario 2: Order Storage
**Objective:** To verify that orders are stored in the database for reference.

**Test Steps:**
1. Complete a successful purchase.
2. Verify that the order details are stored in the database.

**Expected Results:** 
- Order details should be stored in the database for reference.

---

## User Interface:
### Preconditions:
- Online Bookstore application is accessible.
### Scenario 1: UI Intuitiveness
**Objective:** To verify that the UI is intuitive and user-friendly.

**Test Steps:**
1. Navigate through different pages and features of the application.
2. Observe the layout, design, and navigational elements.

**Expected Results:** 
- UI should be intuitive, easy to navigate, and aesthetically pleasing.

---

### Scenario 2: Error Message Display
**Objective:** To verify that error messages are displayed appropriately.

**Test Steps:**
1. Submit forms with invalid inputs.
2. Verify that appropriate error messages are displayed.

**Expected Results:** 
- Error messages should be displayed clearly and specifically indicating the issue.

---

### Scenario 3: Browser Compatibility
**Objective:** To verify compatibility across different browsers.

**Test Steps:**
1. Access the application using different browsers (e.g., Chrome, Firefox, Safari).
2. Test various features and functionalities.

**Expected Results:** 
- Application should function correctly across all supported browsers.

