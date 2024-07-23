
# Grocery Bud JS Web App

Grocery Bud is a simple web application for managing a grocery list. It allows users to add, edit, delete, and clear grocery items. The application uses HTML, CSS, and JavaScript to create an interactive and user-friendly interface.

## How the web page looks like:

![Screen Shot 2024-07-23 at 18 43 38](https://github.com/user-attachments/assets/89bc618b-d10f-43e2-9d4f-8314d6bee3c1)



## Features

- **Add Items**: Enter grocery items and add them to the list.
- **Edit Items**: Modify items in the list.
- **Delete Items**: Remove individual items from the list.
- **Clear All Items**: Remove all items from the list at once.
- **Local Storage**: Stores the grocery list in the browser's local storage to persist data across sessions.

## Table of Contents

- [Usage](#usage)
- [Code Overview](#code-overview)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Usage

1. **Add Grocery Items**:

   - Enter a grocery item into the input field and click the "Submit" button to add it to the list.

2. **Edit Grocery Items**:

   - Click the edit button (pencil icon) next to an item to modify it.

3. **Delete Grocery Items**:

   - Click the delete button (trash can icon) next to an item to remove it.

4. **Clear All Items**:

   - Click the "Clear Items" button to remove all items from the list.

## Code Overview

### `index.html`

- **Purpose**: Contains the structure of the web application, including the form for adding items, the list container, and the clear button.
- **Key Components**:
  - A form for submitting new grocery items.
  - A container for displaying the list of items.
  - Buttons for clearing the list and for each item’s edit and delete functions.

### `styles.css`

- **Purpose**: Provides styling for the Grocery Bud application to enhance its appearance.
- **Key Features**:
  - Responsive design with media queries.
  - Various CSS variables for color and spacing consistency.
  - Styling for buttons, alerts, and the grocery list.

### `grocery_bug.js`

- **Purpose**: Implements the functionality of the Grocery Bud application using JavaScript.
- **Key Features**:
  - Handles form submission and item addition.
  - Manages item editing and deletion.
  - Clears all items and manages local storage operations.
  - Provides feedback to the user via alerts.

#### Key Functions:

- `addItem(e)`: Adds a new item or edits an existing one.
- `displayAlert(text, action)`: Displays an alert message to the user.
- `clearItems()`: Removes all items from the list.
- `deleteItem(e)`: Deletes a specific item from the list.
- `editItem(e)`: Enables editing for a specific item.
- `setBackToDefault()`: Resets the form and flags.
- `addToLocalStorage(id, value)`: Adds an item to local storage.
- `removeFromLocalStorage(id)`: Removes an item from local storage.
- `getLocalStorage()`: Retrieves items from local storage.

## Project Structure

- `index.html`: The main HTML file that includes the structure of the application.
- `styles.css`: The stylesheet that defines the look and feel of the application.
- `grocery_bug.js`: The JavaScript file that contains the logic for adding, editing, deleting, and managing grocery items.

## Contributing

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please submit a Pull Request. Ensure that your contributions are well-documented and tested.

