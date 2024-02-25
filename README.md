# Hospital Management System

This Java-based Hospital Management System simulates basic functionalities for managing patients, doctors, staff, bed occupancy, billing, and payments. The project is organized into multiple classes, each handling a specific aspect of hospital management.

## Classes:

1. **Patient:**
   - Collects patient information (name, gender, disease, admission status, age, phone number, ID).
   - Implemented as a thread to simulate concurrent patient submissions.

2. **Doctor:**
   - Collects doctor information (name, qualification, specialization, availability, ID).
   - Checks doctor availability for patient assignment.

3. **Hospital:**
   - Manages bed availability.
   - Provides a synchronized method (`occupyBed`) for bed assignment.

4. **Staff:**
   - Gathers staff details (ID, name, gender, age, designation, salary).
   - Implemented as a thread for concurrent staff submissions.

5. **Billing:**
   - Calculates patient bills based on charges (basic, additional, medication, room, doctor's fees).
   - Displays the bill details.

6. **Payment:**
   - Simulates payment with options for cash, UPI, or NetBanking.

7. **demo:**
   - Main class where program execution begins.
   - Implements a simple login system.
   - Allows users to manage patients, doctors, staff, bed occupancy, billing, and payments.

## Usage:

1. Run the program (`demo.java`).
2. Log in with the predefined username (`Itp@123`) and password (`Tech@123`).
3. Follow the menu to perform various actions within the hospital management system.

## Note:

- Uses multithreading for concurrent actions (patient and staff submissions).
- Includes basic error handling for user inputs.
- Billing and payment sections implemented as separate threads for asynchronous activities.

Feel free to explore and modify the code to suit your needs!

## How to Run:

```bash
# Compile the program
javac demo.java

# Run the compiled program
java demo
