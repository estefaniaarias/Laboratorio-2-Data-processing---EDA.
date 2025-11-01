# Laboratorio-2-Data-processing---EDA.

## Respuestas interpretativas

### 1. Análisis estadístico
¿Cuál es el promedio, mínimo y máximo de los atributos base (HP, Attack, Dfense, Speed) de todos los Pokemón?




### 2. Análisis gráfico
Cree un histograma para visualizar la distribución de los valores de Base Exp. 
Interprete si la distribución es simétrica o sesgada.

<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/27f6af9c-5d15-4e96-9527-ec525fa24f06" />


La gráfica muestra que la Base Exp en Pokémon no sigue una distribución uniforme, por lo que no es simétrica. La gran mayoría de los Pokémon se concentran en valores de Base Exp entre 50 y 300, con pocos que otorgan valores muy altos.

### 3. Análisis gráfico
Realice un boxplot comparando los valores de Attack Base entre los tipos principales (Type1)
Identifique qué tipo tiene Pokemón con ataques más altos en promedio.

<img width="1389" height="590" alt="image" src="https://github.com/user-attachments/assets/13ad42f3-cccd-4b4e-a70a-421c126971c6" />



Los tipos asociados tradicionalmente a roles ofensivos físicos (Dragon, Fighting, Rock) tienden a tener ataques más altos, según la gráfica la mediana del tipo Dragon se encuentra en el valor más alto en comparación con todos los demás tipos (aproximadamente entre 110 y 115).


### 4. Análisis estadístico
¿ Cuál es el top 5 de especies (Species) más frecuentes en el dataset?



### 5. Análisis gráfico
Genere un gráfico de barras que muestre la cantidad de Pokemón por tipo principal (Type1)
¿Qué tipo es el más común?

<img width="698" height="580" alt="image" src="https://github.com/user-attachments/assets/fbfcf7cf-bc6f-41a4-b988-8c1dbcc4422a" />

El tipo de Pokémon más común es el tipo Water, en la gráfica observamos que su barra es la más alta.

### 6. Análisis estadístico
Calcule la correlación entre los atributos HP Base, Attack Base, Defense Base y Speed Base.
¿Qué atributos están más correlacionados entre si?




### 7. Análisis gráfico
Cree un heatmap (mapa de calor) con la matriz de correlaciones obtenida en el punto anterior.
Interprete los resultados.

<img width="695" height="605" alt="image" src="https://github.com/user-attachments/assets/3d35cd7d-0da1-4e38-bca2-ace907ca9cf6" />


Todas las estadísticas principales están correlacionadas entre sí en cierto grado, un aumento general en las estadísticas de un Pokémon suele significar un aumento en todas sus partes, aunque la fuerza de la relación varíe.

Speed Base y Defense Base son las dos estadísticas que tienen la relación lineal más débil, esto quiere decir que los personajes defensivos son lentos, mientras que los personajes rápidos son frágiles, en conclusión estas dos estadísticas no se mueven de la mano.

### 8. Análisis gráfico
Realice un diagrama de dispersión (scatter plot) entre Weight_kg y Attack Base.
¿Existe relación entre el peso de un Pokemón y su capacidad de ataque?

<img width="773" height="626" alt="image" src="https://github.com/user-attachments/assets/a039e520-a2dc-44f5-99fb-9bd924aa2935" />


En el diagrama se puede observar que la correlación entre ambas variables es débil, a pesar de que nos enseña que los Pokemón más pesados presentan ataques más altos, los puntos se encuentran dispersos, indicando que el peso influye muy poco en la capacidad ofensiva.

### 9. Análisis estádistico
Dtermine el promedio de altura y peso por tipo principal (Type1).
Interprete cual tipo tiende a tener Pokemón más grandes.

Los Pokémon de tipo Steel, Ground y Dragon tienen los promedios más altos, por lo que podemos concluir que los más grandes y pesados, mientras que los tipos Bug, Grass y Fairy poseen los valores más bajos, apuntando a que son los más pequeños y livianos.


### 10. Análisis gráfico
Construya un gráfico de violín o boxplot múltiple comparando el atributo Speed Base entre los tipos Flying, Electric y Ground.
¿Qué tipo de Pokemón tiende a ser más rápido?

<img width="773" height="625" alt="image" src="https://github.com/user-attachments/assets/ea0b3ff2-02bb-4049-88fe-1ed73efe487b" />

Los Pokémon de tipo Electric presentan velocidades base más altas, seguidos por los de tipo Flying y finalmente los de tipo Ground que son más lentos.
