# Daisyworld Espacio-Temporal (V5) 🌼🌍

Este proyecto implementa una extensión espacial del clásico modelo climático "Daisyworld" (Watson y Lovelock, 1983). Evolucionamos el sistema de Ecuaciones Diferenciales Ordinarias (EDO) a un sistema acoplado de Ecuaciones en Derivadas Parciales (EDP) para estudiar la autorregulación térmica y la formación de patrones espaciales.

## 🎥 Animación de expansión de flores
*Aquí vemos cómo las margaritas blancas y negras compiten por el territorio buscando el equilibrio térmico:*

![Animación de Daisyworld](animacion_parches.gif)

## 🛠️ Tecnologías y Métodos Numéricos
* **Lenguaje:** Python (NumPy, Matplotlib)
* **Método Numérico:** Diferencias Finitas (Euler Explícito)
* **Condiciones de Borde:** Periódicas (Topología Toroidal)
* **Estabilización:** Implementación de inercia térmica para el balance de energía de Stefan-Boltzmann.

## 🚀 Cómo ejecutarlo
1. Clona este repositorio.
2. Abre el archivo `margaritas_v5.ipynb` en Jupyter Notebook o Google Colab.
3. Ejecuta todas las celdas para generar la simulación en tiempo real. Se pueden ajustar los parámetros para experimentar con diferentes condiciones.
