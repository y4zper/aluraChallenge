

Proyecto de análisis de datos de ventas para evaluar el desempeño de 4 tiendas y determinar cuál representa la mejor oportunidad de negocio. Se analizaron múltiples variables incluyendo ingresos, categorías de productos, calificaciones de clientes, productos más vendidos y costos de envío.

**Contexto:** El Sr. Juan necesita decidir a qué tienda vender basándose en datos históricos de ventas. El análisis abarca múltiples dimensiones: rentabilidad, satisfacción del cliente, distribución de productos y eficiencia operativa.


---

## Objetivos del Proyecto

- Calcular y comparar los ingresos totales de cada tienda
- Analizar la distribución de ventas por categoría de productos
- Evaluar la satisfacción del cliente mediante calificaciones promedio
- Identificar los productos más y menos vendidos por tienda
- Comparar los costos de envío promedio
- Realizar análisis geográfico de las ventas (opcional)
- Generar visualizaciones claras para la toma de decisiones
- Emitir una recomendación fundamentada sobre qué tienda vender

### Fuente de Datos
Los datos provienen del [Challenge Data Science LATAM de Alura](https://github.com/alura-es-cursos/challenge1-data-science-latam)

### Estructura
│
├── data/                           # Datos de las 4 tiendas
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
│
├── notebooks/                      # Notebooks de análisis
│   ├── 01_carga_y_exploracion.ipynb
│   ├── 02_analisis_ingresos.ipynb
│   ├── 03_analisis_categorias.ipynb
│   ├── 04_calificaciones_clientes.ipynb
│   ├── 05_productos_mas_menos_vendidos.ipynb
│   ├── 06_costos_envio.ipynb
│   ├── 07_visualizaciones_finales.ipynb
│ 
│
├── images/                         # Gráficos generados
│   ├── 01_ingresos_comparacion.png
│   ├── 02_ventas_por_categoria.png
│   ├── 03_calificaciones_linea.png
│   ├── 04_productos_mas_vendidos.png
│   ├── 05_productos_menos_vendidos.png
│   ├── 06_costos_envio_circular.png
│
├── informe/                        # Informe final
│
├── README.md                       # Este archivo

### 3. Ejemplos de Gráficos e Insights

Ingresos Totales: La Tienda 4 genera $112 millones menos que la líder, representando un 10% menos de rentabilidad, lo que la posiciona claramente como la unidad de negocio con menor valor económico.
Distribución por Categoría: Las Tiendas 3 y 4 muestran alta dependencia en Muebles, mientras que las Tiendas 1 y 2 tienen una cartera más diversificada, reduciendo su vulnerabilidad ante cambios en el mercado.
Satisfacción del Cliente: Todas las tiendas mantienen calificaciones similares y aceptables (entre 3.98 y 4.05), indicando que la satisfacción no es un factor diferenciador clave en las decisiones de venta.
Productos Más Vendidos: No existe un producto estrella que diferencie significativamente a ninguna tienda, ya que los volúmenes de venta de los productos top son comparables en todas las ubicaciones.
Productos Menos Vendidos: La distribución similar de productos de baja rotación sugiere una oportunidad generalizada para optimizar inventarios, no un problema específico de una tienda.
Costos de Envío: La ventaja de $2,559 en costos de envío de la Tienda 4 es marginal y no compensa su significativa brecha de ingresos, especialmente considerando que estos costos son asumidos por los clientes.
Distribución Geográfica: Todas las tiendas tienen cobertura similar en las principales ciudades sin dominio regional específico, y la satisfacción del cliente es consistente independientemente de la ubicación.
Conclusión Estratégica: La Tienda 4 debe ser vendida debido a su rendimiento consistentemente inferior en ingresos, su falta de diferenciación competitiva y su impacto desproporcionadamente bajo en el negocio general.

### 4. Ejecución de Proyecto 

Para ejecutar el notebook de análisis de ventas, primero instala Python 3.8 o superior junto con Jupyter Notebook y las bibliotecas necesarias (pandas, matplotlib, seaborn y numpy) usando pip o Anaconda. Luego, inicia Jupyter desde la terminal, abre el archivo .ipynb y ejecuta las celdas secuencialmente con Shift+Enter para generar los gráficos e insights. Asegúrate de ejecutar todas las celdas en orden, desde la configuración inicial hasta las conclusiones, verificando que cada gráfico se muestre correctamente antes de pasar a la siguiente sección del análisis.





