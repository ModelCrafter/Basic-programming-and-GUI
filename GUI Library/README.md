# Library Management Application

This application is a Python-based GUI program for managing a personal library. It allows users to add, edit, search, and sort books using an interactive interface built with Tkinter. Below are the features and functionalities of the application.

## Features

### 1. **Add Books**
   - Users can add new books to the library by specifying:
     - Book Name
     - Writer's Name
     - Book Size
     - Book Type
   - The data is stored in a JSON file (`books.txt`).

### 2. **Edit Books**
   - Edit the details of an existing book, including:
     - Book Name
     - Writer's Name
     - Book Size
     - Book Type

### 3. **Search Books**
   - Search for a book by its name or ID.
   - Displays detailed information about the book if found.

### 4. **Sort Books**
   - Sort books alphabetically by their names or by the writer's name.

### 5. **Dynamic Display**
   - Books are displayed dynamically in a scrollable canvas.
   - Books are categorized by letters or writers based on the sorting method.

### 6. **GUI Elements**
   - **Labels**: Display information and guide the user.
   - **Entry Fields**: Collect input from the user.
   - **Buttons**: Trigger actions like adding, sorting, and searching.
   - **Checkboxes**: Allow users to choose sorting criteria.
   - **Canvas**: Used for dynamically displaying books.

### 7. **Error Handling**
   - Provides error messages for invalid or incomplete inputs.
   - Alerts users when a book is not found during a search.

## Files

### 1. `books.txt`
   - A JSON file that stores all book data in the following format:
     ```json
     [
         ["book_name", "writer_name", "book_size", "book_type"]
     ]
     ```

### 2. `some_constants.py`
   - Contains constants used in the application, such as colors and font styles.

### 3. `tests.py`
   - Includes helper functions for sorting or other utility tasks.

## How It Works

### Initialization
- The application initializes by loading existing data from `books.txt`.
- Book IDs and writer lists are dynamically generated.

### Adding Books
- Users input details in the add book window.
- The book is appended to `books.txt` and displayed in the main canvas.

### Editing Books
- Users specify the book name they want to edit.
- Updated details are saved back to `books.txt`.

### Searching
- Users can search by book name or ID.
- The result is displayed on the canvas.

### Sorting
- Sorting is handled dynamically using the criteria selected by the user (alphabetical or by writer).

## GUI Components

### Main Window
- **Title**: Displays "My Library".
- **Developer Label**: Credits the developer.
- **Book Count**: Shows the total number of books.
- **Search Bar**: Allows book search by name or ID.
- **Buttons**: Add and sort books.
- **Canvas**: Scrollable area to display book details.

### Add Book Window
- Entry fields for book details.
- Save button to add the book to the library.

### Edit Book Window
- Entry field to specify the book to edit.
- Entry fields for updated details.
- Save button to apply changes.

## Usage

1. Run the script.
2. Use the "Add a new book" button to add books to the library.
3. Use the search bar to find books by name or ID.
4. Use the "Sort books" button to organize the display by letters or writers.
5. Edit book details using the shortcut `Ctrl+E`.

## Requirements

- Python 3.x
- Tkinter (comes pre-installed with Python)
- JSON (standard Python library)

## License
This project is licensed under the Apache License 2.0.

## Developer
***Youssef Khaled***   



