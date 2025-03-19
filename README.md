# Gestor de Habitaciones de Hotel

Este proyecto proporciona un sistema básico de gestión de habitaciones para un hotel, permitiendo reservar, liberar y listar las habitaciones disponibles.

## Características

-   Gestión de habitaciones con información sobre número, tipo, capacidad, precio por noche y disponibilidad.
-   Reserva y liberación de habitaciones.
-   Listado de habitaciones disponibles.
-   Interfaz de menú interactiva para gestionar las habitaciones.

## Requisitos

-   Python 3.6+

## Instalación

1.  Clona el repositorio:

    ```bash
    git clone <URL_del_repositorio>
    cd gestor-habitaciones-hotel
    ```

2.  Crea un entorno virtual (recomendado):

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # En Linux/macOS
    venv\Scripts\activate  # En Windows
    ```

3.  Instala las dependencias (si las hubiera, en este caso no hay dependencias externas):

    ```bash
    pip install -r requirements.txt
    ```

## Uso

1.  Ejecuta el script `main.py`:

    ```bash
    python main.py
    ```

2.  Sigue las instrucciones del menú para gestionar las habitaciones.

### Menú

-   **1. Reservar:** Permite reservar una habitación.
-   **2. Liberar:** Permite liberar una habitación.
-   **3. Listar habitaciones disponibles:** Muestra las habitaciones actualmente disponibles.
-   **4. Salir:** Cierra el programa.

### Ejemplo de uso

1.  Ejecuta `python main.py`.
2.  Selecciona la opción "3" para ver las habitaciones disponibles.
3.  Selecciona la opción "1" para reservar una habitación y sigue las instrucciones.
4.  Selecciona la opción "2" para liberar una habitación reservada.
5.  Selecciona la opción "4" para salir del programa.

## Estructura del Proyecto

-   `main.py`: Contiene la lógica principal del programa y la interfaz del menú.
-   `habitaciones.py`: Contiene la información inicial de las habitaciones en forma de datos.

