# Employee Management System

This project is a simple Employee Management System built using HTML, CSS, and JavaScript. The application allows users to register employees, view a list of registered employees, and manage their details. The data is stored in the browser's local storage, ensuring persistence between sessions.

---

## Features

1. **Employee Registration**
   - Users can register new employees by filling out a form with the following details:
     - Name
     - Position
     - About
     - Joining Date
   - Upon submission, the employee data is saved to local storage.

2. **Employee List**
   - Displays all registered employees in a table format with the following columns:
     - Name
     - Position
     - About
     - Joining Date
   - Includes a delete button for each employee to remove them from the list.

3. **Local Storage**
   - The project uses local storage to store and retrieve employee data, ensuring persistence between browser sessions.

4. **Responsive Design**
   - The application is responsive and adapts to different screen sizes using CSS media queries.

5. **Dynamic Navigation**
   - Navigation links between the registration page and the employee list page.

---

## Project Structure

```plaintext
EmployeeManagement/ 
|-- index.html              # Employee Registration Page
|-- employee-list.html      # Employee List Page
|-- style.css               # Styling for the application
|-- src/
    |-- main.js             # JavaScript logic for the application
|-- postcss.config.js       # PostCSS configuration file
|-- package.json            # Project dependencies and scripts
```

---

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd EmployeeManagement
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open the application in your browser at `http://localhost:3000` (or the port displayed in the terminal).

---

## Usage

### Employee Registration
1. Open the application and navigate to the "Employee Registration" page.
2. Fill in the employee details and click **Submit**.
3. The employee will be added to the local storage and redirected to the "Employee List" page.

### Employee List
1. View all registered employees in a table.
2. Use the **Delete** button to remove an employee from the list.

---

## Screenshots

1. **Employee Registration Page**
   *(Add image of the registration page here)*

2. **Employee List Page**
   *(Add image of the employee list page here)*

---

## Technologies Used

- **HTML**: For the structure of the application.
- **CSS**: For styling and responsive design.
- **JavaScript**: For functionality, form handling, and local storage operations.
- **Vite**: For fast development and module bundling.

---

## Future Enhancements

- Add search functionality to filter employees by name or position.
- Implement sorting options for the employee list.
- Integrate a backend service for storing employee data persistently.
- Add form validation to ensure better data integrity.

---

## License

This project is licensed under the **MIT License**. Feel free to use and modify it as per your needs.
