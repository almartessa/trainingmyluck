# Proyecto Inteligent DB

## Descripción
El objetivo de este proyecto es poder establecer un chat de gerencias. Cada gerencia irá guardando su propio chat, el cual servirá como base de conocimiento para sus próximas charlas y así irá aprendiendo. Para ello, necesitamos que pueda establecer una comunicación hablada a través de micrófonos y parlantes, y que todo lo hablado quede registrado en una tabla. Utilizaremos SQL Server y Django como front-end. La base de datos inicialmente estará alojada en localhost.

## Estructura del Proyecto
- `index.js`: Archivo principal del proyecto.

## Instrucciones de Instalación
1. Clona el repositorio:
    ```bash
    git clone https://github.com/almartessa/inteligent.git
    ```
    Clonar un repositorio significa copiar un repositorio de Git a tu máquina local. Esto te permite tener una copia completa del proyecto, incluyendo todo el historial de cambios, ramas y archivos.
2. Navega al directorio del proyecto:
    ```bash
    cd inteligent
    ```
3. Instala las dependencias:
    ```bash
    npm install
    ```
4. Crea y activa un entorno virtual para Django:
    - En Windows (PowerShell):
        ```powershell
        python -m venv venv
        .\venv\Scripts\Activate
        ```
    - En Windows (Command Prompt):
        ```cmd
        python -m venv venv
        venv\Scripts\activate.bat
        ```
    - En Unix o macOS:
        ```bash
        python -m venv venv
        source venv/bin/activate
        ```
5. Instala Django:
    ```bash
    pip install django
    ```

## Uso
Para iniciar la aplicación, ejecuta:
```bash
node index.js
```
