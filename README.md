Description
======
This respiratory builds an android application with the idea of having the same University Course Registration (Goldmine) experience on a mobile device.

The purpose of this respiratory is to allow new or existing users to create accounts and be able to sign up for their college courses. It is common for University students to enroll for their classes. Hence, this application will enhance the experience of the user to register through a mobile app.

How does it work?
======

The android application launches and takes the user to the @see LoginActivity.java and gives an opportunity to the user to log in if they have an existing account, else to register for a new account. This works very well because of the files that are in the backend folder, @see Login.php & 
Register.php. You see these 2 files are stored in my domain and talk to the database. For now the database contains a simple table called user, which
is where the information of the user is stored, i.e user_id (which auto increments each time a new account is created), name, username, age and
finally password.  

Once the user creates an account they can input their credentials with the help of @see Login.php and @see LoginActivity.java and @see LoginRequest verifies if the user credentials are correct. If the credentials are correct @see HomeActivity.java displays with a simple welcome home page.

Screenshots
======
![alt tag](Screenshots/Home-2.png "Log in")

![alt tag](Screenshots/Register-2.png "Register")

![alt tag](Screenshots/Welcome.png "Welcome!")

![alt tag](Screenshots/Add_Courses.png "Register for courses!")

![alt tag](Screenshots/Database.png "Register for courses!")

(https://github.com/oiricaud/University-Course-Registration/blob/master/Screenshots/Database.png "Database")

Above screenshot I have the new register students which includes username/password stored safely in the database 


Use Cases
======
![alt tag](https://cloud.githubusercontent.com/assets/11867058/21087373/7487f0e2-bfe2-11e6-8bf9-d97d105b385b.png)

Register

Log in

Manage Schedule

Add Course

Drop Course

View Catalog

View Transcript

Test Cases
======
