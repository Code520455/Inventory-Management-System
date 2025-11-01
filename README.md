# 📘 Electronics Store Inventory Application
**Author(s):** Rahul Saha  
 
---

## 🧩 Overview
This project implements a **text-based inventory management application** for an electronics store.  
It demonstrates full **Object-Oriented Programming (OOP)** principles in **Python**, including inheritance, abstraction, encapsulation, and polymorphism.

The system allows users to:
- Create, buy, sell, and view **components** (like Wires, Batteries, and Sensors)
- Create, pack, unpack, and sell **circuit kits** (like Light or Sensor Circuits)
- Persist inventory data using **CSV file I/O**
- Interact via a clean **text-based menu interface**

---

## 🖥️ Features
| Feature | Description |
|----------|-------------|
| **Create Components** | Add new components like Wires, Batteries, or LED Lights |
| **Buy / Sell** | Adjust quantities; prevent invalid transactions |
| **Create Circuit Kits** | Combine components into kits |
| **Pack / Unpack Kits** | Duplicate or decompose circuits |
| **File I/O** | Read/write `components.csv` and `circuits.csv` |
| **Exception Handling** | Input validation and file I/O safety |
| **Unit Testing** | Validate methods and exception handling |

---

## 📂 Project Structure
electronics_inventory/
│
├── app.py # Main application (App class)
├── component.py # Component base class + subclasses
├── circuit.py # Circuit base class + subclasses
├── menu.py # Menu handling class
│
├── test_component.py # Unit tests for Component classes
├── test_circuit.py # Unit tests for Circuit classes
│
├── components.csv # Component database file
├── circuits.csv # Circuit database file
│
├── uml_diagram.png

## How to run
- Clone or unzip the project folder.
- Open a terminal inside the directory.
-- Run:
  --python app.py
-Follow on-screen menus to manage inventory.
