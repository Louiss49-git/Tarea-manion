# Proyecto de Prueba con NumPy

Este es un proyecto sencillo en Python que utiliza la librería **NumPy** para crear e imprimir un array. Es ideal como ejemplo para practicar la configuración de entornos virtuales, gestión de dependencias, documentación y control de versiones con Git y GitHub.

## 📌 Versión de Python
Python **3.13.2**

## 📦 Dependencias
- [NumPy](https://numpy.org/)

## 🛠️ Instalación

Sigue estos pasos para clonar y ejecutar el proyecto en tu entorno local:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/Louiss49-git/Tarea-manion.git
   cd Tarea-manion
   ``

2. Crea un entorno virtual e instálalo:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

## 🚀 Ejecución

Ejecuta el script principal con:
```bash
python main.py
```

## 🧾 Contenido del Código

```python
import numpy as np

# Crear un array de NumPy
arr = np.array([1, 2, 3, 4, 5])

# Imprimir el array
print("Array de NumPy:", arr)
```