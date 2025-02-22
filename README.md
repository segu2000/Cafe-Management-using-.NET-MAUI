
# Cafe Management System

## 📌 Overview

The **Cafe Management System** is a user-friendly application designed to streamline the billing process in restaurants. Built using **.NET MAUI**, it provides a structured and interactive way to order food, calculate bills, generate receipts, and maintain financial records. The app follows the **MVVM (Model-View-ViewModel) architecture** and stores billing data using **SQLite** for future reference.

## 🎯 Features

- **Main Page**: Displays a menu using a **Grid Layout**, where users can select food items.
- **Billing Page**: Organizes and displays the bill dynamically using MVVM, allowing users to add/remove items.
- **Final Page**: Shows the total price, a unique order number, and options for **New Customer** and **Print Bill**.
- **Database Storage**: Uses **SQLite** to store billing records for future reference.
- **Financial Management**: Includes an earnings calculation feature to track total revenue at the end of the day.

## 📸 Screenshots

![Picture8](https://github.com/user-attachments/assets/71b8e289-896a-494d-858b-1e9139f7586f)
![Picture7](https://github.com/user-attachments/assets/381c15ec-f985-40ab-a6b7-5e67ba08a517)
![Picture6](https://github.com/user-attachments/assets/102e80e5-6b85-4beb-aeec-9e1277b70f0d)
![Picture5](https://github.com/user-attachments/assets/e7426049-8588-4918-9ba5-b32bad422568)
![Picture4](https://github.com/user-attachments/assets/0162c504-3abf-40a2-a50d-62b55bdaf2db)
![Picture3](https://github.com/user-attachments/assets/7d5ac449-4422-4c2d-8c47-9482316e026a)
![Picture2](https://github.com/user-attachments/assets/d53e3858-c3e2-4db0-b303-93ae73176466)
![Picture1](https://github.com/user-attachments/assets/8171d224-1518-4349-8610-3250db084633)


## 🚀 Installation & Setup

### Prerequisites

Before running the project, ensure you have the following installed:

- **.NET MAUI SDK** (for cross-platform development)
- **Visual Studio** (with .NET MAUI workload installed)
- **SQLite** (included in .NET MAUI)

### Steps to Run the Project

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Open the Project in Visual Studio**
   - Launch **Visual Studio** and open the project folder.
   - Ensure you have the **.NET MAUI workload** installed.

3. **Restore Dependencies**
   ```sh
   dotnet restore
   ```

4. **Run the Application**
   - For Android:
     ```sh
     dotnet build -t:Run -f net7.0-android
     ```
   - For Windows:
     ```sh
     dotnet build -t:Run -f net7.0-windows
     ```

5. **Use the Application**
   - Select food items from the **Main Page**.
   - View and modify the order on the **Billing Page**.
   - Complete the order and print receipts from the **Final Page**.

## 📂 Project Structure

```
/DiningEstablishmentInvoiceSystem
│── /Views         # UI pages (Main, Billing, Final)
│── /ViewModels    # MVVM logic for data handling
│── /Models        # Data structures
│── /Database      # SQLite integration
│── /Resources     # Assets (icons, images)
│── /Services      # Business logic
│── App.xaml       # Application entry point
│── MainPage.xaml  # Main Page UI
│── Program.cs     # Startup logic
└── README.md      # Project documentation
```

## 📝 Usage Guide

- **Select food items** using checkboxes.
- **View the total** amount, including tax.
- **Generate a receipt** showing order details, date, and price.
- **Save, print, or copy** the receipt for records.
- **Access previous receipts** using the "Open" option.
- **Reset the app** for a new customer.
- **Exit the app** when done.

## 🛠️ Technologies Used

- **.NET MAUI** - Cross-platform framework
- **C#** - Backend logic
- **MVVM** - Architecture pattern
- **SQLite** - Database for storing invoices

## 🤝 Contributors

- **Hemateja Segu**
- **Bhanu Prakash Murala**
- **Venkata Bharath Chandra Bapanapalli**
