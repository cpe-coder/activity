# School Cafeteria Management System

## Problem Description

The school cafeteria wants to automate its billing system. Students can buy multiple items in one transaction, and the system should calculate the total bill, apply discounts if applicable, and display a receipt.

Your task is to write a **C# program** to simulate the school cafeteria billing system.

---

## Problem Statement

Write a C# program to simulate the school cafeteria billing system. The program should do the following:

1. **Display Menu:**  
   Display the following menu of available food items and their prices:

   - **Burger** - 50
   - **Fries** - 30
   - **Soda** - 20
   - **Sandwich** - 40

2. **Accept User Input:**

   - Allow the user to select items by entering the item number (e.g., `1` for Burger, `2` for Fries, etc.).
   - Prompt the user to enter the **quantity** for the selected item.
   - Use an **array** or **List** to store item prices and names.

3. **Calculate Total Cost:**  
   Compute the total cost of the selected items. If the total exceeds `200`, apply a **5% discount** to the total.

4. **Display Receipt:**  
   Show a receipt that includes:

   - Each item purchased with its **quantity** and **total price**.
   - The **total bill** before and after applying the discount (if applicable).

5. **Exit Option:**  
   Allow the user to exit the program by entering `0` when prompted for an item number.

---

## Sample Input/Output

### Example 1: No Discount

#### **Input:**

```cmd
Welcome to the School Cafeteria!

Menu:
1. Burger - 50
2. Fries - 30
3. Soda - 20
4. Sandwich - 40

Enter the item number (or 0 to finish): 1
Enter the quantity: 2
Enter the item number (or 0 to finish): 3
Enter the quantity: 3
Enter the item number (or 0 to finish): 0

```

### **Output:**

```cmd
Receipt:
Item         Quantity       Total
Burger       2             100
Soda         3             60

Total before discount: 160
Discount applied: 0
Final total: 160

```

### If Discount Apply

```cmd
Receipt:
Item         Quantity       Total
Burger       3             150
Fries        2             60

Total before discount: 210
Discount applied: 5
Final total: 189

```

## Requirements

1. Use **arrays** or **List** to store item details.
2. Use **loops** for user input and calculations.
3. Use **if-else** statements for discount logic.
4. Ensure the receipt output is neatly formatted.
