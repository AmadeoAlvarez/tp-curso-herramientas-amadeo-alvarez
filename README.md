# TP Curso de Herramientas Básicas de Análisis de Datos
## Trabajo final requerido para obtener la certificación de la cursada y aprobación delCurso Básico de Análisis de Datos de la UTN. Abrl de 2026.

El trabajo consiste en un breve análisis sobre algunos patrones de uso de la red social Instagram y la incidencia de estos en la vida de los usuarios.

Al finalizar el análisis podríamos poder responder las siguientes preguntas.

Existe en Instagram algún tipo de contenido que tenga una notoria prevalencia de consumo por sobre otros?

Cuáles son los países que tienen más usuarios registrados en Instagram y cuáles menos?

Como es la distribución de las edades de los usuarios de Instagram? Definir cuartiles.

Existe manera de medir la incidencia del uso de Instagram en el nivel de stress de los usuarios?

## Metododlogía

Se utilizó un Data Set descargado desde Kaggle que muestra patrones de uso de la red social Instagram. 

https://github.com/AmadeoAlvarez/tp-curso-herramientas-amadeo-alvarez/blob/main/data/ig_df.csv

Utilizando Python dentro de un Notebook de Google Colab, y con la ayuda de las librerías de Panda, Numpy, Matplotlb y Seaborn, he podido realizar algunas métricas y obtener algunas conclusiones.

https://github.com/AmadeoAlvarez/tp-curso-herramientas-amadeo-alvarez/blob/main/notebooks/TP_HBAD_Amadeo_Alvarez.ipynb

Además de los archivos de Google Colab TP_HBAD_Amadeo_Alvarez.ipynb y la base de datos utilizada ig_df.csv, se adjuntan algunos gráficos relevantes obtenidos del análisis.

https://github.com/AmadeoAlvarez/tp-curso-herramientas-amadeo-alvarez/blob/main/visualizaciones/Box%20Plot%20de%20Minutos%20de%20Uso%20Diarios.png

https://github.com/AmadeoAlvarez/tp-curso-herramientas-amadeo-alvarez/blob/main/visualizaciones/Correlación%20entre%20Uso%20y%20Stress.png

https://github.com/AmadeoAlvarez/tp-curso-herramientas-amadeo-alvarez/blob/main/visualizaciones/Distribución%20de%20Tipos%20de%20Contenido.png

https://github.com/AmadeoAlvarez/tp-curso-herramientas-amadeo-alvarez/blob/main/visualizaciones/Distribución%20de%20Usuarios%20por%20País.png

## Conclusiones:

Del Data Set al que pudimos acceder, hemos podido sacar conclusiones de los paises de mayor uso de la red social Instagram por cada continente (con la exepción de África). Estos son: Reino Unido, Canadá, Australia y Korea del Sur.

En cada uno de estos paises, los usuarios de Instagram tienen un uso promedio de casi 190 minutos diarios.

Globalmente, se registran usuarios registrados con edades desde los 13 a los 65 años, con una mediana de 39 años.

Globalmente, la distribución de los tópicos de consumo (preferred_content_theme) es equitativa. No se muestra un tópico que prevalezca notoriamente.

De mayor a menor, los paises con más cantidad de usuarios de Instagram son: Reino Unido, Canadá, Australia y, por últmo, Korea del Sur.

Se observa una correlación entre la cantidad de minutos de uso diario de la red social Instagram y el nivel de stress percibido en los usuarios. Dicha correlación es observable de igual manera en cada uno de los 4 rangos etarios (separados por cuartiles).

## Enlace 

https://github.com/AmadeoAlvarez/tp-curso-herramientas-amadeo-alvarez

Autor. Amadeo Álvarez.
