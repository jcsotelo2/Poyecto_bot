**# TALLER BOT DE VENTAS #**

**## PREGUNTA 1: ##**

*###  ¿(para su README): que hace glob.glob()? ###*

glob.glob() — Busca archivos en una carpeta usando patrones (ej. *.csv) y devuelve la lista de rutas encontradas. Útil para leer varios archivos sin escribirlos uno por uno.

**## PREGUNTA 2: ##**

*### ¿que hace pd.concat()? por que se ejecuta dos veces? ###*

pd.concat() — Une varios DataFrames en uno solo (por defecto, uno debajo del otro). Se ejecuta dos veces porque probablemente primero junta los archivos leídos con glob.glob(), y luego combina ese resultado con otro dato distinto. (Compárteme el código si quieres la razón exacta.)

**## PREGUNTA 3: ##**

*### que hace enumerate()? por que se necesita aqui (i)? ###*

enumerate() — Recorre una lista y te da el índice (i) junto con cada valor. Se usa i cuando necesitas contar o numerar mientras procesas (ej. "archivo 1, archivo 2...").


**## PREGUNTA 4: ##**

*### que hace drop_duplicates()? que hace fillna()? ###*

drop_duplicates(): borra filas repetidas.
fillna(): rellena los valores vacíos (NaN) con algo que tú definas.

**## PREGUNTA 5: ##**

*### que hace groupby()? ¿cual es la diferencia entre el # grafico de barras y el de torta, cuando usar cada uno?###*

groupby(): agrupa filas por una columna (ej. categoría) para sacar totales, promedios, etc.
Barras: para comparar valores entre categorías.
Torta: para mostrar cómo se reparte un total en porcentajes. 













