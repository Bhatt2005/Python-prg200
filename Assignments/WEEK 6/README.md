# Week 6 Assignment — Scope and Modules

**Course:** Introduction to Python Programming  
**Topic:** Variable Scope, Built-in Modules, and Custom Modules

---

## Overview

This repository contains solutions to the Week 6 assignment, which focuses on understanding variable scope (global and local) and working with Python's built-in modules such as `math`, `random`, and `datetime`, as well as creating and importing a custom module.

---

## Programs

### Q1 — Temperature Logger (`temperature_logger.py`)
Analyses daily temperature readings from Kathmandu Weather Station using the `math` module. Calculates the mean and standard deviation of the readings and prints a summary including the minimum and maximum temperatures. Demonstrates the use of a global variable for the station name and a local variable inside `get_deviation()` that cannot be accessed outside the function.

### Q2 — Bill Splitter (`bill_splitter.py`)
Splits a restaurant bill equally among a group of friends and randomly picks one person to pay an extra NPR 50 as a lucky tax. Uses the `random` module with `random.seed(42)` to keep results consistent across runs. Demonstrates the use of local variables inside functions and calling multiple functions within a single summary function.

### Q3 — Exam Scheduler (`exam_scheduler.py`)
Generates an exam schedule for Bhaktapur Multiple Campus by calculating each exam date from a given start date using the `datetime` module. Uses `datetime.datetime` to parse dates and `datetime.timedelta` to add days. The college name is stored as a global variable and printed as a header in the schedule.

### Q4 — Shopping Discount (`shopping_discount.py` + `discount.py`)
Demonstrates how to split logic across multiple files using a custom module. All discount and tax functions are defined in `discount.py`, which is then imported into the main file. Calculates the final price for each product after applying a percentage discount followed by 13% VAT.

> **Note for Jupyter users:** Run `%%writefile discount.py` in the first cell to create the module file before running the main code in the next cell.

---

## How to Run

```bash
python temperature_logger.py
python bill_splitter.py
python exam_scheduler.py
python shopping_discount.py
```

> For Q4, make sure `discount.py` is in the same directory as `shopping_discount.py` before running.
