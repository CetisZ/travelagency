# travelagency
Ceti's Travel Agency Project

Project's First Pahse
Topic 1: Frontend static side, Creation of an HTML/JavaScript/CSS based Website.

Description
Design and Construct a prototype website for the "Travel Experts" travel agency. 
Focused on producing HTML pages with Cascading Stylesheet and Javascript enhancements.  

Deliverables
1a.	A "Main" page that welcomes the customer to the website and provides links and menus to the other pages.
1b. A “Contact Us” page that has information about how to phone, email, or go to the agency.
1c.	A “Customer Registration” page that allows a customer to set up an account with Travel Experts by entering: 
    their name, address (city, province, country, and postal code), email address, home phone number, business phone number, user ID, and password. 
    “Contact Us” page information is then used, after verification, to establish an account for future orders.
1d.	A “Vacation Package” page listing all vacation packages available.  
    This is a static page at this time and is enhanced later to be dynamically generated from a database.
    

Project's Second Pahse
Topic 2: Backend server side, Processing entry data with Node.js, local and cloud MongoDB database server.

Description
Node.js scripts provides dynamic generation of the web pages developed earlier (First Phase), as well as capturing form data from customers.
The following documents are used to dynamically enhance the functionality of web pages:
---	Packages
---	Products
---	Suppliers
---	Products_suppiers
---	Packages_products_suppliers
---	Agencies
---	Agents
---	Customers
---	Bookings

Deliverables
2a.	Customers make a booking for only one package per booking
2b.	When a package is set up, the price is never changed

Suggested features that were built during this project's phase
2.c	Modified the web page that lists the packages available.  
2.c.1 Inserted code that read the database and generated the package list from the travel package table, instead of providing package data that is statically coded in HTML.  
2.c.2 Each package now displays a description, start and end dates, and price.  
2.c.3 The package end date is greater than (or equal to) the current date, so only valid packages are listed. 
2.c.4 Also, checked whether the package start date is less than the current date, and if it is, wrote out some CSS to make the start date bold and red.

2.d	Re-designed the contact page so that it is generated from the database and lists all the agencies, showing the agency address and phone number, 
    followed by the contact information for each agent at that agency.
2.e	After the package list is being generated, created an order button next to each package, which goes/brings to an order page that has a customer order form for that package.  
    Customers enters their data and submit the order which will result in creation of a customer record and a booking record.  

Note:  What if the customer is already on the system? This Customer only can log in, can not create another account.
      








