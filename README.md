# 🎥 Cinema 🎥
It is a great app which represents a cinema booking system! \
Here you can manage different cinema halls and movies. \
There is also a possibility to add tickets to your shopping cart and complete the orders !<br />

## :bulb: Functionality :bulb:
>- _User **registration** and **authentication**_.
>- _Possibility to be in the role of **admin / user**_
>- _Possibility to **login / logout**_
>- _**Admin** rights:_
>- - _**add / see** cinema halls_
>- - _**add new / see available** movies_
>- - _**create / change / delete / see** movie sessions_
>- - _**find users by-email**_
>- _**User** rights:_
>- - _**see** all the cinema halls_
>- - _**see** all the movies_
>- - _**see available** movie sessions_
>- - _**add tickets to shopping cart**_
>- - _**complete the order**_

## :file_folder: Structure :file_folder:
>_This project has **N-tier architecture**. It consists of:_
>>**Controller** - accept http requests from users and display information.
>
>>**Service** - all business-logic is located here.
>
>>**DAO** - all interaction with DataBase is located here
## :gear: Technologies :gear:
>_**Spring MVC**_
>
>_**Spring Security**_
>
>_**Spring Data**_
>
>_**Hibernate**_
>
>_**MySQL**_
>
>_**Tomcat (9.0.50)**_
> 
## :man_shrugging: How can I use it ? :woman_shrugging:
>- _Step 1_ - **Fork this repository**
>- _Step 2_ - **Open IntelliJ IDEA and write `git clone <SSH link>` in console**
>- _Step 3_ - **Configure resources --> "db.properties" file**
>```properties
>db.driver=YOUR_DRIVER
>db.url=YOUR_URL
>db.user=YOUR_USERNAME
>db.password=YOUR_PASSWORD
>```
>- _Step 4_ - **Install Tomcat. (you can install it [here](https://tomcat.apache.org/download-90.cgi)) .**
>- _Step 5_ - **Add Tomcat server in configurations**
>- _Final Step_ - **Run project and enjoy using it ! :wink:**
___
