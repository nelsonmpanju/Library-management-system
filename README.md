# Library Management system

## Overview

Welcome to the Library Management App, a Frappe framework-based solution tailored for efficient book and patron management in libraries.

## Features

- **Catalog Management:** Seamlessly add, edit, and delete books.
  
- **Patron Information:** Manage borrower details and track borrowing history.

- **Borrowing Activity Tracking:** Monitor the status of borrowed and returned books.

- **Reporting Functionality:** Generate insightful reports on book availability and patron activity.

## Installation

Ensure the Frappe framework is installed. Refer to the [Frappe Installation Guide](https://frappeframework.com/docs/user/en/installation).

### Installation Steps:

1. **Install the App:**
   ```bash
   bench get-app --https://github.com/nelsonmpanju/library-management-app.git
   ```

2. **Create a New Site:**
   ```bash
   bench new-site [library-management-app]
   ```

3. **Install the App in the Site:**
   ```bash
   bench --site [library-management-app] install-app library_management_system
   ```

4. **Start the App:**
   ```bash
   bench start
   ```

Access the app at `http://localhost:8000`.

## Usage

- Log in to the Frappe admin panel.
- Navigate to the "Library Management" module to start using the app.

## Contributing

Contribute to enhancing this project. Review [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This project is under the [MIT License](LICENSE). Your contributions are valued as we refine the Library Management App.
