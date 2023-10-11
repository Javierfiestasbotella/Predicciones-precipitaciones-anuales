<!DOCTYPE html>
<html>

<head>
    <title>Proyecto de Predicción de Condiciones Climáticas y Precipitación Anual</title>
   
</head>

<body>
    <h1>Predicciones-precipitaciones-anuales</h1>
    <h2>Predicciones climáticas con IA: Combina modelos de regresión y clasificación para anticipar condiciones climáticas y precipitación anual</h2>

    <h1>Proyecto de Predicción de Condiciones Climáticas y Precipitación Anual</h1>

    <h2>Descripción</h2>
    <p>Este proyecto forma parte de mi curso de especialización en inteligencia artificial en la <a href="https://www.tokioschool.com/">Tokio School</a> y tiene como objetivo predecir condiciones climáticas y la precipitación anual en diferentes regiones. Para lograr esto, utilizamos datos climáticos de múltiples fuentes, incluyendo datos de países nórdicos y datos climáticos históricos de España.</p>

    <h2>Contenido del Proyecto</h2>
    <p>El proyecto consta de dos partes principales:</p>
    <ol>
        <li>
            <h3>Predicción de Precipitación Anual:</h3>
            <ul>
                <li>Carga y procesa datos climáticos históricos de múltiples fuentes, incluyendo años previos y regiones nórdicas.</li>
                <li>Entrena un modelo de regresión lineal para predecir el valor anual de la lluvia.</li>
                <li>Define umbrales para determinar el estado climático (normal, sequía, inundación) basado en las predicciones.</li>
            </ul>
        </li>
        <li>
            <h3>Clasificación de Condiciones Climáticas:</h3>
            <ul>
                <li>Divide los datos climáticos en características y etiquetas.</li>
                <li>Entrena un modelo de regresión logística para clasificar los datos en categorías de estado climático (normal, sequía, inundación).</li>
                <li>Evalúa el rendimiento del modelo, generando un informe de clasificación y una matriz de confusión.</li>
            </ul>
        </li>
    </ol>

    <h2>Configuración del Entorno</h2>
    <p>Asegúrate de tener las siguientes bibliotecas de Python instaladas para ejecutar el proyecto:</p>
    <ul>
        <li><code>pandas</code></li>
        <li><code>numpy</code></li>
        <li><code>scikit-learn</code></li>
        <li><code>joblib</code></li>
        <li><code>matplotlib</code></li>
    </ul>

    <h2>Instrucciones de Ejecución</h2>
    <ol>
        <li>Clona este repositorio o descarga los archivos necesarios.</li>
        <li>Asegúrate de tener las bibliotecas requeridas instaladas en tu entorno de Python.</li>
        <li>Ejecuta los scripts proporcionados para cargar datos, entrenar modelos y realizar predicciones.</li>
        <li>Ajusta los umbrales y los datos de entrada según tus necesidades para personalizar las predicciones.</li>
        <li>Explora los resultados y métricas generados por el proyecto.</li>
    </ol>

    <h2>Resultados</h2>
    <p>El proyecto proporciona predicciones de valor anual de lluvia y clasificación de condiciones climáticas para regiones específicas. Los resultados se basan en modelos de aprendizaje automático entrenados en datos históricos.</p>

    <h2>Autor</h2>
    <p><strong>Nombre:</strong> Javier Fiestas Botella</p>

    <h2>Datos de Referencia</h2>
    <p>Los datos climáticos utilizados en este proyecto se obtuvieron de Kaggle y fuentes de clima de Noruega. Los datos de Noruega se han transformado para adaptarse al proyecto.</p>

    <h2>Licencia</h2>
    <p>Este proyecto se publica bajo la Licencia MIT. Consulta el archivo <a href="LICENSE">LICENSE</a> para obtener más detalles.</p>
</body>

</html>

