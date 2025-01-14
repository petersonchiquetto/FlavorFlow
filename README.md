# FlavorFlow

Welcome to **FlavorFlow**, a Python-based backend application designed to manage restaurant data interactively and efficiently. This README provides an overview of the project, its objectives, and detailed instructions to get started.

## Project Objective 🎯

FlavorFlow aims to simplify restaurant management by allowing users to:

- **Add new restaurants** 🍽️ with their respective categories.
- **View a list of all restaurants** 📋, including their statuses (active or inactive).
- **Toggle activation status** 🔄 of restaurants.

This application serves as a foundational project for learning and demonstrating key backend development concepts in Python.

## Features ✨

1. **Interactive Menu** 🖥️: Users can navigate through various functionalities with ease.
2. **Restaurant Data Management**:
   - Add new restaurants with customizable categories ➕.
   - View restaurant details (name, category, and status) 👀.
   - Toggle activation status for any restaurant 🔁.
3. **User-Friendly Interface**: A console-based UI with prompts and feedback messages.

## Application Architecture 🏗️

FlavorFlow follows a modular and structured approach:

- **Main Application Flow**:
  - Entry point defined in the `main()` function.
  - Interactive menu for user actions.
- **Core Functions**:
  - `cadastrar_novo_restaurante()`: Manages restaurant registration ✏️.
  - `listar_restaurantes()`: Displays all registered restaurants 📃.
  - `alternar_estado_restaurante()`: Toggles activation status 🔄.
- **Utility Functions**:
  - `exibir_nome_do_programa()`: Displays the app title in a stylized format ✨.
  - `exibir_opcoes()`: Presents menu options 🗂️.
  - `voltar_ao_menu_principal()`: Returns the user to the main menu ↩️.
  - `opcao_invalida()`: Handles invalid menu selections ❌.

## Use of Docstrings 📜

FlavorFlow's code utilizes docstrings to document its functions. This technique enables:

- Developers to quickly understand the purpose of each function.
- Automatic documentation tools to generate descriptions from the code.

### Docstring Example

Here is an example of how docstrings are implemented in the code:

```python
def cadastrar_novo_restaurante():
    '''
    This function handles the registration of a new restaurant.

    Inputs:
    - Restaurant name
    - Category

    Outputs:
    - Adds a new restaurant to the list of restaurants
    '''
    exibir_subtitulo('Registering a new restaurant')
    nome_do_restaurante = input('Enter the name of the restaurant: ')
    categoria = input(f'Enter the category of the restaurant {nome_do_restaurante}: ')
    dados_do_restaurante = {'nome': nome_do_restaurante, 'categoria': categoria, 'ativo': False}
    restaurantes.append(dados_do_restaurante)
    print(f'The restaurant {nome_do_restaurante} has been successfully registered!')
    voltar_ao_menu_principal()
```

### Benefits of Docstrings ✅

- **Clarity**: Clearly explain input parameters, outputs, and the purpose of the functions.
- **Maintainability**: Facilitate code maintenance, enabling other developers to understand functionality quickly.
- **Automation**: Integrate with tools like Sphinx or IDEs to auto-generate documentation.

## Directory Structure 📂
```
FlavorFlow/
├── app.py        # Main application file
└── README.md     # Project documentation
```

## Getting Started 🚀

### Prerequisites 📋

Ensure Python is installed on your system. This project is compatible with Python 3.6 and above.

### Installation 🛠️

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FlavorFlow.git
   ```
2. Navigate to the project directory:
   ```bash
   cd FlavorFlow
   ```

### Usage 📖

1. Run the application:
   ```bash
   python app.py
   ```
2. Follow the on-screen instructions to interact with the application.

### Example Outputs 🖥️

**Main Menu:**
```
1. Register restaurant
2. List restaurants
3. Toggle restaurant status
4. Exit
```

**Listing Restaurants:**
```
Restaurant Name         | Category           | Status
- Praça                | Japanese           | inactive
- Pizza Suprema        | Pizza              | active
- Cantina              | Italian            | inactive
```

**Toggling Restaurant Status:**
```
Enter the name of the restaurant to toggle status: Praça
The restaurant Praça has been successfully activated ✅
```

## Contributions 🤝

Contributions are welcome! 🌟 Feel free to open issues or submit pull requests to improve the application.

## License 📜

This project is licensed under the MIT License. See the LICENSE file for details.

---

Happy coding with **FlavorFlow**! 💻🍴

