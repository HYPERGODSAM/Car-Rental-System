# 🚗 Car Rental System (Java Console Application)

A simple yet functional **Car Rental System** developed in **Java** that simulates the rental process for cars. This console-based project allows customers to rent and return cars while managing rental records dynamically.

## 🛠️ Features

- 📋 **Add Cars and Customers**
- 🔄 **Rent a Car**
- ✅ **Check Car Availability**
- 📆 **Calculate Rental Cost Based on Days**
- 🧾 **Rental Summary Confirmation**
- 🔁 **Return a Car**
- 🗂️ **Track Active Rentals**
- 🖥️ **Console-Based Interactive Menu**

## 💻 Technologies Used

- Java (JDK 8+)
- OOP Principles (Encapsulation, Classes, Lists)

## 📂 Project Structure

```
CarRentalSystem/
│
├── Main.java                # Entry point of the program
├── Car.java                 # Car class with availability and pricing
├── Customer.java            # Customer information
├── Rental.java              # Rental record for tracking
└── CarRentalSystem.java     # System logic and user interaction
```

## 🚀 How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/CarRentalSystem.git
   cd CarRentalSystem
   ```

2. **Compile the Code**

   ```bash
   javac Main.java
   ```

3. **Run the Application**

   ```bash
   java Main
   ```


## 📌 Sample Flow

- Start the program and choose to rent or return a car.
- When renting:
  - Enter your name.
  - Choose a car ID from available cars.
  - Enter the rental duration.
  - Review rental info and confirm.
- When returning:
  - Provide the car ID to return it.

## 📈 Future Enhancements

- GUI-based interface (using Swing or JavaFX)
- Persistent storage (database or file-based)
- Admin dashboard to manage fleet and rentals
- More detailed billing with tax and discount options

## 🤝 Contributing

Feel free to fork this repo and submit a pull request for suggestions or improvements!
