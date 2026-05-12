# Proyecto Integrador – Simulación de listas de espera hospitalarias

Este proyecto es una simulación estocástica basada en teoría de colas para poder analizar el comportamiento de listas de espera en los hospitales mediante un modelo M/M/c utilizando el código en Python.

## Objetivo

El objetivo principal del proyecto es ver cómo influye el número de médicos disponibles en el tiempo de espera de los pacientes.
Para ello, hemos comparado distintos escenarios variando la cantidad de médicos disponibles y analizando datos como:
- el tiempo medio de espera,
- el tiempo total en el sistema,
- y el grado de congestión del sistema.

## Herramientas utilizadas

Las herramientas empleadas durante el desarrollo del código han sido:

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- GitHub

## Contenido del repositorio

Este repositorio incluye:

- `Proyecto_integrador.ipynb` → notebook principal con el desarrollo completo de la simulación.
- `README.md` → documento descriptivo del proyecto.

## Ejecución del proyecto

Para ejecutar el proyecto es necesario contar con un entorno compatible con Python, como Google Colab, que es el que hemos utilizado nosotras o Jupyter Notebook.

### Pasos para ejecutar el código

1. Descargar o clonar el repositorio.
2. Abrir el archivo `Proyecto_integrador.ipynb`.
3. Ejecutar las celdas del notebook en orden.

El programa genera automáticamente:
- la simulación de llegada de pacientes,
- la asignación de pacientes a médicos,
- el cálculo de tiempos de espera,
- tablas de resultados,
- y gráficas comparativas entre distintos escenarios.

## Librerías necesarias

El proyecto utiliza las siguientes librerías de Python:

- NumPy
- Pandas
- Matplotlib

Estas librerías pueden instalarse mediante:

```python
pip install numpy pandas matplotlib
