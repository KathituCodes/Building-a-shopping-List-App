# Building-a-shopping-List-App

## Objective
This program allows users to manage their shopping list by adding, removing, and viewing items. It implements various Python data structures and control flow mechanisms to ensure an interactive experience.

## Features
- Add items to the shopping list (with a limit on the number of items).
- Remove items from the shopping list.
- View the current shopping list.
- Utilize Python's list, tuple, set, and dictionary data structures for efficient data management.

## Implementation Details
### Data Structures Used
- **List**: Stores the shopping items.
- **Tuple**: Used for immutable data scenarios.
- **Set**: Helps to prevent duplicate entries.
- **Dictionary**: Could be used to store item names and their corresponding quantities.

### Program Flow
1. The program initializes an empty shopping list.
2. A while loop presents a menu with the following options:
   - Add an item.
   - Remove an item.
   - View the shopping list.
   - Exit the program.
3. The user selects an option, and the program performs the corresponding action.
4. A for loop iterates through the list when displaying items.
5. The `range()` function is used to limit the number of items that can be added.
6. Error handling ensures users enter valid inputs.

## How to Run the Program
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/shopping-list-manager.git
   ```
2. Navigate to the project directory:
   ```bash
   cd shopping-list-manager
   ```
3. Run the script:
   ```bash
   python shopping_list.py
   ```

## Example Usage
```
Welcome to the Shopping List Manager!
1. Add Item
2. Remove Item
3. View List
4. Exit
Choose an option: 1
Enter item to add: Apples
Item added successfully!
```
## Contributing
Feel free to fork this repository, create a new branch, and submit a pull request with improvements!



