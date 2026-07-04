# 🅿️ Parking Lot Management System in Java

A console-based **Parking Lot Management System** developed using **Object-Oriented Programming (OOP)** and **Low-Level Design (LLD)** principles in Java. The system supports different vehicle types, parking spot allocation, ticket generation, fee calculation, and vehicle exit processing.

This project was created as part of **Weekend Dev Challenge #57: LLD Projects** conducted by **CodeChef**.

![Java](https://img.shields.io/badge/Java-OOP-blue)
![Project](https://img.shields.io/badge/Project-Completed-brightgreen)
![CodeChef](https://img.shields.io/badge/Weekend%20Dev%20Challenge-57-orange)

---

## 🏆 About the Challenge

This project was built for **Weekend Dev Challenge #57: Low-Level Design (LLD) Projects**, organized by **CodeChef** to strengthen software design and object-oriented programming skills.

🔗 CodeChef: https://www.codechef.com

🔗 My CodeChef Profile: https://www.codechef.com/users/jestin25

---

## 🚀 Features

* 🚗 Supports multiple vehicle types:

  * Motorcycle
  * Car
  * Truck
* 🅿️ Multiple parking spot sizes:

  * Small
  * Medium
  * Large
* 🎫 Automatic ticket generation
* 💰 Parking fee calculation
* 🔄 Smart parking allocation with fallback mechanism
* 🚪 Vehicle exit processing
* ⚠️ Custom exception handling when parking is full
* 📚 Clean OOP and modular design

---

## 📂 Project Structure

```text id="h6a1er"
pakingLotMain.java
│
├── VehicleType (Enum)
├── SpotType (Enum)
├── NoSpotAvailableException
├── Vehicle
│   ├── Motorcycle
│   ├── Car
│   └── Truck
├── ParkingSpot
│   ├── SmallSpot
│   ├── MediumSpot
│   └── LargeSpot
├── Ticket
├── FeeCalculator
├── ParkingLot
└── pakingLotMain
```

---

## 🛠 Technologies Used

* Java
* Object-Oriented Programming (OOP)
* Collections Framework

  * HashMap
  * Queue
  * LinkedList
* Exception Handling
* UUID Generation

---

## 🧩 OOP Concepts Implemented

* Classes and Objects
* Inheritance
* Abstraction
* Polymorphism
* Encapsulation
* Composition
* Custom Exceptions

---

## 🏗 Design Highlights

### Vehicle to Parking Spot Mapping

| Vehicle Type | Allowed Spots          |
| ------------ | ---------------------- |
| Motorcycle   | Small → Medium → Large |
| Car          | Medium → Large         |
| Truck        | Large                  |

### Smart Allocation Strategy

The system automatically searches for the best available parking spot and falls back to larger spots if necessary.

---

## ▶️ How to Run the Project

### Clone the Repository

```bash id="m5olrw"
git clone https://github.com/your-github-username/parking-lot-management-system.git
```

### Navigate to the Project Directory

```bash id="i5jl7h"
cd parking-lot-management-system
```

### Compile the Program

```bash id="0xvnpk"
javac pakingLotMain.java
```

### Run the Program

```bash id="3v4x9l"
java pakingLotMain
```

---

## 🎮 Sample Output

```text id="0k3y5u"
--- Booting up Parking Lot System ---

[Attempting to park Car 1]
CAR parked at MEDIUM Spot 2

[Attempting to park Car 2]
CAR parked at MEDIUM Spot 3

[Attempting to park Car 3 - Cascading to Large]
CAR parked at LARGE Spot 4

[Attempting to park Truck 1 - Should Fail]
System Alert: Lot Full: No available spots for vehicle type TRUCK
```

---

## 🔮 Future Enhancements

* Multiple parking floors
* Reserved parking spaces
* Dynamic pricing based on parking duration
* Vehicle search by license plate
* Admin dashboard
* Database integration
* Graphical User Interface (GUI)
* Online booking and payment system

---

## 👨‍💻 Author

**Jestin M K**

Passionate Java Developer | Problem Solver | Continuous Learner

🔗 GitHub: https://github.com/your-github-username

🔗 CodeChef: https://www.codechef.com/users/jestin25

---

## 🌟 Acknowledgement

This project was developed as part of **Weekend Dev Challenge #57: LLD Projects** conducted by **CodeChef**, helping developers improve their Low-Level Design and Object-Oriented Programming skills.

⭐ If you like this project, don't forget to **Star ⭐ the repository** and connect with me on CodeChef!
