# Bank-Client-Management-System

# Client Management System

This Client Management System is a console-based application developed in C++. It allows you to manage client data such as account number, PIN code, name, phone number, and account balance. The application supports adding, listing, deleting, updating, and finding client records stored in a text file.

## Features

- **List Clients**: Display a list of all clients.
- **Add New Client**: Add a new client to the system.
- **Delete Client**: Delete an existing client by account number.
- **Update Client Info**: Update the details of an existing client.
- **Find Client**: Search for a client by account number.
- **Exit**: Exit the application.

## Getting Started

### Prerequisites

- A C++ compiler (e.g., GCC, MSVC)
- A development environment for C++ (e.g., Visual Studio, Code::Blocks)

### Installation

1. Clone the repository:

    ```bash
[    git clone https://github.com/your-username/client-management-system.git
    cd client-management-system](https://github.com/hagarMjd/Bank-Client-Management-System.git)
    ```

2. Build the application using your preferred C++ compiler. For example, using g++:

    ```bash
    g++ -o ClientManagementSystem main.cpp
    ```

3. Run the application:

    ```bash
    ./ClientManagementSystem
    ```

## Usage

Upon running the application, you will be presented with a main menu. You can navigate through the menu by entering the corresponding number for each option:

1. **Show Client List**: Displays all clients currently in the system.
2. **Add New Client**: Prompts you to enter details for a new client.
3. **Delete Client**: Prompts you to enter an account number and deletes the corresponding client.
4. **Update Client Info**: Prompts you to enter an account number and update the client's details.
5. **Find Client**: Prompts you to enter an account number and displays the client's details.
6. **Exit**: Exits the application.

## File Structure

- `main.cpp`: The main source code file containing the implementation of the client management system.
- `Clients.txt`: The file where client data is stored.

## Code Overview

- **Main Menu**: Displays options to the user and performs the selected action.
- **Client Structure**: Defines the client data structure.
- **File Operations**: Functions to read from and write to the client data file.
- **Client Operations**: Functions to add, delete, update, and find clients.

## Functions

- **ShowMainMenue**: Displays the main menu and handles user input.
- **ReadMainMenueOption**: Reads the user's choice from the main menu.
- **PerfromMainMenueOption**: Executes the selected option from the main menu.
- **ShowAllClientsScreen**: Displays all clients.
- **ShowAddNewClientsScreen**: Handles adding new clients.
- **ShowDeleteClientScreen**: Handles deleting a client.
- **ShowUpdateClientScreen**: Handles updating a client's information.
- **ShowFindClientScreen**: Handles finding a client.
- **ShowEndScreen**: Displays a message when the program ends.
