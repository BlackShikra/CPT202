# CPT202
Group_Progrem

## Server and MySql

  ### Notice
   We use **MySQL** database **8.0**.<br>
   
  ### Step 1
   Please import _yummy.sql_ from the **SQL** into your MySQL database.<br>
   
  ### Step 2
   Open **yummyServer** in IDEA and link to database. Then modify the following code.
   ~~~
   spring.datasource.url=jdbc:mysql://localhost:3306/#your_database_name#?serverTimezone=UTC
   spring.datasource.username=#database_username#
   spring.datasource.password=#database_password#
   ~~~
   Modify the database information to your own.<br>
   
  ### Step 3
   Run the server code<br>
    
## Browser

  Open **YummyBrowser** in WebStorm.<br>
  
  ### Build Setup
  ~~~
  # install dependencies
  npm install

  # serve with hot reload at localhost:8080
  npm run dev

  # build for production with minification
  npm run build
  ~~~
  
  ### Default available account
  You can find the set up account in the database. Here are two of them.<br>
   #### Customer 
    Username:shichu@163.com
    Password:shichu
  
   #### Canteen
    Username:1
    Password:zhenhuan
    
  
