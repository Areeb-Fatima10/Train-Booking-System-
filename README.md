# Train-Booking-System-
# 🚆 Train Booking System in C++

## 📌 Project Description

This is a basic **Train Booking System** implemented in C++. It allows users to:

- Select from 3 bogies (A, B, or C)
- View available seats
- Book any vacant seat by specifying row and column
- Display final seat layout after booking

The system is fully console-based and uses a 2D array to represent seats in each bogie.

---

## 🧠 Features

- Seat layout for each bogie displayed with rows and columns.
- Seats are marked:
  - `'V'` for **Vacant**
  - `'B'` for **Booked**
- Prevents double booking of a seat.
- Supports multiple bookings in one run.
- Final layout is shown after user exits.

---

## 🗂️ Structure

Each bogie has:
- 10 rows
- 4 columns
- Total: **40 seats per bogie**
- Total bogies: **3** (`A`, `B`, `C`)

---

## ▶️ How to Run

1. **Save the code** in a file named `main.cpp`.
2. **Compile** using any C++ compiler:

   ```bash
   g++ main.cpp -o trainbooking
