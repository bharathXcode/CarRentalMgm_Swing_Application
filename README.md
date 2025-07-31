# 🚗 Car Rental Management System (Java Swing)

**Author:** Bharath L  
**Technology:** Java Swing  
**Type:** Desktop GUI Application  

---

## 📘 Introduction

The **Car Rental Management System** is a Java Swing–based desktop application to manage car rental operations.  
Users can:

- Add new rental entries
- View all rentals in a table
- Search by customer name
- Delete selected records

All operations are available via an interactive GUI.

---

## ✨ Features Table

| Feature               | Description                                              |
|------------------------|----------------------------------------------------------|
| ➕ Add Rental           | Add new rental with car and customer details             |
| 👀 View All Rentals     | Display all rentals in a table view                      |
| 🔍 Search by Customer  | Find rentals by customer name                            |
| ❌ Delete Rental        | Remove selected rental entry                             |
| 📋 JTable Integration  | Show records in a scrollable, editable table             |
| 🖱️ Swing UI            | GUI built with buttons, text fields, panels, and alerts  |

---

## 📂 Components Table

| Component            | Purpose                                                  |
|----------------------|----------------------------------------------------------|
| `JFrame`             | Main window frame                                        |
| `JPanel`             | Layout containers                                        |
| `JTextField`         | Input fields for car model, car number, customer, etc.   |
| `JButton`            | Buttons for add, search, delete, etc.                    |
| `JTable`             | Table to display all rental records                      |
| `DefaultTableModel`  | Data model behind the JTable                             |
| `JScrollPane`        | Enables table scrolling                                  |
| `JOptionPane`        | Displays dialog messages                                 |
| `ArrayList<Rental>`  | Stores rental entries in memory                          |

---

## 🛠️ How to Run the Project

### ✅ Requirements

- Java JDK 8 or above
- Any Java IDE (e.g. IntelliJ, Eclipse) or terminal

### ▶️ Steps to Run

1. Open your IDE or terminal.
2. Create a new Java file named `CarRentalSystem.java`.
3. Copy the full source code into the file.
4. Compile and run:

bash
javac CarRentalSystem.java
java CarRentalSystem

### Preloaded Data
| Car Model    | Car Number    | Customer | Contact    | Days |
| ------------ | ------------- | -------- | ---------- | ---- |
| Toyota Camry | KA-01-AA-1234 | Alice    | 9876543210 | 3    |
| Hyundai i20  | KA-05-BB-4567 | Bob      | 9123456789 | 5    |

### Future Enhnacements
* Store/load data using files or databases (currently uses in-memory ArrayList)
* Add ability to update records
* Integrate date picker for rental duration
* Filter rentals by car model or time period
* Improve layout for screen resizing

### Output Vedio


https://github.com/user-attachments/assets/ac7edf5f-8759-429b-9a50-911c44cc3395

