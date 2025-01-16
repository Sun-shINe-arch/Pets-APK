# ![ic_launcher](https://github.com/user-attachments/assets/ae4c74f2-5916-4bf4-b8ab-2c81a317c98b)   Pet Shelter App

This is a simple Android application designed to manage a pet shelter. The app allows users to add, edit, and delete pet records in a SQLite database. Users can also view a list of pets and their details, including name, breed, gender, and weight.

## Features

- **Catalog View**: Display a list of pets with their name and breed.
- **Add New Pet**: Insert new pet records using a floating action button.
- **Edit Pet**: Update pet details such as name, breed, gender, and weight.
- **Delete Pet**: Delete a pet record from the database.
- **Gender Selection**: Choose a pet's gender from a spinner (Male, Female, Unknown).
- **SQLite Database**: The app uses SQLite for storing pet data locally.

## Screenshots

Include any relevant screenshots here to showcase the app's interface and functionality.

## Technologies Used

- **Android**: Java for app development.
- **SQLite**: Local database to store pet information.
- **Content Providers**: To manage and access pet data.
- **CursorAdapter**: Used to display pet records in a `ListView`.

## Project Structure

1. **Activities**:
    - `CatalogActivity`: Displays the list of pets.
    - `EditorActivity`: Allows adding and editing pet details.

2. **Data**:
    - `PetContract`: Defines the structure of the pet database.
    - `PetDbHelper`: Helper class to manage database creation and version management.
    - `PetCursorAdapter`: Custom adapter to bind data from the database to the list view.

3. **UI**:
    - `activity_catalog.xml`: Layout for the main catalog view.
    - `activity_editor.xml`: Layout for the pet editor view.
    - `list_item.xml`: Layout for individual pet list items.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/pet-shelter-app.git
    ```

2. Open the project in Android Studio.

3. Build and run the app on your Android device or emulator.

## Usage

- On the main catalog page, you can see a list of pets. You can click on any pet to edit its details.
- Use the floating action button to add a new pet.
- In the pet editor, enter details such as name, breed, weight, and gender.
- You can save or delete pet entries from the editor screen.

## Contributing

Feel free to fork this repository and submit pull requests if you have improvements or bug fixes to contribute.
contact : mk7581505@gmail.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

