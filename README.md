# JavaFX-XML-ContactManager

A simple and clean **JavaFX application** for managing a contact list using an **XML file** as the data source. This project demonstrates the use of the **MVC (Model-View-Controller)** architecture, with basic CRUD functionality integrated into a JavaFX UI.

## Features

- View, add, delete, and navigate through contacts  
- Save and load contacts to/from `contacts.xml`  
- Clean and minimal UI using JavaFX  
- Fully structured with **MVC design principles**  
- Uses Java's **DOM API** for XML parsing and generation  

## Technologies Used

- Java 17 or higher  
- JavaFX  
- XML (DOM Parser)  

## Getting Started

### Prerequisites

- Java 17 or later installed  
- JavaFX SDK installed and configured in your IDE or build tool  

### Running the Application

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/JavaFX-XML-ContactManager.git
    ```
2. Open the project in your favorite IDE (e.g., IntelliJ IDEA, Eclipse) and ensure JavaFX is properly configured.  
3. Run the `Contact` class which contains the `main` method and launches the JavaFX application.  
4. Use the UI buttons to load contacts from the XML, add new contacts, delete existing ones, and save changes back to the XML file.  

## Project Structure

- **ModelContact.java**: Contact model with properties for name and contact number.  
- **ContactController.java**: Handles UI logic, data loading/saving, and contact list management.  
- **Contact.java**: JavaFX Application class that builds the UI and connects the controller.  

## How to Use

- Use the `load` button to load contacts from the `contacts.xml` file (should be placed in the working directory).  
- Navigate contacts using the `<<` (previous) and `>>` (next) buttons.  
- Add new contacts by filling the text fields and clicking the `+` button.  
- Delete the currently displayed contact with the `delete` button.  
- Save your contact list to `contacts.xml` using the `save` button.  


