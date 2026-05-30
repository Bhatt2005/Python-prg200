# Week 4 Assignment — Functions in Python

**Course:** Introduction to Python Programming
**Topic:** Functions — Definition, Parameters, Return Values

---

## Overview

This repository contains solutions to the Week 4 assignment, which focuses on defining and using functions in Python. Each program is written around a real-world scenario relevant to Nepal, covering topics such as billing systems, alert mechanisms, calendar conversion, text analysis, and banking operations.

---

## Programs

### Q1 — Small Shop Billing and Inventory System 
Simulates a billing counter for a small grocery shop in Kathmandu. The `process_order` function processes a customer's cart, checks available stock, calculates item-wise costs, prints a formatted bill, and updates the inventory after purchase.

### Q2 — Water Level Alert System 
Models a flood monitoring system for the Koshi River. The `check_water_level` function takes a sensor location and water level reading, then returns an appropriate status — Safe, Warning, or Danger — to guide field workers during monsoon season.

### Q3 — Date Converter for Nepal Bank System 
Converts dates between the Bikram Sambat (BS) and Gregorian (AD) calendars. Uses the `nepali-datetime` library for accurate month and day conversion, since a simple year offset formula cannot correctly map months between the two calendar systems. Supports multiple output formats including ISO and full Nepali month name.

> **Dependency:** Install before running — `pip install nepali-datetime`

### Q4 — Word Frequency Counter 
Analyses a block of text to identify the most frequently occurring words. The `word_frequency` function lowercases all words, strips punctuation, builds a frequency dictionary, and prints the top 3 most common words along with their counts.

### Q5 — Simple ATM Simulator 
Implements a basic ATM system for a cooperative bank. The `atm` function validates the account ID and PIN before performing one of three operations — balance inquiry, deposit, or withdrawal — and handles edge cases such as wrong PIN, insufficient funds, and non-existent accounts.

---

## How to Run

Make sure Python 3 is installed. For Q3, install the required library first:

```bash
pip install nepali-datetime
```

Then run any program individually:

```bash
python week4_q1_billing.py
python week4_q2_water_level.py
python week4_q3_date_converter.py
python week4_q4_word_frequency.py
python week4_q5_atm.py
```
