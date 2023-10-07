# Project Explanation
  - Users can view the website responsively in mobile view and tablet view as well.
  
  - Login Route
    - Users can only login to the website by entering a valid username and password.
    - Valid username: rahul and password: rahul@2021.
    
  - Home Route
    - Users can navigate to Home, Products, Cart routes using links in Navbar.
    - Users can also navigate to Home route by clicking on **Nxt Trendz** logo.
    - Users can use the Sortby options to sort the products based on ratings.
    - Users can use the search bar to search any particular products.
   
  - Cart Route
    - Users can select the Cart link in the navbar to view their added cart products.
    - Each product quantity and price will be displayed in the Cart list.
    - Users can increase or decrease their product quantity and the total price will be automatically get updated.
    - Users can remove all the products by clicking on Remove All button.
  
 
# Technologies Used
  - React JS, JS, CSS, Bootstrap, Routing, REST API Calls, Local Storage, JWT Token,
    Authorization, Authentication


# Project Details
  - Implemented Nxt Trendz application which is a clone for ECommerce applications like Amazon, Flipkart where
    users can login and can see list of products with search, filters, sort by, etc..
    
     ● Implemented Different pages and routes for Login, Products, Product details using React Router
       components Route, Switch, Link, props, state, lists, event handlers, form inputs.
  
     ●  Authenticating and authorizing users by taking username, password and doing login POST HTTP API
        Call and implementing filters by sending them as query parameters to product api calls.
    
     ● Persisted user login state by keeping jwt token in local storage, Sending it in headers of further api calls
       to authorize the user.
    
     ● Implemented username and password authentication and persisted login state using client storage.
    
     ● Implemented a protected route to ensure only authenticated users can access the pages like home,
       specific restaurant details, etc.
 
