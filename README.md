# 📊 Mi primer repositorio

Este repositorio contiene dos archivos de datos simulados en formato **CSV**:  
- `clientes.csv` → información de clientes registrados.  
- `ventas.csv` → información de ventas realizadas.  

Ambos archivos están diseñados para prácticas de **análisis de datos**, **gestión comercial** y **ejercicios académicos**.

---

## 👥 Archivo `clientes.csv`

Este archivo contiene la **información básica de los clientes**.  
Columnas incluidas:
- **ID** → identificador único del cliente.  
- **Nombre** → nombre del cliente.  
- **Apellido** → apellido del cliente.  
- **Email** → correo electrónico.  
- **Teléfono** → número de contacto.  
- **Ciudad** → ciudad de residencia.  
- **País** → país de residencia.  

### 📋 Ejemplo en tabla

| ID | Nombre    | Apellido   | Email                      | Teléfono   | Ciudad     | País     |
|----|-----------|------------|----------------------------|------------|------------|---------|
| 1  | Ana       | Pérez      | ana.perez@example.com      | 0991234567 | Cuenca     | Ecuador |
| 2  | Carlos    | Gómez      | carlos.gomez@example.com   | 0987654321 | Quito      | Ecuador |
| 3  | María     | López      | maria.lopez@example.com    | 0971122334 | Guayaquil  | Ecuador |
| 4  | José      | Ramírez    | jose.ramirez@example.com   | 0965566778 | Cuenca     | Ecuador |
| 5  | Lucía     | Fernández  | lucia.fernandez@example.com| 0959988776 | Manta      | Ecuador |

---

## 💰 Archivo `ventas.csv`

Este archivo contiene la **información de las ventas realizadas**.  
Columnas incluidas:
- **Fecha** → día en que se realizó la venta.  
- **Producto** → artículo vendido.  
- **Cantidad** → número de unidades vendidas.  
- **Precio Unitario** → valor por unidad.  
- **Total** → monto total de la venta.  

### 📋 Ejemplo en tabla

| Fecha       | Producto   | Cantidad | Precio Unitario | Total |
|-------------|------------|----------|-----------------|-------|
| 2025-11-01  | Laptop     | 2        | 800             | 1600  |
| 2025-11-02  | Mouse      | 5        | 20              | 100   |
| 2025-11-03  | Teclado    | 3        | 35              | 105   |
| 2025-11-04  | Monitor    | 1        | 200             | 200   |
| 2025-11-05  | Impresora  | 2        | 150             | 300   |

---

## 🔗 Relación entre clientes y ventas

En un sistema real, ambos archivos se relacionarían mediante un **ID de cliente** en el archivo de ventas.  
Esto permitiría saber **qué cliente compró qué producto** y realizar análisis como:  
- Ventas por cliente.  
- Ventas por ciudad o país.  
- Productos más vendidos.  

Ejemplo de relación:

| ID Cliente | Fecha       | Producto | Cantidad | Total |
|------------|-------------|----------|----------|-------|
| 1          | 2025-11-01  | Laptop   | 2        | 1600  |
| 2          | 2025-11-02  | Mouse    | 5        | 100   |

---

## ✅ Conclusión

El proyecto de **Datos de Ventas y Clientes** constituye una base sólida para la práctica de análisis comercial y académico.  
La integración de los archivos `clientes.csv` y `ventas.csv` permite simular un entorno real de gestión, en el cual es posible:  

- Identificar patrones de compra y comportamiento de los clientes.  
- Evaluar el rendimiento de productos y detectar los más vendidos.  
- Analizar la distribución geográfica de las ventas para apoyar decisiones estratégicas.  
- Facilitar la creación de reportes y dashboards que respalden la toma de decisiones.  

En conjunto, estos datos ofrecen un escenario ideal para aplicar técnicas de **Business Intelligence**, **Data Analytics** y **gestión de sistemas de información**, fortaleciendo tanto el aprendizaje académico como la preparación para entornos profesionales.  
