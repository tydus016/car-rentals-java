# Car Rentals Windows Software Application
Tony's Garrage - Car Rentals is an Open Source online rental bookings application. It has two sides, one for customers and one for admin. Admins can create a listing for their available cars and label them such as for prices and images of the cars. Customers can place a booking request for the car/s of their choice. And can pay through bank transfer.

<p align="center"><img src="http://nextlvl.tech/assets/img/portfolio/tonys-featured.png" width="400"></p>

## Installation
<ol>
<li>Download or Clone this Repository</li>
<li>Import as Project in your IDE. preferably Apache Netbeans.</li>
<li>Clean and Build and run the project.</li>
</ol>

## To use it as full Admin Control
<ol>
<li>Download or Clone this <a href="https://github.com/tydus016/car-rentals-database" target="_blank">SQL tables Repository</a></li>
<li>Create new Database connection and import the tables.</li>
<li>Find these codes and replace it with your own database connection info.</li>
</ol>
   <img src="https://snipboard.io/n1tvsm.jpg">
   
 ## Short Code Documentation
 <ol>
 <li>User Registration - Every users has two account types in MYSQL users table. <b><i>account_type = 0 & account_type = 1</i></b> 0 is for regular users or customers and 1 is for admin users.<br>
 A user that register's through Register Frame is automatically marked as <b>account_type = 0</b> since it's only purpose if for customers who wants to register. When adding a new Admin acount, there are two ways on how to do it. The first way is to use the default admin account provided inside the SQL file we provided. <br><br>
 <b>Default Admin Account</b><br>
 Username: admin<br>
 Password: 123<br><br>
 And once you are in the Admin Dashboard, click the <b>Add new admin</b> button and fill up the form. The second way is to bypass to the <b>PHP my Admin database</b>
 directly and insert new data for <b>username and password</b> column and set the <b>account_type</b> to 1.
 </li>
 <li>
 User Login - The user login for both customer account and admin account is just one. The program will automatically detect which kind of account type is the user trying to login. Customer account will always redirect to Home Frame and for Admin account will also redirect to Admin dashboard. We do this because we dont want unauthorized users to get access to the Admin side of the application.
 </li>
 <br>
 The implemtation of the codes in this program is very precise, that everything you see in the GUI is easy to understand. Just explore!
 </ol>
 
  ## Renting Guide
  
  <img src="https://snipboard.io/e0tBOH.jpg">
  <ol>
  <li>Select a car type</li>
  <li>Select a car you like</li>
  <li>Click view details for to expand car information</li>
  <li>Click rent button</li>
  <li>Fill up the form data</li>
  <li>Click confirm details to see the final payment details.</li>
  <li>Select a payment type you like.</li>
  </ol>
   Once you successfully rent a car, you can view the information you rented under the dropdown account tab in the upper right and click history.
   
 ## Developer

This application is developed and powered by <a href="http://nextlvl.tech/" target="_blank">NEXT LEVEL TECHNOLOGY</a>. NEXT LEVEL TECHNOLOGY is a freelance Web / Software application servicing in affordable prices.
We also provide some open source application such as this one.

## License

Unless otherwise stated, next lvl technology and/or its licensors own the intellectual property rights for all material on next lvl tech. All intellectual property rights are reserved. You may access this from next lvl tech for your own personal use subjected to restrictions set in these terms and conditions.
<ul>
<li>Republish material from next lvl tech</li>
<li>Sell, rent or sub-license material from next lvl tech</li>
<li>Reproduce, duplicate or copy material from next lvl tech</li>
<li>Redistribute content from next lvl tech</li>
</ul>
