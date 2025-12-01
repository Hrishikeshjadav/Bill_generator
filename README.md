🧾 Python Billing System (with CSV Export & Table Format)

This project is a simple and efficient billing system written in Python.
It lets users:

Add multiple items (name, quantity, price)

Automatically calculate totals

Apply GST (default 18%)

Display the bill in normal view or formatted table view

Optionally auto-save bills as CSV

Generate timestamped CSV bills

🚀 Features
✔ Add Unlimited Items

Each item includes:

Serial Number

Item Name

Quantity

Price

Total (qty × price)

✔ Two Bill Display Modes

Simple Text Format

Clean ASCII Table Format

Example (table mode):

+-------+-----------+-----+--------+--------+
| Sr.no | Name      | Qty | Price  | Total  |
+-------+-----------+-----+--------+--------+
| 1     | Apple     | 2   | 50.00  | 100.00 |
| 2     | Banana    | 1   | 30.00  | 30.00  |
+-------+-----------+-----+--------+--------+
Subtotal: 130.00
GST(18%): 23.40
Grand Total: 153.40

✔ Auto manual CSV Export

When enabled, every bill is saved as:

bill_YYYYMMDD_HHMMSS.csv
