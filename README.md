# cpp-apps

Four console programs in C++ from early C++ practice (2022): a menu-driven bank program in two versions, a phone bill calculator based on call count, and a class-based book record.

| File | What it does |
|---|---|
| `bank_menu_practice.cpp` | Bank menu with account creation, cash withdrawal and cash deposit prompts (class `bank`) |
| `bank_menu_draft.cpp` | The first draft of the bank menu: integer fields, numbered options 1 to 3 |
| `phone_bill_calculator.cpp` | Calculates a phone bill from the number of calls |
| `book_record_class.cpp` | `book` class that reads a book's id, price and pages and prints them back |

## Build and run

```
g++ bank_menu_practice.cpp -o bank_menu_practice
./bank_menu_practice
```

Each program is a single file with no dependencies beyond the C++ standard library.
