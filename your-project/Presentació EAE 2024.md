# Presentación EAE: GOING TO A MUSIC FESTIVAL

---

## Introducción: Te va a pasar:

**Contexto:**
Acabas de llegar a Barcelona para estudiar. La ciudad está llena de eventos musicales, pero no sabes a cuál asistir. Con tantas opciones, ¿cómo decides cuál es el concierto adecuado para ti?

**Inicio del Proyecto:**
Una variante de esta situación me llevó a crear un proyecto para analizar y recomendar música usando datos de Spotify. Quería asegurarme de que los eventos a los que asistía coincidieran con mis gustos musicales y no sólo eso quería TOMAR DECISIONES.

---

## 1. Descripción del Proyecto

**Objetivos:**
- Obtener recomendaciones musicales de Spotify basadas en mis playlists.
- Comparar canciones de un festival con los clusters generados a partir de mis playlists.

---

## 2. Hipótesis

**Preguntas Clave:**
- ¿Podemos agrupar las canciones de mi playlist en estilos musicales distintos?
- ¿Es posible solicitar recomendaciones específicas a Spotify?
- ¿Sería una buena idea asistir al próximo festival de música en Barcelona?

---

## 3. Conjunto de Datos

**Fuente de Datos:**
- Usé la API de Spotify y la librería Spotipy para recolectar datos de mis playlists.
- **Desafíos**: La función de recomendaciones en Spotipy tenía un bug que necesitaba ser resuelto para manejar correctamente las solicitudes.

---

## 4. Limpieza de Datos

**Proceso de Limpieza:**
- Wrangling y normalización de datos.
- Manejo de queries en formato JSON de múltiples niveles.

---

## 5. Entrenamiento y Evaluación del Modelo

**Modelo Utilizado:**
- K-Means clustering para agrupar canciones en géneros musicales.
- **Resultados**: Capaz de diferenciar entre música clásica y ópera, pero menos efectivo para géneros similares como Pop, Indie, Rock y Folk.

**Análisis del Festival:**
- Aplicación del mismo modelo al festival, probando con 3 clusters (Pop, Indie y Rock). Dato recogido de su descripción

---

## 6. Conclusiones

**Principal Conclusión:**
- Las características de las canciones en Spotify no son suficientemente detalladas para etiquetar canciones con precisión basándose solo en esos parámetros.

---

## 7. Trabajo Futuro

**Mejoras Propuestas:**
- Contactar a Spotipy para informar sobre el bug que me encontré durante el ttratamiento de datos.
- Mejorar la clusterización usando técnicas avanzadas de IA, como deep learning y análisis de segmentos de canciones.

---

## 8. Flujo de Trabajo

**Pasos Seguidos:**
1. Obtener los Datos
2. Wrangling de Datos

---

## 9. Organización

**Método Personal:**
- Prefiero dibujar esquemas en papel usando lápiz, lo que mejora mi visualización debido a mi formación en diseño y 3D.
- Utilizo bocetos y storyboards para estructurar mi trabajo.

---

## 10. Enlaces y Recursos

- [Artículo en Medium sobre la idea de los gráficos polares](https://towardsdatascience.com/profiling-my-favorite-songs-on-spotify-through-clustering-33fee591783d)

---

## Historia: Cómo la IA Puede Mejorar el Análisis Musical

**Un Concierto Perfecto:**
Al aplicar IA avanzada, como deep learning y análisis de audio, podemos mejorar significativamente la precisión de las recomendaciones musicales.

**Mejoras Propuestas:**
- Separación de pistas de canciones para analizar vocales, instrumentos y beats por separado.
- Redes neuronales profundas para capturar características complejas.
- Aprendizaje por refuerzo para ajustar recomendaciones basadas en el feedback del usuario.

---

## 11. Futuro de las APIs y la IA en el Análisis Musical

**Avances Recientes:**
- Las nuevas APIs de análisis musical están proporcionando datos más detallados y precisos sobre las características de las canciones.
- La rápida evolución de la IA está mejorando la capacidad de los algoritmos para entender y clasificar la música.

**Potencial de Mejora:**
- **Análisis Más Detallado:** Con las nuevas APIs, podemos obtener datos más granulares, como la separación de instrumentos, patrones rítmicos y estructuras armónicas.
- **Mejores Algoritmos:** Los avances en IA permitirán desarrollar algoritmos de recomendación más sofisticados, capaces de entender matices musicales más finos y proporcionar recomendaciones más precisas.
- **Scores de Análisis:** La combinación de datos más detallados y mejores algoritmos resultará en scores de análisis y coincidencia mucho más precisos, mejorando la experiencia del usuario al encontrar música que realmente disfrute.

---

## Conclusión de la Historia

Gracias a este proyecto, pude determinar si los festivales de música eran adecuados para mis gustos musicales. La IA no solo me ayudó a tomar una decisión informada, sino que también abrió nuevas posibilidades para personalizar y mejorar mi experiencia musical.

---

## Agradecimientos

Espero que esta presentación os proporcione una visión clara de cómo la IA puede revolucionar el análisis musical y las recomendaciones, especialmente en una ciudad vibrante como Barcelona. 
