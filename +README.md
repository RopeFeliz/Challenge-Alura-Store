Proyecto: Alura Store Latam — Análisis de Ventas y Rendimiento
📌 Descripción
Este proyecto tiene como objetivo analizar el rendimiento de cuatro tiendas de Alura Store Latam, con el fin de ayudar al señor Juan a tomar una decisión estratégica: determinar cuál tienda vender para invertir en un nuevo negocio.

Se evalúan cinco aspectos clave para cada tienda:

Facturación total — ¿Cuál tienda vende más?

Categorías más populares — ¿Qué productos se venden más en cada tienda?

Promedio de evaluación de clientes — ¿Qué satisfacción tienen los clientes?

Productos más y menos vendidos — ¿Cuáles son los productos estrella y los de menor desempeño?

Costo promedio de envío — ¿Cuánto cuesta en promedio enviar los productos?

🗂 Estructura del Proyecto
text
AluraStoreLatam/
│
├── AluraStoreLatam.ipynb           # Notebook principal con análisis completo
├── README.md                       # Este archivo
└── datos/
    ├── tienda_1.csv                # Datos de ventas tienda 1
    ├── tienda_2.csv                # Datos de ventas tienda 2
    ├── tienda_3.csv                # Datos de ventas tienda 3
    └── tienda_4.csv                # Datos de ventas tienda 4
Los datos originales se descargan desde GitHub en el notebook.

📊 Aspectos Analizados
1. Facturación total por tienda
Se calculó la suma de ventas (Precio) de cada tienda.

Resultado destacado: Tienda1 lidera en ventas totales con $1,150,880,400, seguida por Tienda2, Tienda3 y Tienda4.

Gráfico: Barras comparativas de ventas totales.

2. Ventas por categoría de producto
Se agruparon ventas por categoría en cada tienda.

Categoría más vendida en todas las tiendas: Electrónicos.

Electrónicos representa la mayor facturación, seguida de Electrodomésticos y Muebles.

Gráfico: Barras apiladas o comparativas por categoría.

3. Promedio de evaluación de clientes
Se calculó la calificación promedio por tienda.

Insight: Las tiendas con mejor evaluación suelen tener mayor fidelización, aunque no siempre correlacionan con mayor facturación.

4. Productos más y menos vendidos
Se identificaron los productos con mayor y menor cantidad de ventas por tienda.

Ejemplo: En Tienda1, "Smartwatch" y "Laptop" son los más vendidos; "Guitarra acústica" entre los menos.

5. Costo promedio de envío
Se calculó el promedio de Costo de envío por tienda.

Insight: Tiendas con mayor costo de envío pueden estar afectando la satisfacción del cliente, aunque no necesariamente las ventas.

📈 Ejemplo de Gráficos Incluidos
Ventas totales por tienda — Gráfico de barras verticales.

Ventas por categoría — Gráfico de barras agrupadas o apiladas.

Mapa de calor de ventas por categoría y tienda — Opcional para visualización avanzada.

🧪 Cómo Ejecutar el Proyecto
Requisitos
Python 3.8+

Librerías: pandas, matplotlib, numpy

Instalación de dependencias
bash
pip install pandas matplotlib numpy
Ejecutar el notebook
Clona o descarga el repositorio.

Abre AluraStoreLatam.ipynb en Jupyter Notebook o Google Colab.

Ejecuta todas las celdas en orden.


📄 Licencia
Este proyecto es de uso educativo. Los datos son proporcionados por Alura para fines de aprendizaje.

