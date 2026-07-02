# 📱 Recharge App (Java)

A simple **console-based Mobile Recharge Application** developed in **Java** using Object-Oriented Programming (OOP) concepts. The application allows users to register customers, select recharge plans, apply discounts, and display the final recharge details.

## 🚀 Features

- Register multiple customers
- Select from three recharge plans (Plan A, Plan B, Plan C)
- Automatic discount calculation
- Display recharge summary
- Menu-driven console interface

## 🛠️ Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Scanner Class
- Arrays

## 💡 OOP Concepts Implemented

- **Inheritance** (`customer` extends `person`)
- **Abstraction** (`plans` abstract class)
- **Interface** (`Discountable`)
- **Polymorphism** (Different discount implementations for each plan)
- **Encapsulation** (Private data members with getter methods)

## 📋 Available Recharge Plans

| Plan | Price | Discount |
|------|------:|---------:|
| Plan A | ₹199 | 10% Off |
| Plan B | ₹299 | Flat ₹50 Off |
| Plan C | ₹399 | 20% Off |

## 📂 Project Structure

```
Recharge App/
│── Customer.java
│── RechargeApp.java
```

## ▶️ How to Run

1. Clone the repository.
2. Open the project in any Java IDE (Eclipse, IntelliJ IDEA, or VS Code).
3. Compile the Java files.
4. Run `RechargeApp.java`.
5. Enter customer details and choose a recharge plan.

## 📸 Sample Output

```
Enter number of Customers: 1

Enter your Name:
John

Enter your Phone Number:
9876543210

Available Plans
A - PlanA (₹199, 10% discount)
B - PlanB (₹299, Flat ₹50 off)
C - PlanC (₹399, 20% discount)

Recharge Details
--------------------------
Customer Name: John
Phone Number: 9876543210
Plan Selected: PlanA
Plan Price: ₹199
Discount: ₹19.9
Final Price: ₹179.1
```

## 🎯 Future Enhancements

- Recharge history
- Payment gateway simulation
- Mobile number validation
- File handling for customer records
- Graphical User Interface (GUI)

## 👨‍💻 Author

**Arokiya Muthu Sirija**

---
⭐ If you found this project useful, consider giving it a star!
