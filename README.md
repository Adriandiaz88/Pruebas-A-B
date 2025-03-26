# Pruebas A/B para empresa internacional
Se realizarón estudios para una tienda en linea, los datos quedarón inconclusos, pero, se continuó con las pruebas A/B para ver comportamientos y diferencias de usuarios en ventas de la tienda.

### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Análisis de cohortes](https://img.shields.io/badge/Análisis_de_cohortes-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

## Preguntas clave
1. ¿Hay diferencias significativas en el comportamiento de los usuarios entre los grupos de control (A)
y tratamiento (B) en las pruebas?
2. ¿Qué puedes decir sobre los resultados de la prueba A/B?
3. ¿Cúantos usuarios abandonan la pagina antes de llegar a la compra?
4. ¿Es la prueba exitosa?

## Metodología
- **Preprocesamiento de datos:** Limpieza de datos (valores ausentes, duplicados, formatos de columnas, y tipos de datos adecuados).
- **Análisis exploratorio de datos** Estudiamos la conversión en las diferentes etapas del embudo ¿El número de eventos por usuario está distribuido equitativamente entre las
muestras?
- **Análisis de los Resultados de la Prueba A/B

## Conclusiones y recomendaciones

### Factores clave y estrategias integradas para reducir la taza de cancelación:
- Ambas pruebas mostraron impacto negativo en la conversión:
- Significancia estadística: Las diferencias no son aleatorias; los cambios en las pruebas empeoraron
el desempeño.
- Hubo errores en la implementación, problemas técnicos en el rediseño de interfaz o sistema de
recomendaciones.

### Advertencias Importantes:
- El Grupo B era 3 veces más pequeño que el Grupo A, lo que limita
los resultados.
- La caída del 80% en usuarios fue por la mala experiencia en el carrito.
- Hay que priorizar la optimización del carrito (ejemplo: simplificar checkout, clarificar costos).
- Asegurar que no hubo errores de implementación en los tratamientos.
- Re-ejecutar pruebas A/B en períodos sin campañas y con grupos balanceados.
- Los cambios aplicados en ambas pruebas no son viables, y la prioridad debe ser resolver el cuello
de botella en product_cart antes de testear nuevas hipótesis.

