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
   spring.datasource.url=jdbc:mysql://localhost:3306/yummy?serverTimezone=UTC
   spring.datasource.username=root
   spring.datasource.password=
   ~~~
   Modify the database information to your own.<br>
   
  ### Step 3
    Run the server code<br>
    
## Browser

  Open **YummyBrowser** in WebStorm.<br>
  
  ### Build Setup

  ``` bash
  # install dependencies
  npm install

  # serve with hot reload at localhost:8080
  npm run dev

  # build for production with minification
  npm run build
