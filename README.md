# ENDPOINTS
![image](https://user-images.githubusercontent.com/58859695/201439599-6840d65b-6907-4afb-a3d5-f67eb0707ef4.png)

# ARQUITECTURE 
![image](https://user-images.githubusercontent.com/58859695/201437570-66750578-db89-4237-af65-4617d3227b61.png)

# How to star cus-shopping-car-service

`git clone https://github.com/ShoppingCarProject/cus-shopping-car-service.git`

![image](https://user-images.githubusercontent.com/58859695/201437977-faf15f7a-426a-4905-89ae-170e77573e94.png)

Start your MySql On Xamp 

![image](https://user-images.githubusercontent.com/58859695/201438043-fe3fefbf-d34c-472c-aab2-e7c7ec67252d.png)

Download here : https://www.apachefriends.org/es/download.html

Connect in your Client: 

![image](https://user-images.githubusercontent.com/58859695/201438136-fc803dfc-b5ec-4187-9828-ad985ec632fe.png)

Import project and Existing maven projects

![image](https://user-images.githubusercontent.com/58859695/201438289-25473b43-f26d-423f-9761-3692069bb3d3.png)

Open

![image](https://user-images.githubusercontent.com/58859695/201438327-11e76b66-58f1-4a64-8a68-72efe5aaac22.png)
 Seacrh the application.properties and put your configuration data 
 ![image](https://user-images.githubusercontent.com/58859695/201438417-b0e20794-cdf5-4f63-b463-19b396eb782a.png)
 
 I dont'have the schema shoppingcar
 ![image](https://user-images.githubusercontent.com/58859695/201438467-5db88cd8-77b9-46b6-990f-e3fa1df99c0b.png)

Run your project! 

![image](https://user-images.githubusercontent.com/58859695/201438567-a68baf5a-0e8a-4a85-b955-1bf39fa720b3.png)

the aplication Tomcat started on port(s): 7001 (http) with context path ''

and we are going to have the database in my own mysql 

![image](https://user-images.githubusercontent.com/58859695/201438736-e1151188-36ff-4116-b786-eb305dc37528.png)

# It's All! for this project 

# How to star cus-security-service

`git clone https://github.com/ShoppingCarProject/cus-security-service.git`

![image](https://user-images.githubusercontent.com/58859695/201438930-d5327561-370d-4984-bb41-5ea93a511e15.png)

follow the steps for importing the project cus-shopping-car-service

we are going to use redis for this step we are going to use docker.

`docker pull redis`
 and start 
 `docker run --name redis -p 6379:6379 redis`
we are going to open the application.properties and we are going to have our own configurtions , the docker image have the same configurations
![image](https://user-images.githubusercontent.com/58859695/201439442-46fe27aa-fae6-4bba-84ea-c3b121a41f7b.png)
