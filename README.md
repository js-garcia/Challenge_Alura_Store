# 🛒 Análisis de Datos – Alura Store

Este proyecto forma parte del Challenge de **Alura Latam**, cuyo objetivo es analizar el rendimiento de cuatro tiendas de la cadena *Alura Store* para ayudar al Sr. Juan a decidir cuál de ellas debería vender.

Para ello, se evaluaron ingresos, ventas por categoría, calificaciones de clientes, productos más/menos vendidos y costos de envío promedio. El análisis se realizó en Python utilizando Pandas y Matplotlib.

---

## 📌 Objetivos del proyecto

- Analizar los datos de ventas de las 4 tiendas.
- Identificar la tienda con menor rendimiento general.
- Generar visualizaciones que apoyen las conclusiones.
- Elaborar una recomendación final basada en datos.

---

## 🧰 Tecnologías utilizadas

- **Python 3**
- **Pandas** – manipulación de datos
- **Matplotlib** – creación de gráficos
- **Google Colab** – entorno de ejecución
- (Opcional) Folium – visualización geográfica

---

## 📂 Estructura del repositorio

Challenge_Alura_Store
│
├── 📄 Challenge_Alura_Store.ipynb # Notebook con el análisis completo
└── 📄 README.md # Documentación del proyecto


---

## 📊 Análisis realizado

### **1. Ingresos por tienda**
Se sumaron los valores de la columna `Precio` de cada tienda para determinar su facturación total.

### **2. Ventas por categoría**
Se agruparon los datos por `Categoría del Producto` y se contó cuántas ventas hubo por categoría en cada tienda.

### **3. Calificación promedio**
Se calculó el promedio de la columna `Calificación` para evaluar la satisfacción del cliente.

### **4. Productos más y menos vendidos**
Se utilizó `value_counts()` para identificar los productos con mayor y menor movimiento.

### **5. Costo de envío promedio**
Se calculó el promedio de la columna `Costo de envío` para analizar la eficiencia logística.

### **6. Visualizaciones**
Se generaron gráficos de:
- Barras (ingresos por tienda)
- Circular (ventas por categoría)
- Barras (calificación promedio)
- Opcional: dispersión geográfica de ventas

---

## ⭐ Conclusión final

Tras comparar todas las métricas, la tienda con peor rendimiento general resultó ser **Tienda 4**, al presentar:

- La menor facturación total.  
- Menor movimiento en categorías clave.  
- Mayor cantidad de productos con pocas ventas.  
- El costo de envío promedio más alto.  

📌 **Recomendación:** El Sr. Juan debería vender **Tienda 4**, ya que es la que menos aporta al desempeño global de la cadena.

---

## ▶️ Cómo ejecutar este proyecto

1. Clonar el repositorio:
```bash
git clone https://github.com/js-garcia/Challenge_Alura_Store.git

👩‍💻 Autora

Proyecto realizado por Soledad J. García
📌 Challenge de Análisis de Datos – Alura Latam
