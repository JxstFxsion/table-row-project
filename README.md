# Table Row Control Project

## 🔍 Overview
This project demonstrates basic HTML, CSS, and JavaScript to dynamically insert and delete rows in a table. It also includes a real-time message system to inform the user when the table is empty.

## 📂 Files Included

- **`table-assignment.html`**  
  Main file containing all HTML, styling, and JavaScript functionality. It:
  - Creates a table with 5 initial rows and 2 columns.
  - Includes two buttons: `Insert row` and `delete row`.
  - Adds new rows to the **bottom** of the table on click.
  - Deletes rows from the **top** of the table on click.
  - Displays a message `"No more rows to delete"` if the table becomes empty.
  - Hides the message once a new row is added again.

## 📌 What I Did

- Wrote the full HTML from scratch in **Notepad**.
- Implemented JavaScript functions to handle dynamic table manipulation.
- Used inline comments throughout the file to show understanding of each part.
- Made sure the behavior matched all screenshots from the assignment.
- Verified that:
  - Rows are inserted to the bottom (Figure 2).
  - Rows are deleted from the top (Figure 4).
  - Message appears when table is empty (Figure 6).
  - Message clears when a row is added (Figure 7).

## 🧠 What I Learned

- How to use `insertRow()` and `insertCell()` to add table rows dynamically.
- How to use `deleteRow(0)` to remove the first row in a table.
- How to update DOM elements with JavaScript (`innerText`, `getElementById()`).
- Importance of clear commenting for both personal understanding and assignment requirements.

## 💡 Sources

- All HTML, CSS, and JavaScript were written by me.
- Guidance and clarification were received through educational support conversations (e.g., ChatGPT).
- No external libraries or starter code were used.

## 👤 Author

- Austin W. Davis
- Created as part of a Lab Assignment on dynamic table manipulation using JavaScript.

