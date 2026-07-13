Week 1 – Python OOP Practice

A collection of small Python programs written to practice the core pillars of
Object-Oriented Programming: classes, inheritance, encapsulation, polymorphism,
and abstraction. Includes ten standalone practice exercises plus one larger
mini-project (a console-based Library Management System).

 Setup:



```bash
git clone https://github.com/Manumha-Nadeem/week-1-python.git
cd week-1-python
```


Usage

Each exercise is a standalone script. Run any of them directly:

```bash
python3 qno1              # Student class - grade calculator
python3 qno3               # Rectangle - area, perimeter, square check
python3 qno4               # Employee - salary increment
python3 qno5               # Vehicle -> Car / Bike inheritance
python3 qno6               # ATM - encapsulation with private attributes
python3 qno7               # Animal -> Dog/Cat/Cow polymorphism
python3 qno8               # Abstract Shape class (Circle, Rectangle, Triangle)
python3 qno9               # Circle - area & circumference
python3 qno10              # Person -> Student inheritance
python3 "bank account qno2"  # BankAccount - deposit/withdraw
```

The Library Management System is interactive — it prints a menu and reads
your choice from the keyboard:

```bash
python3 "library management system"
```

Sample menu:
```
===== Library Management System =====
1. Add Book
2. Remove Book
3. Register Member
4. Remove Member
5. Borrow Book
6. Return Book
7. Search Books
8. List All Books
9. List All Members
10. View Member History
0. Exit
```

 Project Structure

| File | Concept Practiced |
|---|---|
| `qno1` | Basic class definition, methods, conditional logic (grading) |
| `qno3` | Class with computed properties (area, perimeter) |
| `qno4` | Object state mutation via methods |
| `qno5` | Single-level inheritance, method overriding |
| `qno6` | Encapsulation — private attributes (`__pin`, `__balance`) |
| `qno7` | Polymorphism — shared interface across subclasses |
| `qno8` | Abstraction — `ABC` |
| `qno9` | Basic class, arithmetic operations |
| `qno10` | Inheritance |
| `bank account qno2` | Class with guarded state changes (insufficient balance check) |
| `library management system` | Multi-class mini-project — `Book`, `Member`, `Transaction`, `Library` working together |

 Notes:

- Each `qnoX` file is self-contained and runs its own demo data at the bottom
  of the script — no setup needed beyond running the file.
- The library system persists data only for the runtime of the program
  (in-memory dictionaries); it does not save to disk between runs.
