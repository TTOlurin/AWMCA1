This is a Python based web application built using Django, Postgresql and Docker. 
This application allows users to create an account, log in/out and view their current location on a map. 

The user's profile data is stored on a Postgresql database and each time they click on the map, their location is updated and stored in the database.

The application contains 3 pages which are the Home, Map and Sign Up.

Home page when the user hasn't logged in or signed up:

![image](https://user-images.githubusercontent.com/71713573/200970381-e4d73b07-1ddc-4460-b5c7-d90d2534b346.png)



Log In Page:

![image](https://user-images.githubusercontent.com/71713573/200970750-ef7447da-cec1-4746-a878-6e0a6ed33ae9.png)

Home page when the user has logged in:

![image](https://user-images.githubusercontent.com/71713573/200971282-30c1bf8d-709e-4058-8da1-7a529d483c1f.png)

Map Page:

![image](https://user-images.githubusercontent.com/71713573/200971461-60aa7133-a85e-4b66-ab5a-04b4d1124628.png)

Map Page with hoverable dropdown menu:

![image](https://user-images.githubusercontent.com/71713573/200971838-5429ee32-81a8-4ff3-875c-eb534f008080.png)

Once I built the application, I created docker containers for the project and the image.

To deploy this application, I created a VM instance using Digital Ocean's Droplet feature. And acquired a domain from Namecheap.

Droplet:

![image](https://user-images.githubusercontent.com/71713573/200975810-5e6abe20-e9de-40e4-8d3a-3c41823bdf38.png)


Next, I modified the DNS entry of my domain name and changed the IP address to that of the Droplet's:

![image](https://user-images.githubusercontent.com/71713573/200975450-af477c7e-9d8d-44b6-81da-8ebe3a9d807b.png)

when I pinged my domain name, the Droplet's IP address was returned:

![image](https://user-images.githubusercontent.com/71713573/200975620-5c488b8a-0647-477d-8100-df9064d472db.png)

Next steps: I am continuously working on this project and plan to fully deploy the application very soon.







