🚖 Cab Booking System
A Cab Booking System built using C programming, demonstrating the use of file handling for storing and retrieving data.


✨ Features
User Registration and Login System.
Booking cabs for specific locations and time slots.
View booking history.
Save and retrieve data using text files.

📁 Cab_Booking_System  
├── main.c                 # Main program file  
├── bookings.txt           # Stores booking details  
├── users.txt              # Stores user credentials  
├── cabs.txt               # Stores cab details  
## 📄 Documentation

You can view the full documentation for the **Cab Booking System** here:

[Download PDF Documentation](cab_booking_sytem.pdf)


🔧 Setup Instructions
Clone the repository:
git clone https://github.com/your-username/cab-booking-system.git  
Ensure the following text files are created in the same directory as the executable:

1.bookings.txt (for storing booking details)
2.users.txt (for storing user credentials)
3.cabs.txt (for storing available cab details)
If the program is run without these files, it will automatically create them, but they will be empty.

Compile the program using a C compiler:

gcc main.c -o cab_booking_system  
Run the executable:
./cab_booking_system  

📝 Text File Format
1. users.txt
Contains user credentials in the following format:
username,password

2. cabs.txt
Contains details of available cabs in the following format:
Cab_ID,Driver_Name,Car_Type,Capacity,Fare_Per_KM
 
4. bookings.txt
Stores booking records in the following format:
Booking_ID,Username,Cab_ID,Pickup_Location,Drop_Location,Distance,Total_Fare
 
💻 Technologies Used
C Programming: Core logic and flow.
File Handling: To store and retrieve user, cab, and booking data persistently.

