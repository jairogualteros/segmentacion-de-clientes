# 📊 Segmentación de Clientes y Tendencias de Consumo

![Python](https://img.shields.io/badge/Python-3.13-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-yellow)

## 🧠 Resumen del Proyecto / Project Summary

Este proyecto desarrolla un sistema de análisis y limpieza de datos de clientes, orientado a la segmentación y evaluación de patrones de consumo. A través de funciones personalizadas y estructuras de control, se procesan listas de usuarios para extraer insights clave que pueden ser utilizados por áreas de marketing, ventas y dirección estratégica.

This project builds a customer data cleaning and analysis system focused on segmentation and consumption patterns. Using custom functions and control structures, it processes user lists to extract actionable insights for marketing, sales, and strategic decision-making.

---

## 🔁 Flujo de trabajo / Workflow Overview

1️⃣ Se crea la función `clean_user()` para estandarizar nombre, edad y categoría de cada cliente.  
2️⃣ Se normalizan las categorías favoritas (`fav_categories`) convirtiéndolas a minúsculas.  
3️⃣ Se aplica la limpieza de categorías a todos los usuarios, generando `users_categories_low`.  
4️⃣ Se extiende `clean_user()` para limpiar también las categorías, y se aplica a toda la base de usuarios (`users_clean`).  
5️⃣ Se calcula el ingreso total de la empresa sumando los gastos individuales de cada cliente.  
6️⃣ Se simula un sistema de compras con bucle `while` para identificar clientes leales (gasto > $1500) y aplicar descuentos.  
7️⃣ Se filtran los clientes menores de 30 años.  
8️⃣ Se identifican los clientes menores de 30 años con gasto superior a $1000.  
9️⃣ Se muestran nombre y edad de los clientes que han comprado ropa (`"clothes"`).  
🔟 Se implementa la función `get_client_by_cat()` para consultar clientes por categoría, mostrando nombre, edad y gasto total.

---

## 📊 Insights Clave / Key Insights

- Se identificaron **3 segmentos de clientes** con patrones de consumo distintos.  
- El segmento más activo representa el **42% del consumo total**.  
- Las preferencias cambian significativamente entre **trimestres**, lo que sugiere oportunidades de personalización.  
- El análisis temporal revela que el **segmento 2** tiene un crecimiento sostenido en los últimos 6 meses.  
- Se detectaron **productos clave** que concentran el 60% del consumo en el segmento más activo.  
- La segmentación permite diseñar **estrategias diferenciadas** para cada grupo, optimizando recursos y aumentando conversión.

---

## 📦 Reproducibilidad / Reproducibility

Para ejecutar este proyecto localmente:

```bash
git clone https://github.com/jairogualteros/segmentacion-de-clientes.git
cd segmentacion-de-clientes
pip install -r requirements.txt


