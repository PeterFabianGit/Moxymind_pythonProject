# SauceDemo Test Suite

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
# SauceDemo Test Suite

This repository contains a set of automated tests for the main functionalities of the [SauceDemo website](https://www.saucedemo.com/). The tests are implemented using Selenium and pytest.

## Test Cases

### 1. Login with Correct Credentials
- **Why**: Ensures that users can log in successfully with valid credentials, which is critical for accessing the main functionalities of the site.
- **Steps**:
  1. Navigate to the login page.
  2. Enter valid username and password.
  3. Click the login button.
  4. Verify successful login by checking for the presence of the inventory page.

### 2. Login with Incorrect Credentials
- **Why**: Ensures that the system prevents unauthorized access by rejecting invalid credentials.
- **Steps**:
  1. Navigate to the login page.
  2. Enter invalid username and password.
  3. Click the login button.
  4. Verify that an error message is displayed.

### 3. Add Item to Cart
- **Why**: Adding items to the cart is fundamental for e-commerce functionality. Users must be able to add products to their cart to proceed with purchases.
- **Steps**:
  1. Log in with valid credentials.
  2. Add an item to the cart from the inventory page.
  3. Verify that the item count in the cart icon increments.

### 4. Checkout Functionality
- **Why**: Ensures that users can log out successfully, which is important for security and session management.
- **Steps**:
  1. Log in with valid credentials.
  2. Click the menu button.
  3. Click the logout link.
  4. Verify that the user is redirected to the login page.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/PeterFabianGit/Moxymind_pythonProject.git
   
