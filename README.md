🏪 STOCK MANAGEMENT SYSTEM (C Programming)
📄 ABSTRACT

The Stock Management System is a terminal-based application written in C that allows users to manage store inventory efficiently. It provides essential functionalities such as adding items, displaying all items, searching by ID, updating item details, deleting items, and generating customer bills.

All stock information is handled in a dynamic in-memory structure using arrays, making the program simple, fast, and ideal for academic demonstrations of C programming fundamentals.

This project demonstrates key C programming concepts, including structures, arrays, functions, loops, conditionals, input validation, and menu-driven interfaces. It is well-suited for beginners, mini-projects, and academic lab submissions.

✨ FEATURES
🔧 Core Functionalities
➕ Add New Item

Stores:

Item ID

Name

Quantity

Price

📋 Display All Items

Shows all available items in a clean, formatted table.

🔍 Search Item

Search by Item ID
Displays full details if found.

✏ Update Item Details

Modify:

Name

Quantity

Price

❌ Delete Item

Removes an item by ID and rearranges the remaining list.

💰 Generate Bill

Allows purchasing items

Verifies stock quantity

Calculates total cost

Deducts purchased items from stock

🖥 Menu-driven CLI Interface

User-friendly and easy to navigate.

🛠 TECHNICAL REQUIREMENTS
🖥 System Requirements

Windows / Linux / macOS

Terminal or Command Prompt

Very low RAM usage (less than 2 MB)

No storage required (data is not saved permanently)

💻 Software Requirements

C Compiler: GCC / Clang / MSVC / MinGW

Code Editor: VS Code, Dev-C++, Code::Blocks, CLion, etc.

🔣 Programming Requirements

Language: C

Standard: C89 / C99 / C11

Required headers:

#include <stdio.h>
#include <string.h>

✔ Functional Requirements
1. User Interface

Fully terminal-based

Menu-driven

Easy to use

Displays confirmations & errors

2. Item Operations

Add new item to stock

Display all available stock

Search item by ID

Update item details (quantity, price, name)

Delete item using ID

Generate bill for purchased items

3. Data Management

Data stored in an in-memory array

Maximum 100 items allowed

No permanent storage (clears on exit)

4. Program Flow

Menu loop continues until the user selects Exit

Displays appropriate messages for success or failure

▶️ How to Run the Program
1. Compile the Program
gcc stock_management.c -o stock_management

2. Run the Program
Linux / macOS
./stock_management

Windows
stock_management.exe

🖼️ Screenshots

  Main Menu.
  

<img width="540" height="204" alt="Screenshot 2025-12-04 222301" src="https://github.com/user-attachments/assets/6987da31-6147-450e-9a28-24b0afd4b299" />



📥 Add Item


<img width="256" height="184" alt="Screenshot 2025-12-04 222431" src="https://github.com/user-attachments/assets/1632642d-d754-4ef6-9645-c28d61e9ddec" />



📋 Display All Items


<img width="480" height="177" alt="Screenshot 2025-12-04 222440" src="https://github.com/user-attachments/assets/3852a357-4dde-4d76-916c-cb750e99d703" />



🔍 Search Item


<img width="450" height="225" alt="Screenshot 2025-12-04 222447" src="https://github.com/user-attachments/assets/d3873905-6d1b-489f-800f-a8e683793a97" />



✏ Update Item


<img width="281" height="223" alt="Screenshot 2025-12-04 222546" src="https://github.com/user-attachments/assets/a0337439-69e3-40e1-b9e8-cfd20e2b8daa" />


❌ Delete Item


<img width="318" height="123" alt="Screenshot 2025-12-04 223419" src="https://github.com/user-attachments/assets/0d793f77-4b9d-4a82-94ff-7fa5ef4dd239" />



🧾 Generate Bill


<img width="251" height="258" alt="Screenshot 2025-12-04 223028" src="https://github.com/user-attachments/assets/fff20903-095f-43b1-9a62-5372db3a9f7f" />



🚪 Exit


<img width="230" height="69" alt="Screenshot 2025-12-04 223045" src="https://github.com/user-attachments/assets/079406fc-f6fc-4368-b62f-f7d7784dff19" />



