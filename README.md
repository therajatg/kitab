# kitab

Kitab is an ecommerce book store that I made using the parts component library. In order to use the components from my component library. I added @import url("https://parts-builder.netlify.app/styles/main-style.css"); inside all-styles.css

Here's how I arranged all the pages of kitab:

1. all-styles.css is the file inside the styles folder which contains all the below styles:<br/>

   a. @import url("https://parts-builder.netlify.app/styles/main-style.css");   =>    This is style from component library. <br/>      
   
   b. @import url("main-style.css");                                            =>    This is the common style across kitab (other than component library style) <br/> 
   
   c. @import url("home.css");                                                  =>    This is the styling for the home page (index.html)<br/> 
   
   d. @import url("product-listing.css");                                       =>    Styling for product-listing page (product-listing.html)<br/>   
   
   e. @import url("cart.css");                                                  =>    Styling for shopping-cart page (cart.html)<br/>        
   
   f. @import url("wish-list.css");                                             =>    Styling for wish-list page (wish-list.html)<br/>  
   
   g. @import url("login.css");                                                 =>    Styling for login page (login.html)<br/>          
   
   h. @import url("signup.css");                                                =>    Styling for signup page (signup.html)<br/>       



2. all HTML pages except index.html (home-page) are inside the docs folder.

3. all styles are inside the styles folder.


Here's a link of kitab: https://kitab-ecom.netlify.app/docs/product-listing.html
