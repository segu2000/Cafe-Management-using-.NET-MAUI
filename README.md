# Cafe-Management-using-.NET-MAUI
📌 Overview
The Cafe Management System is a user-friendly application designed to streamline the billing process in restaurants. Built using .NET MAUI, it provides a structured and interactive way to order food, calculate bills, generate receipts, and maintain financial records. The app follows the MVVM (Model-View-ViewModel) architecture and stores billing data using SQLite for future reference.

🎯 Features
Main Page: Displays a menu using a Grid Layout, where users can select food items.
Billing Page: Organizes and displays the bill dynamically using MVVM, allowing users to add/remove items.
Final Page: Shows the total price, a unique order number, and options for New Customer and Print Bill.
Database Storage: Uses SQLite to store billing records for future reference.
Financial Management: Includes an earnings calculation feature to track total revenue at the end of the day.

📸 Screenshots

![Picture8](https://github.com/user-attachments/assets/470c396a-2828-48d6-9aa9-1bccbdc8f1ac)
![Picture7](https://github.com/user-attachments/assets/7cf9cc3c-b84e-46bb-b2ab-95d50dc83286)
![Picture6](https://github.com/user-attachments/assets/36822c00-7471-4df0-81e1-f01d3f09f219)
![Picture4](https://github.com/user-attachments/assets/8c1623a1-0139-49ca-af26-d7ff0f619e62)
![Picture3](https://github.com/user-attachments/assets/20ea8872-26e7-4b99-a23e-e3f14a623550)
![Picture2](https://github.com/user-attachments/assets/13de849e-561e-4555-856a-ec60028f3e0b)
![Picture1](https://github.com/user-attachments/assets/7a312a2f-9c3a-4013-a103-d119f651e6ef)


🚀 Installation & Setup
Prerequisites
Before running the project, ensure you have the following installed:

.NET MAUI SDK (for cross-platform development)
Visual Studio (with .NET MAUI workload installed)
SQLite (included in .NET MAUI)

Steps to Run the Project:
Clone the Repository

sh
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Open the Project in Visual Studio

Launch Visual Studio and open the project folder.
Ensure you have the .NET MAUI workload installed.
Restore Dependencies

sh
Copy
Edit
dotnet restore
Run the Application

For Android:
sh
Copy
Edit
dotnet build -t:Run -f net7.0-android
For Windows:
sh
Copy
Edit
dotnet build -t:Run -f net7.0-windows
Use the Application

Select food items from the Main Page.
View and modify the order on the Billing Page.
Complete the order and print receipts from the Final Page.


📂 Project Structure
bash
Copy
Edit
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

📝 Usage Guide
Select food items using checkboxes.
View the total amount, including tax.
Generate a receipt showing order details, date, and price.
Save, print, or copy the receipt for records.
Access previous receipts using the "Open" option.
Reset the app for a new customer.
Exit the app when done.

🛠️ Technologies Used
.NET MAUI - Cross-platform framework
C# - Backend logic
MVVM - Architecture pattern
SQLite - Database for storing invoices

🤝 Contributors
Hemateja Segu, 
Bhanu Prakash Murala, 
Venkata Bharath Chandra Bapanapalli
