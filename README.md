![Logo](https://github.com/Iteracion2023/Calificaciones-en-Tiempo-de-Covid-I-parte-/blob/main/LinkedIn%20Cover%20Photo.png)


<h1>Calificaciones en tiempo de Covid: Educación Técnico Profesional (II parte)</h1>

**Introducción:** A pesar de la pandemia, una de las prácticas que los docentes no pudieron dejar de realizar fue evaluar a sus estudiantes. Los medios a través del cual, buscaron verificar los aprendizajes fueron diversos: videos; formularios de google, trabajos escritos enviados por e-mail, guías en papel enviadas a las casas y entregadas en el mismo formato en las porterías de los establecimientos. etc. Por lo mismo, una pregunta surge de todo ello fue: **¿Cuál fue la diferencia entre notas obtenidas el 2020 con la de años anteriores y posteriores?**

Para responder esta inquietud, decidimos recurrir a los datos oficiales que entrega el Mineduc. Por lo cual, utilizamos a sus  base de datos: **<i>"Notas y egresados de enseñanza media"</i>** de los años 2018, 2019, 2020, 2021. Consideramos el 2018 como punto de partida , porque fue el año que se creó la última región: Ñuble y como punto final el 2021, porque aun no están publicados los datos del 2022.

Las visualizaciones muestran los resultados de los promedios del nivel IV medio en cada uno de estos años en **<i>establecimientos educativos <i>**Técnicos Profesionales</i>**. Los resultados se presentan por regiones y solo tienen un **carácter exploratorio.**

**¿Qué hicimos?**:
- Descargamos las bases de datos junto a los documentos que reseñan cada una de las variables. 
- Cada DF fue revisado y se aplicó la limpieza de datos: Nan; eliminación de filas con datos faltantes, conversión de object a float. En este caso, trabajamos con librería de Python. 
- Posteriormente concatenamos los DF. En este caso notamos, que el df del 2021 tiene un declarado 330.005 estudiantes en relación a laos 978.137 del 2020 pero reporta mayor número de egresado: 280.013, 40.000 aprox. que los años anteriores. No hay información de esta diferencia en el Mineduc. 
- Organizamos la información en función de nuestra pregunta guía y visualizamos con Seaborn incluyendo la **media nacional** de los promedios. 
- Entregamos algunas conclusiones

**Archivos:**
  - El script con el trabajo realizado esta en formato html.
  - Presentanci{on en pdf con los gráficos y las conclusiones.
  - Debido al peso de las DF que no permitieron subirlas a este repositorio (tampoco en formato RAR), dejamaos el link para que puedan ser descargados directamente de la web del MINEDUC: https://datosabiertos.mineduc.cl/notas-y-egresados-de-ensenanza-media/
