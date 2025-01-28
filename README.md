# StudentRegistryPom

## Overview
**StudentRegistryPom** is a Page Object Model (POM) structured project designed for testing the student registry system. It utilizes a modular approach for UI automation, ensuring maintainability and scalability.

## Project Structure
The project is organized into two main folders:

### 1. **Pages**
This folder contains the page object classes that represent different sections of the application:
- **AddStudent.cs** - Handles interactions with the "Add Student" page.
- **BasePage.cs** - A base class containing shared functionality for all pages.
- **HomePage.cs** - Represents the main homepage of the application.
- **ViewStudents.cs** - Manages interactions with the "View Students" page.

### 2. **PageTests**
This folder contains the test classes that validate the functionality of the pages:
- **AddStudentsPageTests.cs** - Tests for the "Add Student" page.
- **BaseTests.cs** - A base test class with shared setup and teardown logic.
- **HomePageTests.cs** - Tests for the homepage.
- **ViewStudentsPageTests.cs** - Tests for the "View Students" page.

## Technologies Used
- **C#**
- **Selenium WebDriver**
- **NUnit/xUnit** (or another testing framework if applicable)

## Setup & Execution
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/StudentRegistryPom.git
   ```
2. Navigate to the project directory:
   ```sh
   cd StudentRegistryPom
   ```
3. Restore dependencies:
   ```sh
   dotnet restore
   ```
4. Run the tests:
   ```sh
   dotnet test
   ```
