# FlavorFlow

Welcome to **FlavorFlow**, a Python-based backend application for managing restaurant data interactively and efficiently. This README provides an overview of the project, its objectives, and detailed instructions to help you get started.

## Project Objective

FlavorFlow is designed to streamline restaurant management by allowing users to:

- **Add new restaurants** 🍽️ with their respective categories.
- **View a list of all restaurants** 📋, including their statuses (active or inactive).
- **Toggle the activation status** 🔄 of restaurants.

This application serves as a foundational project for learning and demonstrating key backend development concepts in Python.

## Features

1. **Interactive Menu** 🖥️: Users are presented with a menu to navigate various functionalities.
2. **Restaurant Data Management**:
   - Add new restaurants with customizable categories ➕.
   - View restaurant details (name, category, and status) 👀.
   - Toggle the activation status of any restaurant 🔁.
3. **User-Friendly Interface**: Simple console-based UI with prompts and feedback messages.

## Application Architecture

FlavorFlow follows a modular and structured approach:

- **Main Application Flow**:
  - Entry point defined in the `main()` function.
  - Interactive menu for user actions.
- **Core Functions**:
  - `cadastrar_novo_restaurante()`: Handles restaurant registration ✏️.
  - `listar_restaurantes()`: Displays all registered restaurants 📃.
  - `alternar_estado_restaurante()`: Toggles the activation status 🔄.
- **Utility Functions**:
  - `exibir_nome_do_programa()`: Displays the app title in a stylized format ✨.
  - `exibir_opcoes()`: Presents the menu options 🗂️.
  - `voltar_ao_menu_principal()`: Returns the user to the main menu ↩️.
  - `opcao_invalida()`: Handles invalid menu selections ❌.

### Directory Structure
```
FlavorFlow/
├── app.py        # Main application file
└── README.md     # Project documentation
```

## Getting Started

### Prerequisites

Ensure you have Python installed on your system. This project is compatible with Python 3.6 and above.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FlavorFlow.git
   ```
2. Navigate to the project directory:
   ```bash
   cd FlavorFlow
   ```

### Usage

1. Run the application:
   ```bash
   python app.py
   ```
2. Follow the on-screen instructions to interact with the application 🛠️.

### Sample Outputs

**Main Menu:**
```
1. Cadastrar restaurante
2. Listar restaurantes
3. Alternar estado do restaurante
4. Sair
```

**Listing Restaurants:**
```
Nome do restaurante     | Categoria           | Status
- Praça                 | Japonesa            | desativado
- Pizza Suprema         | Pizza               | ativado
- Cantina               | Italiano            | desativado
```

**Toggling Restaurant Status:**
```
Digite o nome do restaurante que deseja alterar o estado: Praça
O restaurante Praça foi ativado com sucesso ✅
```

## Contributing

Contributions are welcome! 🌟 Feel free to open issues or submit pull requests to improve the application.

## License

This project is licensed under the MIT License. See the LICENSE file for details.


---

Happy coding with **FlavorFlow**! 💻🍴

