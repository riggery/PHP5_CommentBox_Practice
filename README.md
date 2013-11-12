# README: PHP5_CommentBox_Practice

###Features 
- Jquery Ajax dynamicly update database
- HTML/CSS user interface design
- PDO is used to prevent sql injection security
- Allow the user to remove entries from table dynamically

Setting
------------

### PHP database connection
Look in [/PHP/connection.php](https://github.com/riggery/PHP5_CommentBox_Practice/blob/master/PHP/connection.php) to see a list of available settings.

#### Database
```
    CREATE DATABASE PHP_test_db;
    
    USE PHP_test_db;
    
    CREATE TABLE info (
    	ID INT(11) NOT NULL AUTO_INCREMENT,
            Name VARCHAR(200) NOT NULL,
            Comment VARCHAR(500) NOT NULL,
            Date_Created VARCHAR(200) NOT NULL,
            Primary Key(ID)
    )
```
Or Import [/info.sql]

#### Run  
Type in browser `http://localhost/php5test/`


### ScreenShot
[![solarized dualmode](https://raw.github.com/riggery/PHP5_CommentBox_Practice/master/Screen%20Shot.png)](#features)

