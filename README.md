# Shopping List App

Welcome to the Shopping List App! This React Native application allows you to manage your shopping list by adding and deleting items. The app features a simple and intuitive user interface.

## Features

- **Add Items**: Easily add items to your shopping list.
- **Delete Items**: Remove items from your list when they are purchased or are no longer needed.
- **Alert for Empty Item**: Receive an alert when attempting to add an empty item.

## Getting Started

To get started with the Shopping List App:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shopping-list-app.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the application:
   ```bash
   npm start
   ```

4. Open the app on your emulator or device.

## Usage

1. **Add an Item**:
   - Type the name of the item in the provided input field.
   - Press the "Add" button to add the item to your shopping list.

2. **Delete an Item**:
   - Swipe left on an item to reveal the delete button.
   - Press the delete button to remove the item from your list.

3. **Alert for Empty Item**:
   - If you attempt to add an empty item, an alert will prompt you to enter a valid item name.

## Components

- **Header Component**:
  - Displays the title "Shopping List" at the top of the app.

- **ListItem Component**:
  - Represents each item in the shopping list.
  - Allows users to delete an item by swiping left.

- **AddItem Component**:
  - Provides an input field to enter the name of the item to be added.
  - Allows users to add an item to the shopping list.

## Code Overview

The main functionality of the app is implemented in the `App.js` file. It uses the state hook to manage the list of items and provides functions for adding and deleting items. The components `Header`, `ListItem`, and `AddItem` are used to structure the app's UI.

Feel free to explore, customize, and enhance the app based on your preferences.

Happy shopping! 🛒✨
