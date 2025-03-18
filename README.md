USB/IP Mobile & Computer Applications
Introduction
The final year project I have decided to develop is a USB over IP mobile and computer application. The way this will work is a client/customer will plug in a USB device into their mobile device, and the application can wirelessly transmit it – acting as a gateway so that the host/admin can access the connected device as if it was directly connected to their computer system. How this system will work is a VPN (virtual private network) will be created by the admins system which the client will connect to – this basically will act as a server, forming a way of communication between the two systems. Once that form of communication is established, the hosts system will search the clients connected USB devices and bind the requested device to their system. Once paired, the devices USB COM/port protocol will be forwarded to the host, making it come up on their system as a regular device which is plugged in directly.

Aim of the project & who it is for
The reason behind making it a cross platform USB redirector/forwarder system is to allow remote diagnostics/coding to be possible for a technician/mechanic at a vehicle customisation/repairs shop. This is because this application would allow OBD (Onboard diagnostics) VCI (Vehicle Communication Interface) devices to be connected to the phone and then the shop can access that device remotely and diagnose on their computer using their proprietary software. This means that the customer won’t need to travel to the shop, saving time and means that they wouldn’t need to purchase a laptop or computer to do the same process, which makes it a much more inexpensive process if the client is only available for remote services. 
How it will work
The computer software will allow technicians to firstly dispense/create tokens for potential jobs. These tokens will act as a form of login for the customers, without this the customer won’t be able to progress on the app. When creating the token on the program, the technician will be asked to enter:
•	Description of the job.
•	Timescale allocated for the job.
•	Time and date of when the job is meant to take place.
When the token has been created, the technician will be able to access it from their jobs page. From there they can either edit, activate/start, or delete jobs. If they decide to start/activate a job. If they start a job, it can either be completed or cancelled if they encounter an issue.
Mobile side of the system
The mobile application will have the code input for the token, which they can then enter on their device. This will automatically redirect them to the job sheet page on the app. On this section it will show:
•	A brief description job which is going to be completed.
•	Timescale on how long the job is scheduled to take.
•	The technicians contact details should any issues arise.
•	The date and time when the job is booked to take place, also allowing the customer to add it to their phones calendar application.
When the job is going to the start, the technician can activate the job, which will automatically start the process of connecting the customers OBD device to the technician’s computer system. There will also be instructions displayed for the customer to easily setup the OBD device on their vehicle. Once the job is complete the display will turn green and display a message saying the job is complete.
If the job is under progress, it will show that on the customers screen, else if the job is cancelled/delayed that will also be shown.
Project Objectives
1.	Research on USB IP, specifically on cross platform issues which may arise due to differentiating communication methods and how to counteract them.
2.	Explore the development approaches which are suitable to build an application/system like this, such as Android Studio, C#, Java, and which drivers will be required to make the communication possible.
3.	Survey customers on what they would like to see in the mobile application and technicians for the computer software then design the product around the feedback given.
4.	Develop the basic UI/Menu part of the system.
5.	Research into different hosting services which can host the database and scripts which will be used by the application to make the remote connection possible. Examples of such services include AWS (Amazon Web Services) and Poseidon (the universities server).
6.	Setup the database needed to store the data.
7.	Develop the USB/IP part of the system.
8.	Develop token & instruction parts of system.
9.	Develop complete menu.
10.	Develop a chat system where customers will have the ability to interact with the technicians should there be any issues/queries about the job which they want to take place.
11.	User Testing.
12.	Product evaluation at each stage which consists of running a variety of tests including Load testing, UI Testing, Acceptance testing to ensure that the product is meeting the requirements.
13.	Keep an up-to-date logbook for the whole duration of the project.
Optional Objectives
1.	Investigate on how to integrate a booking system on the mobile application – allowing for customers to decide on which company they would like to procced with.
2.	Research on how to make the customers mobile application auto translate text, making it accessible to a wider audience and helping technicians communicate even with a language barrier.
3.	Investigate into the OBD protocol and develop potential safeties which could be integrated to the software to prevent issues such as live battery voltage, customers internet data speed, OBD connection status.
