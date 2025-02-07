# Comandos Indispensables de Git

Git es una herramienta fundamental para el control de versiones. A continuación, se describen algunos de los comandos más importantes y frecuentemente utilizados en Git para gestionar proyectos de manera eficiente.

## 1. Inicialización y Clonación

- **`git init`**: Inicializa un nuevo repositorio Git en el directorio actual.
- **`git clone <url>`**: Clona un repositorio remoto a tu máquina local.

```bash
git init            # Inicializa un repositorio vacío
git clone <url>     # Clona un repositorio remoto
git status           # Verifica el estado de los archivos
git add <archivo>    # Añadir un archivo a la zona de preparación
git commit -m "mensaje"  # Hacer un commit con un mensaje
git push origin <rama>    # Empuja cambios a un repositorio remoto
git pull origin <rama>    # Obtiene cambios del repositorio remoto
git branch               # Muestra las ramas locales
git checkout <rama>      # Cambia a otra rama

