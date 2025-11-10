# Proyecto Análisis de Datos – Unidad 1: Adquisición y manejo de datos
**Empresa**: GlobalShop S.A.  
**Entorno de ejecución**: `101.py` o `101.ipynb`

---

## 📌 Descripción del proyecto
GlobalShop S.A. es una empresa de comercio electrónico que ha almacenado información en distintos formatos a lo largo de los años. El objetivo de este proyecto es:

✅ Cargar los datos  
✅ Unificarlos en un único conjunto  
✅ Realizar análisis exploratorio de ventas, clientes y productos  

> Enunciado completo disponible aquí:  
> https://mp5101-ad.vercel.app/docs/unidades/01/tareas/enunciado

---

## 📁 Archivos de datos proporcionados
| Archivo | Tipo | Contenido |
|--------|------|-----------|
| `pedidos.csv` | CSV (UTF-16) | Transacciones de ventas |
| `clientes.json` | JSON | Información de clientes |
| `productos.db` | SQLite DB | Detalles de productos |

---

## 🎯 Objetivos / Apartados del proyecto
El proyecto incluye 19 apartados que deben resolverse en orden:

1️⃣ Carga del *dataset*  
2️⃣ Unificación de datos  
3️⃣ Información básica del dataset  
4️⃣ Tipos de datos y nulos  
5️⃣ Estadísticas descriptivas  
6️⃣ Filtrado simple  
7️⃣ Filtrado con múltiples condiciones  
8️⃣ Filtrado temporal  
9️⃣ Análisis del estado del pedido  
🔟 Análisis del método de pago  
1️⃣1️⃣ País de envío  
1️⃣2️⃣ Demografía de clientes  
1️⃣3️⃣ Clientes por país  
1️⃣4️⃣ Clientes por ciudad  
1️⃣5️⃣ Categoría de productos  
1️⃣6️⃣ Precios y top productos  
1️⃣7️⃣ Productos más vendidos  
1️⃣8️⃣ Análisis temporal de ventas  
1️⃣9️⃣ Duplicados  
2️⃣0️⃣ Valores faltantes  
2️⃣1️⃣ Valoración final

> Cada apartado debe ir acompañado de un **comentario indicando el número del apartado** y su **solución justo debajo**.

---

## 📌 Requisitos del entregable
- Un único archivo: `101.py` o `101.ipynb`
- Cada salida debe mostrar:
  - Número de apartado
  - Respuesta del análisis
- Si un apartado no se puede resolver:
  - Dejar el comentario del apartado y una línea en blanco
- Si se detectan errores en los datos:
  - Indicar qué error es y cómo se soluciona antes de continuar
- **Copias o código de IA no se corregirá** → puntuación **0**

---

## 🛠️ Requisitos técnicos
- Python 3.x
- Librerías sugeridas:
  - `pandas`
  - `numpy`
  - `sqlite3` (para `.db`)
- Comandos recomendados:
```bash
pip install pandas numpy
```

## 🗂️ Estructura recomendada del repositorio

```text
/
├── 101.ipynb        # Notebook principal (o 101.py)
├── pedidos.csv
├── clientes.json
├── productos.db
└── README.md
```

## ▶️ Cómo ejecutar

- Clonar el repositorio

- Instalar dependencias

- Ejecutar el notebook/script

- Verificar rutas de acceso a los datos


📌 Nota final

Este proyecto corresponde a la Unidad 1 - Adquisición y Manejo de Datos, y sienta las bases para futuros análisis avanzados sobre información real de una empresa de comercio electrónico.

