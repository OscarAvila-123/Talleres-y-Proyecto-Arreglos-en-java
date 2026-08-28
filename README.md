# 🚀 Talleres – Proyecto Arreglos en Java

## 📝 Descripción Corta
Este repositorio contiene la solución práctica a los retos de programación y al proyecto integrador sobre **arreglos unidimensionales en Java** para la asignatura de Estructura de Datos[cite: 1]. Su objetivo principal es aplicar conceptos clave de gestión de memoria (Stack y Heap)[cite: 1], recorrido lineal, algoritmos de ordenamiento/búsqueda con complejidad optimizada ($\mathcal{O}(n)$ y $\mathcal{O}(1)$ espacial)[cite: 1], y la sincronización de datos mediante arreglos paralelos[cite: 1].

---

## 📌 Información General

* **Institución:** Corporación Universitaria Minuto de Dios – UNIMINUTO
* **Asignatura:** Estructura de Datos
* **NRC:** 90547
* **Docente:** Edilberto Ramirez Rivera
* **Ubicación:** Ciudad Bolívar – 2026

### 👥 Integrantes
* **Oscar Stiven Avila Nomesque** — ID: 1045928
* **David Santiago Borda Jimenez** — ID: 1095539
* **Andres Sebastian Reina Yazo** — ID: 1094995

---

## 🛠️ Contenido del Repositorio

### 🕹️ Reto 1: El Analista de Tendencias (Frecuencia y Moda)
* **Objetivo:** Analizar 20 registros de ventas de videojuegos (IDs del 0 al 20) para determinar el producto más vendido sin usar librerías avanzadas[cite: 1].
* **Funcionalidades Clave:**
  * **Conteo de Frecuencias:** Arreglo auxiliar de contadores con complejidad temporal de $\mathcal{O}(n)$[cite: 1].
  * **Cálculo de Moda:** Identificación del ID con mayor cantidad de ventas[cite: 1].
  * **Histograma Visual:** Gráfico de barras impreso en consola con asteriscos (`*`) para los artículos con ventas[cite: 1].

---

### 🔄 Reto 2: El Reordenamiento de la Memoria (Partición de Elementos)
* **Objetivo:** Reorganizar un arreglo heterogéneo (positivos, negativos y ceros) simulando la optimización de espacio en memoria[cite: 1].
* **Funcionalidades Clave:**
  * **Segregación In-Place:** Reordenamiento en la misma memoria ($\mathcal{O}(1)$ espacio auxiliar) agrupando negativos a la izquierda y positivos a la derecha[cite: 1].
  * **Eficiencia Temporal:** Máximo de dos recorridos sobre el arreglo ($\mathcal{O}(n)$)[cite: 1].
  * **Variante con Ceros:** Posicionamiento central de los ceros (`0`) como pivote intermedio[cite: 1].

---

### 📦 Proyecto: Sistema de Control de Inventario Logístico (SCIL)
* **Objetivo:** Sistema interactivo en consola para monitorear existencias físicas en una bodega regional[cite: 1].
* **Arquitectura y Requerimientos:**
  * **Arreglos Paralelos:** Sincronización entre `nombresProductos[]` (`String`) y `cantidadesStock[]` (`int`) mediante sus índices[cite: 1].
  * **Gestión de Stock:** Visualización en tabla y modificación directa de cantidades tras auditorías físicas[cite: 1].
  * **Alertas de Desabasto:** Filtro con ciclo `for` que identifica productos con 0 unidades y los marca como **"AGOTADOS"**[cite: 1].
  * **Interfaz:** Menú continuo en consola usando estructuras `switch` e interacción con `Scanner`[cite: 1].
