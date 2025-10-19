# 🏨 Simple Hotel Management System

A **Java Swing-based Hotel Management System** that allows users to book rooms, check out, track room status, and monitor total revenue. Data is stored **persistently** using JSON files.

---

## Features
- Book rooms with **customer name, room type, and number of nights**.  
- Check out rooms and display the **total bill**.  
- View **room status** in a table (room number, type, availability, customer, nights, price).  
- Track **total revenue** earned from all check-outs.  
- **Persistent storage**: Rooms and their status are saved in a JSON file.  
- Clean **GUI using Java Swing**.

---

## Room Types & Pricing
| Type   | Price per Night |
|--------|----------------|
| Single | $100           |
| Double | $150           |
| Suite  | $250           |

---

## Installation & Running
1. Make sure you have **Java 8+** installed.  
2. Download/clone this repository.  
3. Add **Gson library** to your project for JSON support:  
   - Download `gson-2.10.1.jar` from [Gson GitHub](https://github.com/google/gson)  
   - Add it to your project classpath.  
4. Compile and run:

```bash
javac -cp gson-2.10.1.jar SimpleHotelManagement.java
java -cp .;gson-2.10.1.jar SimpleHotelManagement

