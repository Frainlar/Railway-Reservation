# Railway Reservation System
This repository contains a simple console application built with C++ (Version 14) and named as the 'Railway Reservation System' project.  This program features two modes, password protection and some basic file handling operations to add and display train inquiry and reservation records. This project is complete and totally-error free, and I have presented the source code in a very understandable manner.

# Run
- Clone the Repository
- Run 'railwayReservation.exe' File to run the Application

# Application Logic
There are two modes in this project – the administrator mode and the user mode. 
## Administrator mode: 
- For the first time you have to create Users from the Admin mode. Once users are created, you can use the same user again and again, and they will be stored in separate files.
- The operations related to both these modes are quite similar in this railway reservation system project in C++. In Admin mode, you can create detail database, add details, display details, perform user management functions and display passenger details.
## User mode: 
- As aforementioned, at first you need to go to the administrator mode and create users. After that, you can use these users as you wish, and the information related to them will be recorded in separate files. In the user mode, you can create id database, add details and display details.
## Train and Reservation details: 
- In this railway reservation system project in C++, users can get both the train details and the train reservation details. The details to be provided for train are train no., train name, boarding point, destination point, no. of seats in first class and fare per ticket, no. of seats in second class and fare per ticket and date of travel.
- And, in case of reservation details, the information to be provided are train no., train name, boarding point, destination point, no. of seats required, seat class specification, date of reservation, passenger category and amount to be paid. According to the no. of seats, additional information – passenger name and passenger age are to be provided. The passenger category is divided as: military, senior citizen, children and none.
## Cancel reservation: 
- It is somewhat similar to the feature mentioned above. This feature requires the date of cancellation in this railway reservation system project in C++. Then cancellation details can be displayed; the details here include train no., train name, boarding point, destination point, passenger class, no. of seats to be cancelled, passenger name and age, date of cancellation and the amount to be collected back.
## Password: 
- This railway reservation system project in C++ requires the administrator password to access the admin mode. The password is “codewithc”. If you enter the wrong password, it displays the message – “You are not permitted to login.”
