# Pharmacy Management System

This is a comprehensive **Pharmacy Management System** built using Python and the `customtkinter` library for the graphical user interface (GUI). The system is designed to manage various aspects of a pharmacy, including medicine inventory, sales, suppliers, financial reporting, and more. It integrates with a MySQL database to store and retrieve data efficiently.

---

## Features

### 1. **Medicine Management**
   - **Add New Medicine**: Add new medicines to the inventory with details such as medicine ID, supplier ID, company name, quantity, expiry date, and more.
   - **Edit Medicine**: Modify existing medicine details, including quantity, expiry date, and pricing.
   - **Medicine Stock Report**: View the current stock of medicines, including low stock and out-of-stock items.
   - **Medicine Expiry Report**: Track medicines that are expiring soon or have already expired.

### 2. **Supplier Management**
   - **Add New Supplier**: Add new suppliers with details such as supplier ID, name, contact person, phone, email, and address.
   - **Edit Supplier**: Update supplier information.
   - **View Suppliers**: View a list of all suppliers with their details.

### 3. **Sales and Billing**
   - **Sales and Billing Interface**: A user-friendly interface to manage sales, including adding medicines to the bill, applying discounts, and calculating the total amount.
   - **Print Bill**: Generate and print bills for customers with details of the purchased medicines, total amount, discount, and change.

### 4. **Reporting**
   - **Added Medicines Report**: View a report of all medicines added to the inventory, filtered by date range.
   - **Sold Medicines Report**: Track all sales transactions, including details of the medicines sold, quantity, price, and total amount.
   - **Shifted Medicines Report**: View a report of medicines that have been shifted from one location to another.
   - **Profit Management**: Generate profit reports, including detailed profit analysis and actual profit calculations.

### 5. **Finance Management**
   - **Add New Bill**: Create new financial transactions.
   - **Edit Bill**: Modify existing financial transactions.
   - **Bill Report**: Generate reports of all financial transactions.

### 6. **Return Management**
   - **Add New Refund**: Manage refunds for returned medicines.
   - **Medicine Refund Report**: Generate reports of all refunds processed.

---

## Installation

### Prerequisites
- **Python 3.x**: Ensure Python 3.x is installed on your system.
- **MySQL Server**: A MySQL database is required to store the application data.
- **Libraries**: Install the required Python libraries.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/arslanraza23cit111/pharmacy-management-system.git
   cd pharmacy-management-system
