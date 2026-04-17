# Number-System
🎯 Objective

This program converts a decimal number into:

Binary (Base 2)
Octal (Base 8)
Hexadecimal (Base 16)

It is a simple console-based project useful for understanding number systems and logic building in C.

🧠 Concepts Used
Arrays (char arr[])
Loops (for)
Conditional statements (if-else)
ASCII value conversion
String functions (strrev)
Basic arithmetic operations
⚙️ Program Working
🔹 1. Menu Display

The program shows options:

1. Decimal to Binary
2. Decimal to Octal
3. Decimal to Hexadecimal
4. Exit
User selects option using getch()
🔹 2. Decimal to Binary
Logic:
Divide number by 2
Store remainder (0 or 1)
Repeat until number becomes 0
Store digits in array
Reverse using strrev()

👉 Example:
Decimal 10 → Binary 1010

🔹 3. Decimal to Octal
Logic:
Divide number by 8
Store remainder (0–7)
Reverse result

👉 Example:
Decimal 10 → Octal 12

🔹 4. Decimal to Hexadecimal
Logic:
Divide number by 16
Remainder:
0–9 → digits
10–15 → A–F
ASCII conversion used:
+48 → numbers
+55 → letters

👉 Example:
Decimal 255 → Hex = FF

🔹 5. Looping Feature
After execution:
User can continue by pressing 1
Program restarts using main()
📂 Important Variables
Variable	Purpose
n	Input decimal number
temp	Stores original number
arr[]	Stores converted result
i	Index for array
c	User choice
🔄 Program Flow
Show menu
Take user input
Perform selected conversion
Display result
Ask user to continue
🚀 Key Features

✔ Multiple number conversions
✔ Simple logic (division method)
✔ Uses ASCII for character conversion
✔ User-friendly menu

⚠️ Limitations
Uses conio.h (not portable)
Uses strrev() (not standard in GCC)
No input validation
Uses recursion (main()), not recommended
📈 Future Improvements
Replace strrev() with manual reverse
Use loop instead of main() recursion
Add negative number support
Add binary → decimal conversion
Make menu continuous using while loop
🧾 Conclusion

This project is a basic yet powerful example of how number systems work internally in computers.
It helps build strong fundamentals in:

Logic building
Loop handling
Data representation
