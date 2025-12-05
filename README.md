# shopping-list
🛒 Shopping List App (Python)

A simple, interactive command-line Shopping List Application built using Python.
This project is perfect for beginners who want to practice:

Lists

Loops

Functions

File handling

Basic CRUD operations

🚀 Features

✔️ View all items in the shopping list
✔️ Add items
✔️ Remove items
✔️ Edit/Update items
✔️ Save the list to a file
✔️ Clear the entire list
✔️ Exit the program

📌 How It Works

The app runs in a loop and displays a menu with multiple options.
Users can choose an option from 1 to 7 to interact with their shopping list.

📷 Menu Preview
---- Shopping List Menu ----
1. View list
2. Add item to list
3. Remove item from list
4. Edit the list
5. Save the list
6. Clear List
7. Quit

🧿 Code Overview

shopping_list = [] → initializes an empty list

show_menu() → prints the main menu

Uses while loop to continuously take user input

Uses file handling (open, write) to save items to a text file

📝 Saving the List

When the user selects option 5, the program asks for a filename.
The list items are saved one per line in the specified file.

Example:

Enter the filename to save the list: mylist.txt

▶️ How to Run

Install Python (if not already installed):
https://www.python.org/downloads/

Download or clone this repository:

git clone https://github.com/<your-username>/shopping-list-app.git


Run the script:

python shopping_list.py

📂 Project Structure
shopping-list-app/
│
├── shopping_list.py     # Main program
└── README.md            # Documentation

✨ Future Improvements (Optional Ideas)

Add search functionality

Prevent duplicate items

Save automatically on exit

Add load feature to restore a saved list

Convert to GUI using Tkinter or PyQt

🤝 Contributing

Feel free to contribute by adding new features or improving the code.
Pull requests are welcome!

🧑‍💻 Author

Sivamani Muppalla
GitHub: https://github.com/Siva-ops-coder

LinkedIn: https://linkedin.com/in/sivamanichowdary
