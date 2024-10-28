# Online Shopping System

This project is a web-based online shopping system that includes both a user interface for customers and an advanced admin page for managing products, orders, and users.

Developed by [Aryan Kumar](https://github.com/aryankumar109).

## Prerequisites

To run this project locally, you will need:

- **XAMPP or WAMP**: Install either XAMPP or WAMP to set up a local server with Apache and MySQL.
- **Git (Optional)**: To clone the repository directly from GitHub.
- **Web Browser**: A modern browser like Chrome, Firefox, or Edge.
- **Basic PHP Knowledge** (optional but helpful): For troubleshooting or customization.

## Installation Steps

1. **Start Apache and MySQL**:
   - Open the XAMPP/WAMP control panel.
   - Start the Apache and MySQL services.

2. **Clone or Download the Project**:
   - Download the project from [GitHub - Online Shopping System](https://github.com/aryankumar109/online-shopping-system-with-advanced-admin-page).
   - Alternatively, clone the project:
     ```bash
     cd C:\xampp\htdocs\
     git clone https://github.com/aryankumar109/online-shopping-system-with-advanced-admin-page.git
     ```

3. **Set Up the Database**:
   - Open a browser and go to [phpMyAdmin](http://localhost/phpmyadmin).
   - Create a new database named `onlineshop`.
   - Select the database, go to **Import**, and upload the `onlineshop.sql` file from the project’s `database` directory.

4. **Access the Application**:
   - Go to [http://localhost/online-shopping-system-with-advanced-admin-page-master](http://localhost/online-shopping-system-with-advanced-admin-page-master) to view the app.
   - Register as a new user to explore features.

5. **Admin Login**:
   - Email: `admin@gmail.com` or Username: `admin`
   - Password: `123456789`

## Troubleshooting

### "Not Found" Error
1. **Verify Directory Path**: Ensure the project folder is located in `C:\xampp\htdocs\`.
2. **Check URL**: Ensure there are no typos in the URL.
3. **Restart Apache**: Restart Apache from the XAMPP control panel.

### Alternate Setup Options
If your project directory is outside `htdocs`, create an alias in Apache’s `httpd.conf`:
   ```apache
   Alias /online-shopping-system "C:/Users/pkpri/OneDrive/Documents/aryandp2/college_placement/project/clone/online-shopping-system"
   <Directory "C:/Users/pkpri/OneDrive/Documents/aryandp2/college_placement/project/clone/online-shopping-system">
       AllowOverride All
       Require all granted
   </Directory>
