# Gestor de Tareas

Este proyecto es un gestor de tareas simple pero potente desarrollado en Python. Permite crear, editar, iniciar, marcar como completadas y guardar tareas en varios formatos de archivo. Utiliza bibliotecas populares como `os`, `datetime`, `pandas`, `python-docx` y `reportlab`.

## Requisitos

Para ejecutar este programa, asegúrate de tener instaladas las siguientes bibliotecas:

- pandas
- python-docx
- reportlab

Puedes instalar estas bibliotecas utilizando pip:

```
pip install pandas
pip install python-docx
pip install reportlab
```
## Uso

El programa proporciona una interfaz interactiva para gestionar tus tareas. Puedes agregar nuevas tareas, cambiar su estado, editar sus descripciones y guardar tus tareas en archivos de texto, Excel, Word o PDF.

### Funcionalidades

- **Agregar tareas**: Puedes agregar múltiples tareas a la vez ingresando sus descripciones separadas por comas.
- **Cambiar estado de tareas**: Marca tareas como "Iniciando" o "Completado".
- **Editar tareas**: Edita la descripción de una o varias tareas a la vez.
- **Guardar tareas**: Guarda tus tareas en varios formatos de archivo, incluyendo TXT, XLS, DOCX y PDF.

### Estructura del Programa

El programa consta de dos clases principales:

- `Tarea`: Representa una tarea individual con atributos como descripción, estado, fecha de inicio, fecha de fin, fecha de cambio y tiempo transcurrido.
- `ListaDeTareas`: Maneja una lista de tareas, permitiendo agregar, ordenar, mostrar y guardar tareas.

### Ejemplo de uso

1. Ejecuta el programa.
2. Selecciona la opción deseada del menú interactivo.
3. Sigue las instrucciones en pantalla para realizar la acción deseada.

## Contribuciones

Siéntete libre de contribuir al proyecto. Tus sugerencias y mejoras son bienvenidas.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT.
