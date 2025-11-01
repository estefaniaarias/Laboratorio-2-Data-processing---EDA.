# Laboratorio-2-Data-processing---EDA.

## Respuestas interpretativas

### 1. Análisis estadístico
¿Cuál es el promedio, mínimo y máximo de los atributos base (HP, Attack, Dfense, Speed) de todos los Pokemón?

### 2. Análisis gráfico
Cree un histograma para visualizar la distribución de los valores de Base Exp. 
Interprete si la distribución es simétrica o sesgada.

<img width="2970" height="1767" alt="pregunta2_histograma_base_exp" src="https://github.com/user-attachments/assets/b0fb4ad4-784c-44f9-8f59-5bf977e33a6a" />

La gráfica muestra que la Base Exp en Pokémon no sigue una distribución uniforme, por lo que no es simétrica. La gran mayoría de los Pokémon se concentran en valores de Base Exp entre 50 y 300, con pocos que otorgan valores muy altos.

### 3. Análisis gráfico
Realice un boxplot comparando los valores de Attack Base entre los tipos principales (Type1)
Identifique qué tipo tiene Pokemón con ataques más altos en promedio.

<img width="4170" height="2370" alt="pregunta3_boxplot_attack_type" src="https://github.com/user-attachments/assets/001700f9-691d-4574-bcc1-6c6c9bacf7d7" />

Los tipos asociados tradicionalmente a roles ofensivos físicos (Dragon, Fighting, Rock) tienden a tener ataques más altos, según la gráfica la mediana del tipo Dragon se encuentra en el valor más alto en comparación con todos los demás tipos (aproximadamente entre 110 y 115).


### 4. Análisis estadístico
¿ Cuál es el top 5 de especies (Species) más frecuentes en el dataset?

### 5. Análisis gráfico
Genere un gráfico de barras que muestre la cantidad de Pokemón por tipo principal (Type1)
¿Qué tipo es el más común?

<img width="4170" height="2369" alt="pregunta5_barras_pokemon_tipo" src="https://github.com/user-attachments/assets/3885e71f-cead-4ecd-9f07-cac1daf436e6" />
El tipo de Pokémon más común es el tipo Water, en la gráfica observamos que su barra es la más alta.

### 6. Análisis estadístico
Calcule la correlación entre los atributos HP Base, Attack Base, Defense Base y Speed Base.
¿Qué atributos están más correlacionados entre si?

### 7. Análisis gráfico
Cree un heatmap (mapa de calor) con la matriz de correlaciones obtenida en el punto anterior.
Interprete los resultados.

<img width="2602" height="2366" alt="pregunta7_heatmap_correlacion" src="https://github.com/user-attachments/assets/aa412e37-249c-483c-b698-59172855777a" />

Todas las estadísticas principales están correlacionadas entre sí en cierto grado, un aumento general en las estadísticas de un Pokémon suele significar un aumento en todas sus partes, aunque la fuerza de la relación varíe.

Speed Base y Defense Base son las dos estadísticas que tienen la relación lineal más débil, esto quiere decir que los personajes defensivos son lentos, mientras que los personajes rápidos son frágiles, en conclusión estas dos estadísticas no se mueven de la mano.

### 8. Análisis gráfico
Realice un diagrama de dispersión (scatter plot) entre Weight_kg y Attack Base.
¿Existe relación entre el peso de un Pokemón y su capacidad de ataque?

### 9. Análisis estádistico
Dtermine el promedio de altura y peso por tipo principal (Type1).
Interprete cual tipo tiende a tener Pokemón más grandes.

### 10. Análisis gráfico
Construya un gráfico de violín o boxplot múltiple comparando el atributo Speed Base entre los tipos Flying, Electric y Ground.
¿Qué tipo de Pokemón tiende a ser más rápido?
