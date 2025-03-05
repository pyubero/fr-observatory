# metodología y resultados 

En base a nuestro **objetivo** de ofrecer una serie de herramientas que recojan de una manera estructurada discursos, iniciativas y políticas de la extrema derecha cuando llegan al gobierno de alguna región específica, hemos desarrollado una **metodología**  semiautomática, apoyada en la IA para el procesado masivo de datos generados por medios, partidos, gobiernos… y que los catalogue en función de su temática. Para, más tarde explotarlo de distintas maneras que aquí presentamos. 

---
## 🎯 Minado de datos
El minado de datos consiste en un proceso automatizado que accede, descarga y transforma volúmenes grandes de información en conocimiento útil. En nuestro caso,  el proceso comienza con la recolección de datos provenientes de múltiples fuentes, como twitter/X, medios de comunicación, discursos políticos y boletines oficiales, cada uno en un formato distinto. Esta parte del flujo de trabajo automatiza tareas repetitivas, generando una base de datos inicial que nutren las demás herramientas del observatorio.

En el caso de castilla y león hemos obtenido:

- +2.500 tweets de cuentas oficiales
- +20.000 titulares de prensa
- +40 actas del Boletín Oficial de Castilla y León
 

---
## 🚀 Entrenamiento del Clasificador

Una vez obtenida nuestra base de datos "raw", queremos clasificar su contenido por temática (o "guerras"), además de filtrar documentos que no son de interés. Este proceso consta de los siguientes pasos:

- **Obtener los embeddings** de los documentos con LLMs como GPT.
- **Reducir la dimensionalidad** de los embeddings mediante PCA y UMAP.
- **Entrenar un clasificador** con datos etiquetados manualmente y datos sintéticos.

Así, logramos dos cosas: filtramos documentos irrelevantes y clasificamos los importantes en una de las 10 guerras de la extrema derecha lograndoun **R² ~0.9** con validación cruzada. 

En la siguiente figura puedes ver algunos resultados: cada punto representa un documento. Los documentos coloreados han sido etiquetados manualmente y, como puedes ver, los similares en palabras y temática aparecen juntos. Esto es precisamente lo que facilita la clasificación de documentos sin etiquetar (puntos grises).

![Resultados clasificador](https://github.com/pyubero/fr-observatory/blob/main/resultados_clasificador.png  "Resultados clasificador")


---
##  📈 Dinámica de los discursos

Gracias a nuestra base de datos clasificada, podemos analizar **cómo evolucionan los debates históricos**. También nos ayuda a identificar eventos clave que impulsan el discurso de la extrema derecha. Por ejemplo, tras el asesinato de Mocejón (Toledo) el 18 de agosto de 202X, se observa un pico en los discursos contra los migrantes. 


---
## 📨 Newsletter Semanal

También, con la base de datos podemos generar newsletters con un resumen de los temas más importantes de los últimos días.

Ejemplos:

- [Newsletter 15-ene-2023](https://htmlpreview.github.io/?https://github.com/pyubero/fr-observatory/blob/main/newsletters/sample_newsletter-2023-01-15.html)

- [Newsletter 31-ene-2023](https://htmlpreview.github.io/?https://github.com/pyubero/fr-observatory/blob/main/newsletters/sample_newsletter-2023-01-31.html)

