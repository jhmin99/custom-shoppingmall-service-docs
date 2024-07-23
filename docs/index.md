## Welcome to Docs

**Version: V0.1**

This allows you to customize your own shoppingmall application.

Custom-Shoppingmall-Service provides the following functionality:

Headless Project consists of the following components:

[Spring boot Java / Spring boot backend](https://github.com/jhmin99/custom-shoppingmall-service)    
React JS administration web application    
React JS front end application   

### Admin Page
- **User Management**
    - View user accounts.
    - Create, view, update, and delete admin accounts.
- **Category Management**
    - Create, view, update product categories.
    - Ensure items are correctly categorized.
    - Delete only if items are not assigned. 
- **Item Management**
    - Add new items, edit existing items, and mark items as invalid instead of deleting them.
    - Manage inventory levels and notify users who have signed up for stock alerts.
    - Notify users whenever items in their carts have been marked as invalid.
- **Coupon Management**
    - Create, update, delete, and assign coupons to users.
    - Track coupon usage and expiration dates.
- **Notice Management**
    - Post, edit, and delete public notices.
    - Ensure important information is communicated to users.
- **Review Management**
    - View, and delete user reviews.
    - Respond to user feedback.
- **Inquiry Management**
    - Manage customer and product inquiries.
    - Track inquiry status and respond to user questions.

### User Page
- **Registration**
    - Create a new user account.
    - Set up user profile.
- **Login / Logout**
    - Login:
        - Access account by entering credentials (username and password).
        - A secure authentication token (JWT) will be issued upon successful login.
    - Logout:
        - Securely log out of account to protect information.
        - Session will be cleared.
- **Mypage**
    - Manage personal information.
- **Notice**
    - View important announcements and updates.
- **Coupon**
    - View and manage available coupons.
    - Apply coupons during checkout for discounts.
- **Cart**
    - Add items to shopping cart.
    - Update item quantities and remove items from the cart.
- **WishList**
    - Add items to the wishlist for future reference.
    - Move items from the wishlist to the cart.
- **Review**
    - Write and submit reviews for purchased items.
    - Edit or delete existing reviews.
- **Inquiry**
    - Submit inquiries about products or general customer service questions.
    - Track the status of submitted inquiries.
- **Order**
    - Place new orders and track existing order status.
    - View order details.
- **Item**
    - Browse and search for products.
    - View detailed information and reviews for each product.


