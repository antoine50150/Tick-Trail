# User Manual - Tick&Trail

## Version 3.7

### Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Features](#features)
4. [FAQ](#faq)
5. [Support](#support)

---

### I. Introduction

**Tick&Trail** is a software solution designed to simplify train route selection across specific cities in France. It allows users to choose their desired routes via dedicated terminals located in select train stations. This user manual will guide you through installing the project, creating an account, booking a route, and managing your reservations.

---

### II. Installation

**Step 1: Retrieve the Project**

You can obtain the Tick&Trail project in two ways:

- **Using Git**:  
  Clone the project repository using the following command:  
  ```bash
  git clone https://github.com/tick-trail-projet/tick-trail.git
  ```

- **Direct Download**:  
  Download the project as a ZIP file:  
  [Download Tick&Trail](https://github.com/tick-trail-projet/tick-trail/archive/refs/heads/main.zip)

**Step 2: Install Java and Maven**

The project runs on **Java 18** and uses **Maven** to manage dependencies.

- **Java 18**: Download and install Java from the following link:  
  [Download Java 18](https://www.oracle.com/java/technologies/javase/jdk18-archive-downloads.html)

- **Maven**: Ensure Maven is installed to handle project libraries:  
  [Maven Installation Guide](https://maven.apache.org/docs/3.8.6/release-notes.html)

**Step 3: Set Up the Database**

To configure the database:

1. Download the `ticktrail.sql` file.
2. Import the SQL file into **phpMyAdmin** or your preferred MySQL management tool.

For additional help, consult this video tutorial:  
[How to Create and Host a Database on Your Computer](https://www.youtube.com/watch?v=IEdmATIA4g&ab_channel=CyberSoftCreation.fr)

---

### III. Features

1. **Account Creation**  
   To start using Tick&Trail, click on the “Register” button and fill in the necessary details to create your account.

2. **Logging In**  
   Once your account is created, click “Log in” and enter your registered email and password. Be sure to click "Log out" after each session for security.

3. **Booking a Train Route**  
   - Select your **departure** and **arrival** stations.
   - Choose your **departure date**.
   - Click “Search” to view available routes, then select your preferred option.
   - Complete your booking by confirming the details and clicking "Book."

4. **Viewing Reservations**  
   In the “My Reservations” tab, you can view all your current and past reservations. You can check the status and details of each reservation.

5. **Canceling a Reservation**  
   To cancel a reservation, go to “My Reservations,” select the reservation you wish to cancel, and click "Delete."

6. **Updating Account Information**  
   You can update your personal details by navigating to the “My Account” section. After filling in your new information, click "Edit" to save changes. All updates will be reflected in the system database.

---

### IV. FAQ

**1. Error at launch**

Make sure that:
- Java 18 and Maven are correctly installed on your system.
- The database is running and accessible.

**2. Do I need to import the `TickTrail.sql` file every time I use the software?**

No, you only need to import the `TickTrail.sql` file once during the initial setup. After that, your data and routes will remain intact.

**3. Is it necessary to run the database before each use?**

Yes, for Tick&Trail to function properly, you need to start your database server each time you use the software.

**4. Can I retrieve my data from another computer?**

No, the data is stored on a local or hosted database. To access your data on another computer, the database must be connected to the internet and accessible remotely.

**5. I can't create an account**

Double-check that the email address you’re entering is valid and hasn't already been used. If problems persist, contact the database administrator for help.

**6. I can't log in**

Ensure your login credentials are correct. The email should be in the format `yourname@domain.com`, and the password must contain at least one uppercase letter, a number, and a special character. If you're still unable to log in, contact the database administrator for assistance.

**7. I can't book a route**

Verify that your account details are correct and that the routes you're searching for are available. If the issue persists, ask the administrator to check the database.

**8. I can't view my reservations**

First, ensure that you are logged in. If you're logged in but still can't view your reservations, confirm that you completed the booking process by clicking "Pay" during reservation.

**9. I can't update my account information**

Ensure that the new information is different from your previous data and that you've clicked "Edit" to save the changes. Contact support if the issue continues.

**10. I can't log out**

Double-check that you're logged in and click "Log out" in the top-right corner of the screen. If the issue persists, refresh the page and try again.

---
