# Program Description

This program is a command-line application that allows users to track their learning progress in different subjects. It provides various options to manage and update the information about the subjects the user is studying.

## How to Use

1. Run the `DerechClass` class, which contains the main method, to start the program.
2. The program will display a menu with different options.
3. Enter the corresponding letter to select an option and press Enter.
4. Follow the instructions provided by the program to interact and navigate through the options.

## Program Features

### Home Page
- Displays the user's name.
- Provides options to:
  - View limud progress.
  - Update limud progress.
  - Delete a Limud.
  - End the program.

### View Limud Progress
- Displays the user's name and all the limud information.
- Press Enter to go back to the home page.

### Update Limud Progress
- Displays the user's current limud information.
- Prompts for the name of the ספר (book) to update the progress.
- Prompts for the page/daf number the user has reached.
- Updates the progress and displays the updated completion percentage.

### Delete a Limud
- Displays the user's current limud information.
- Prompts for the name of the ספר (book) to delete.
- Deletes the selected limud from the list and confirms the deletion.

### End Program
- Exits the program.

## Limud Class
The `Limud` class represents a specific subject of study. It contains the following attributes:
- `type`: The type of limud, such as תנך, משנה, גמרא, מחשבה, or other.
- `category`: The category of the limud, such as סדר (for משנה and גמרא) or ספר (for תנך and מחשבה).
- `book`: The name of the specific book or מסכתא being studied.
- `quantity`: The total quantity or number of pages/dapim to cover in the limud.
- `amountComplete`: The current progress or number of pages/dapim completed.

The class provides getters and setters for each attribute and overrides the `toString()` method to display the limud information based on its type.

Please note that this program is a command-line application and relies on user input through the console.
