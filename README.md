# Library Management System (LMS)

This Python program implements a simple Library Management System (LMS) using a command-line interface. The system allows users to manage a list of books, issue books, add new books, return books, and display the current list of books.

## How to Run:

1. **Run the Program:**
   - Save the provided code in a file, e.g., `library_management_system.py`.
   - Open a terminal or command prompt.
   - Navigate to the directory containing the file.
   - Run the program using the command:
     ```bash
     python library_management_system.py
     ```

2. **Interact with the LMS:**
   - Follow the on-screen instructions to navigate through the LMS options.
   - Enter the corresponding key for the desired operation (Display Books, Issue Books, Add Books, Return Books, Quit).

## Features:

- **Display Books:**
  - Displays the current list of books along with their status (Available or Already Issued).

- **Issue Books:**
  - Allows users to issue a book by entering the book's ID.
  - Checks if the book is available and issues it to the user, updating the book's status and lending details.

- **Add Books:**
  - Adds new books to the library by entering the title.
  - Validates the title length and ensures it does not exceed the limit of 20 characters.

- **Return Books:**
  - Allows users to return a previously issued book by entering the book's ID.
  - Updates the book's status, lender name, and lending date.

- **Quit:**
  - Exits the LMS.

## Notes:

- The LMS is implemented with a simple text file (`list_of_books.txt`) to store book titles.
- The lending details and book status are maintained in a Python dictionary (`books_dict`).
- Users interact with the LMS through a command-line interface.

## Developer:

- This Library Management System was developed by an anonymous contributor.
