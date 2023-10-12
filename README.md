<!-- Add background image with transparency -->
<div style="background-image: url('imagen_python_01.png'); background-size: cover; opacity: 0.9;">
    <h1>Proyecto de Predicción de Condiciones Climáticas y Precipitación Anual</h1>
    <p>Este proyecto forma parte de mi curso de especialización en inteligencia artificial en la <a href="https://www.tokioschool.com/">Tokio School</a> y tiene como objetivo predecir condiciones climáticas y la precipitación anual en diferentes regiones. Para lograr esto, utilizamos datos climáticos de múltiples fuentes, incluyendo datos de países nórdicos y datos climáticos históricos de España.</p>
</div>

## Contenido del Proyecto

El proyecto consta de dos partes principales:

### Predicción de Precipitación Anual

- Carga y procesa datos climáticos históricos de múltiples fuentes, incluyendo años previos y regiones nórdicas.
- Entrena un modelo de regresión lineal para predecir el valor anual de la lluvia.
- Define umbrales para determinar el estado climático (normal, sequía, inundación) basado en las predicciones.

### Clasificación de Condiciones Climáticas

- Divide los datos climáticos en características y etiquetas.
- Entrena un modelo de regresión logística para clasificar los datos en categorías de estado climático (normal, sequía, inundación).
- Evalúa el rendimiento del modelo, generando un informe de clasificación y una matriz de confusión.

## Configuración del Entorno

Asegúrate de tener las siguientes bibliotecas de Python instaladas para ejecutar el proyecto:

- `pandas`
- `numpy`
- `scikit-learn`
- `joblib`
- `matplotlib`

## Instrucciones de Ejecución

1. Clona este repositorio o descarga los archivos necesarios.

2. Asegúrate de tener las bibliotecas requeridas instaladas en tu entorno de Python.

3. Ejecuta los scripts proporcionados para cargar datos, entrenar modelos y realizar predicciones.

4. Ajusta los umbrales y los datos de entrada según tus necesidades para personalizar las predicciones.

5. Explora los resultados y métricas generadas por el proyecto.

## Resultados

El proyecto proporciona predicciones de valor anual de lluvia y clasificación de condiciones climáticas para regiones específicas. Los resultados se basan en modelos de aprendizaje automático entrenados en datos históricos.

## Autor

**Nombre:** Javier Fiestas Botella

## Datos de Referencia

Los datos climáticos utilizados en este proyecto se obtuvieron de Kaggle y fuentes de clima de Noruega. Los datos de Noruega se han transformado para adaptarse al proyecto.

## Licencia

Este proyecto se publica bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles.


    <h2>Licencia</h2>
    <p>Este proyecto se publica bajo la Licencia MIT. Consulta el archivo <a href="LICENSE">LICENSE</a> para obtener más detalles.</p>
</body>

</html>

