🏨 Simple Hotel Management System

A Java Swing-based Hotel Management System that allows users to book rooms, check out, track room status, and monitor total revenue. Data is stored persistently using JSON files.

Features

Book rooms with customer name, room type, and number of nights.

Check out rooms and display the total bill.

View room status in a table (room number, type, availability, customer, nights, price).

Track total revenue earned from all check-outs.

Persistent storage: Rooms and their status are saved in a JSON file.

Clean GUI using Java Swing.

Room Types & Pricing
Type	Price per Night
Single	$100
Double	$150
Suite	$250
Installation & Running

Make sure you have Java 8+ installed.

Download/clone this repository.

Add Gson library to your project for JSON support:

Download gson-2.10.1.jar from Gson GitHub

Add it to your project classpath.

Compile and run:

javac -cp gson-2.10.1.jar SimpleHotelManagement.java
java -cp .;gson-2.10.1.jar SimpleHotelManagement


⚠️ On Mac/Linux, replace ; with : in the classpath.

How to Use

Book Room

Enter room number, customer name, select room type, and number of nights.

Click Book Room.

Check-Out Room

Enter the room number to check out.

The total bill will be displayed and the room will be marked available.

Room Status Table

View all rooms, availability, customer name, nights, and price.

Click Refresh Table to update the view.

Total Revenue

Displayed at the bottom of the window.

Updates automatically after check-out.

Data Storage

rooms.json stores room details (booked status, customer, nights).

Ensures persistent data across program runs.

Future Enhancements

Color-coded room availability in the table (green = available, red = booked).

Search or filter rooms by customer or status.

Generate reports (PDF/CSV) of revenue and transactions.

Add more room types and pricing tiers.

Screenshots

(Optional: add screenshots of the GUI here)
