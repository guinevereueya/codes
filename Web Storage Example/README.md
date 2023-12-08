# Web Storage Example

This HTML file demonstrates a simple web storage application using the Local Storage feature in web browsers. The application allows you to enter data, store it in local storage, recall the stored data, and reset the storage.

## Usage

1. Open the HTML file in a web browser.
2. Enter data in the input field under the "Enter Data" section.
3. Click the "Store Data" button to store the entered data in local storage.
4. Click the "Recall Data" button to retrieve and display the stored data.
5. Click the "Reset" button to remove the stored data.

## Code Overview

- **`store()`:** Stores the entered data in local storage and updates the legend text.

- **`recall()`:** Retrieves and displays the stored data from local storage.

- **`remove()`:** Removes the stored data from local storage and updates the legend text.

- The `localStorage` API is utilized for storing, recalling, and removing data.

Feel free to customize the script based on your requirements or integrate it into more complex web applications.

**Note:** Web storage is specific to each browser and domain. The stored data persists even if the browser is closed and reopened.
