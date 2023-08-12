# What is Dev-Sec-Ops-Handbook?
This handbook is a web application designed to teach users about **SQL Injections and JavaScript Cross Site Scripting**. The handbook contains **both theoretical and practical** learning materials, and contains **over 30 different challenges** for users to hone their skills with.

## Installation
There are two methods of installation; The first method utilises XAMPP Control Panel while the second method is a "plug-and-play" Virtual Machine.
### Method one: XAMPP Control Panel
1. Download XAMPP Control Panel 
2. [Download all necessary files here](test)
3. Move the folders 'majorProject' and 'hands-on' to your XAMPP's **htdocs folder**
4. Open the apache config file 'httpd.conf'. Search for the string 'xampp/htdocs' and **uncomment the line** ```# AllowOverride All```. More information can be found in the link below:
	- https://stackoverflow.com/questions/24472349/htaccess-doesnt-work-on-xampp-windows-7
5. Turn on MySQL and Apache in XAMPP. Navigate to phpmyadmin by typing 'localhost/phpmyadmin' in your browser's URL.
6. Create 3 databases; **handbook**,**handson**, and **challenges**
7. Create the user **wukong**. Set the host name to **localhost** and the password to **heaven**.
	- Give the user **wukong** access to **only the database 'handbook'**. This user **should not** have access to any other databases.
8. Create the user **nezha**. Set the host name to **localhost** and the password to **demon**.
	- Give the user **nezha** access to **only the databases 'handson' and 'challenges'**. This user **should not** have access to any other databases.
9. Lastly, import all the data from the .sql files provided. Import the files 'handbook.sql', 'handson.sql', and 'challenges.sq' accordingly based on their respective databases.

### Method two: Virtual Machine
TODO
 
