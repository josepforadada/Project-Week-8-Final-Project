<img src="https://www.eaebarcelona.com/sites/eae.bcn/themes/custom/eae_mad/logo.webp" alt="EAE Logo" width="100"/>

# Presentación EAE: GOING TO A MUSIC FESTIVAL

---

## Contenido
- [Introducción](#introducción)
- [Descripción del proyecto](#descripción-del-proyecto)
- [Hipótesis](#hipótesis)
- [Conjunto de datos](#conjunto-de-datos)
- [Limpieza de datos](#limpieza-de-datos)
- [Entrenamiento y evaluación del modelo](#entrenamiento-y-evaluación-del-modelo)
- [Conclusiones](#conclusiones)
- [Trabajo futuro](#trabajo-futuro)
- [Historia: cómo la ia puede mejorar el análisis musical](#historia-cómo-la-ia-puede-mejorar-el-análisis-musical)
- [Futuro de las apis y la ia en el análisis musical](#futuro-de-las-apis-y-la-ia-en-el-análisis-musical)
- [Conclusión de la historia](#conclusión-de-la-historia)
- [Agradecimientos](#agradecimientos)


---

<a name="introducción"></a>
## Introducción: Te va a pasar:

**Contexto:**
Acabas de llegar a Barcelona para estudiar. La ciudad está llena de eventos musicales, pero no sabes a cuál asistir. Con tantas opciones, ¿cómo decides cuál es el concierto adecuado para ti?

**Inicio del Proyecto:**
Una variante de esta situación me llevó a crear un proyecto para analizar y recomendar música usando datos de Spotify. Quería asegurarme de que los eventos a los que asistía coincidieran con mis gustos musicales y no sólo eso quería TOMAR DECISIONES.

---

<a name="descripción-del-proyecto"></a>
## 1. Descripción del Proyecto

**Objetivos:**
- Obtener recomendaciones musicales de Spotify basadas en mis playlists.
- Comparar afinidad entre un festival de música, concierto o cualquier variante con mis playlist de cacnciones favoritas.

---

<a name="hipótesis"></a>
## 2. Hipótesis

**Preguntas Clave:**
- ¿Podemos agrupar las canciones de mi playlist en estilos musicales distintos?
- ¿Es posible solicitar recomendaciones específicas a Spotify?
- ¿Sería una buena idea asistir al próximo festival de música en Barcelona? Como escoger donde ir por la Mercé y el BAM??

---

<a name="conjunto-de-datos"></a>
## 3. Conjunto de Datos

**Fuente de Datos:**
- Usé la API de Spotify y la librería Spotipy para recolectar datos de mis playlists y de la playlist del evento.
- **Desafíos**: La función de recomendaciones en Spotipy tenía un BUG que necesitaba ser resuelto para manejar correctamente las solicitudes. Desconozco la situación actual.

---

<a name="limpieza-de-datos"></a>
## 4. Limpieza de Datos

**Proceso de Limpieza:**
- Wrangling y normalización de datos. 
- Manejo de queries en formato JSON de múltiples niveles.

---

<a name="entrenamiento-y-evaluación-del-modelo"></a>
## 5. Entrenamiento y Evaluación del Modelo

**Modelo Utilizado:**
- K-Means clustering para agrupar canciones en géneros musicales. Dimensionar.
- **Resultados**: Capaz de diferenciar entre música clásica y ópera, pero menos efectivo para géneros similares como Pop, Indie, Rock y Folk. 

**Análisis del Festival:**
- Aplicación del mismo modelo al festival, probando con 3 clusters (Pop, Indie y Rock). Dato recogido de su descripción.

---

<a name="conclusiones"></a>
## 6. Conclusiones

**Principal Conclusión:**
- Las características de las canciones en Spotify no son suficientemente detalladas para etiquetar canciones con precisión basándose solo en esos parámetros.

---

<a name="trabajo-futuro"></a>
## 7. Trabajo Futuro

**Mejoras Propuestas:**
- Contactar a Spotipy para informar sobre el bug que me encontré durante el tratamiento de datos.
- Mejorar la clusterización usando técnicas avanzadas de IA, como deep learning y análisis de segmentos de canciones.

---

<a name="historia-cómo-la-ia-puede-mejorar-el-análisis-musical"></a>
## Historia: Cómo la IA Puede Mejorar el Análisis Musical

**Un Concierto Perfecto:**
Al aplicar IA avanzada, como deep learning y análisis de audio, podemos mejorar significativamente la precisión de las recomendaciones musicales.

**Mejoras Propuestas:**
- Separación de pistas de canciones para analizar vocales, instrumentos y beats por separado.
- Redes neuronales profundas para capturar características complejas.
- Aprendizaje por refuerzo para ajustar recomendaciones basadas en el feedback del usuario. Utilizar APIs de otros proveedores sin encapsularse solo en Spotify

---

<a name="futuro-de-las-apis-y-la-ia-en-el-análisis-musical"></a>
## 11. Futuro de las APIs y la IA en el Análisis Musical

**Avances Recientes:**
- Las nuevas APIs de análisis musical están proporcionando datos más detallados y precisos sobre las características de las canciones.
- La rápida evolución de la IA está mejorando la capacidad de los algoritmos para entender y clasificar la música.

**Potencial de Mejora:**
- **Análisis Más Detallado:** Con las nuevas APIs, podemos obtener datos más granulares, como la separación de instrumentos, patrones rítmicos y estructuras armónicas.
- **Mejores Algoritmos:** Los avances en IA permitirán desarrollar algoritmos de recomendación más sofisticados, capaces de entender matices musicales más finos y proporcionar recomendaciones más precisas.
- **Scores de Análisis:** La combinación de datos más detallados y mejores algoritmos resultará en scores de análisis y coincidencia mucho más precisos, mejorando la experiencia del usuario al encontrar música que realmente disfrute.

---

<a name="conclusión-de-la-historia"></a>
## Conclusión

Gracias a este proyecto, pude determinar si los festivales de música eran adecuados para mis gustos musicales. La IA no solo me ayudó a tomar una decisión informada, sino que también abrió nuevas posibilidades para personalizar y mejorar mi experiencia musical.

[Slides](https://slides.com/josepforadada/deck-6#/)  

---

<a name="agradecimientos"></a>
## Agradecimientos

Espero que esta presentación os proporcione una visión clara de cómo la IA puede revolucionar el análisis musical y las recomendaciones, especialmente en una ciudad vibrante como Barcelona.
