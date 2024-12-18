# Task Manager

The **Task Manager** is a simple, responsive web application built using **Bootstrap 5.3.3**. It provides a user-friendly interface for managing tasks, including adding, viewing, editing, and organizing tasks. This project demonstrates practical usage of Bootstrap components, including navigation bars, modals, cards, tabs, breadcrumbs, and more.

## Features

- **Responsive Navbar**: A fully responsive, collapsible navigation bar for easy access to the app's sections.
- **Breadcrumb Navigation**: Clear hierarchical navigation for improved usability.
- **Task Management**:
  - Add tasks using a modal form.
  - Display tasks with status badges in a structured list.
- **Dropdown Actions**: Quick access to task operations such as editing, deleting, and marking as complete.
- **Tabbed Navigation**: Organized views for "All Tasks," "Completed Tasks," and "Pending Tasks."
- **Pagination**: Easy navigation through pages of tasks.
- **Tooltips and Popovers**: Additional contextual information with a clean UI.
- **Responsive Design**: Ensures usability across devices, from mobile to desktop.

## Built With

- **Bootstrap 5.3.3**: A CSS framework for responsive design.
- **HTML5**: Markup for structuring the content.
- **JavaScript**: Bootstrap's interactivity features such as tooltips, popovers, modals, and tabs.

## Live Demo

[View the Task Manager in Action](#)  
*(Add your hosted app link here)*

---

## Getting Started

### Prerequisites

To use this project, you need:

- A modern browser with JavaScript enabled.
- Internet access to load Bootstrap from the CDN.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/task-manager.git
   ```
2. Open the `index.html` file in your browser.

### Usage

1. **Navigate Tasks**: Use the navbar or breadcrumb to switch between sections.
2. **Add Tasks**: Click the "Add Tasks" button to open a modal form and enter task details.
3. **Manage Tasks**: Interact with task actions (Edit/Delete/Mark as Complete) using the dropdown.
4. **Tabs**: Use the tabs to filter tasks by their status.
5. **Pagination**: Move between pages using the pagination controls.
6. **Tooltips and Popovers**: Hover over buttons or click for additional information.

---

## Project Structure

```plaintext
Task Manager/
│
├── index.html          # Main HTML file
├── README.md           # Project documentation
├── assets/             # Directory for additional assets (e.g., images, custom CSS/JS)
│
└── cdn/                # Bootstrap and floating-ui loaded via CDN
```

---

## Key Bootstrap Components Used

1. **Navbar**: For primary navigation.
2. **Breadcrumb**: Provides hierarchical navigation.
3. **Modal**: To add tasks.
4. **Card**: For task list display.
5. **Dropdowns**: For task actions.
6. **Tabs**: To organize tasks into categories.
7. **Pagination**: To handle multiple pages.
8. **Tooltips and Popovers**: Enhance user interaction.

---

## Customization

### CSS
To apply custom styling, you can extend Bootstrap's default theme using a custom CSS file or by overriding Bootstrap variables using Sass.

### JavaScript
Extend functionality by integrating with backend frameworks like Node.js, Flask, or PHP for full CRUD operations.

---

## Known Issues

- **Form Validation**: Task forms currently lack real-time validation.
- **Static Data**: Task data is hardcoded; backend integration is required for persistent storage.

---

## Future Enhancements

1. **Dynamic Data**: Integrate with a backend or local storage for dynamic task management.
2. **Search and Filter**: Add search and advanced filtering capabilities.
3. **User Authentication**: Secure the app by adding user login/logout.
4. **Theme Customization**: Add light/dark mode support.

---

## Contributing

1. Fork the repository.
2. Create a new branch (`feature/your-feature-name`).
3. Commit your changes.
4. Push your branch and open a Pull Request.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Acknowledgments

- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [Floating UI Library](https://floating-ui.com/)
