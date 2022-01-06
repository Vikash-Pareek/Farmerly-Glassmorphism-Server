# Farmerly - Backend

> For Frontend code visit :
  <b>https://github.com/Vikash-Pareek/Farmerly-Glassmorphism-Client</b>

<br/>


#### Website works best in Google Chrome browser
#### For best experience in Mozilla Firefox browser do the following :
    1. type "about:config" in the browser's url address bar and press Enter.
    
    2. Accept the warning.
    
    3. type "layout.css.backdrop-filter.enabled" in the search bar and click on the reversible arrow icon on the extreme right and change the value from "false" to "true".
    
    4. Next, type "gfx.webrender.all" in the search bar and click on the reversible arrow icon on the extreme right and change the value from "false" to "true".
    
    => Learn More:
    https://dev.to/snkds/how-to-enable-backdrop-filter-in-firefox-2n8e

<br/>
<br/>
<br/>

> Frontend-> React JS

> Backend-> Node JS & Express JS

> Database-> MongoDB

## Installation Process
1. #### Clone the repo using this command
    ```bash
    git clone https://github.com/Vikash-Pareek/Farmerly-Glassmorphism-Server.git
    ```
2. #### Install NPM Packages :
    ```bash
    cd Farmerly-Glassmorphism-Server
    npm install
    ```
3. Go to the config folder at Farmerly-Glassmorphism-Server/config & create default.json of mongoDB connection, JWT_SECRET, BRAINTREE_MERCHANT_ID, BRAINTREE_PUBLIC_KEY and BRAINTREE_PRIVATE_KEY.

    ```bash
    cd Farmerly-Glassmorphism-Server
    cd config
    cat >> default.json
    ```
    (Ctrl+c to exit previous command)
    
    ##### Sample code for default.json
    ```json
    {
      "MONGODB_URI": "YOUR_MONGODB_URI",
      "JWT_SECRET": "YOUR_JWT_SECRET",
      "BRAINTREE_MERCHANT_ID": "YOUR_BRAINTREE_MERCHANT_ID",
      "BRAINTREE_PUBLIC_KEY": "YOUR_BRAINTREE_PUBLIC_KEY",
      "BRAINTREE_PRIVATE_KEY": "YOUR_BRAINTREE_PRIVATE_KEY"
    }

    ```
    ##### Instructions:
    1. You can use any random string as JWT_SECRET
    2. #### note: add default.json in .gitignore file

4. <b>Deploy this project</b> on your local server by using this command :
    ```bash
    cd Farmerly-Glassmorphism-Server
    npm run dev
    ```
    #### note: both backend & frontend server will start at once with the above command.

### Website Description:
    1. User can view all equiments
    2. User can view single equipment
    3. User can search equipments and view equiments by Brand and Price Range
    4. User can Add equipments to Cart, Checkout equipments using credit card info
    5. User can register & sign in
    6. Admin can create, edit, update & delete equipments
    7. Admin can create Brands
    8. Admin can view rented equipments
    9. Admin can change the status of a equipment (processing, shipped, delivered, etc.)

<br/>
<br/>

> Website's Live Deployed Link :
   <br/><b>https://farmerly.netlify.app/</b>
