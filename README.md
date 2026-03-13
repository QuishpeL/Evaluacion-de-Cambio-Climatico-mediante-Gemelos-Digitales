# Evaluacion-de-Cambio-Climatico-mediante-Gemelos-Digitales
Este repositorio contiene el framework de modelado geoespacial para la creación de un Gemelo Digital Climático de la Provincia del Guayas. El sistema integra variables dinámicas de precipitación extrema y modelos hidrológicos estáticos para proyectar escenarios de riesgo de inundación con una resolución de 30 metros.


Especificaciones del ModeloAnclaje Climático: Uso de datos históricos multidecadales (CHIRPS 1981-2025) para la calibración del presente real.Proyección Futura: Ensamble multimodelo de 15 modelos de circulación global (CMIP6) bajo el escenario de emisiones altas (SSP5-8.5).Hidrología de Precisión: Integración de curvas IDF (Intensidad-Duración-Frecuencia) de la estación INAMHI M0056 (Guayaquil Aeropuerto).Análisis HAND (Height Above Nearest Drainage): Normalización topográfica basada en el modelo MERIT Hydro para determinar la vulnerabilidad geomorfológica.Capa Urbana: Identificación de superficies impermeables mediante la base de datos Google Open Buildings V3 para el cálculo de coeficientes de escorrentía variables.

📊 Valor Agregado (Digital Twin)A diferencia de un mapa estático, este script actúa como un gemelo digital que permite:Ajuste de Variables: Modificar el Periodo de Retorno ($Tr$) y Tiempo de Concentración ($tc$) en tiempo real.Stress Test: Evaluar la resiliencia de la infraestructura urbana actual frente a la "lluvia de diseño" del futuro.




