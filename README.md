# proyecto_standar_data_scientist

Grupo de carpetas standar para llevar de forma ordenada tu proyecto data science

├── data/
│   ├── raw/                               <- Data cruda, datos descargados sin modificar
│   ├── external/                          <- Data de fuentes de 3eras partes
│   ├── interim/                           <- Datos intermedios que han sido transformados
│   └── processed/                         <- Datos procesados, que serán usados para el modelo

├── notebooks/                             <- Cuaderno Jupyter (resumen y concatenador de .py)

├── src/
│   ├── clean_scripts/                     <- Scripts para cargar, limpiar, transformar y procesar datos
│   ├── features_scripts/                  <- Scripts para generar características a partir de los datos
│   ├── model_scripts/                     <- Modelos de aprendizaje automático y scripts para entrenarlos y evaluarlos
│   └── visualization_scripts/             <- Scripts para crear visualizaciones de datos

├── reports/                               <- Resultados generados (graficos, informes, etc)
├── README.md                              <- Descripción del proyecto, instrucciones de instalación y uso 
├── requirements.txt                       <- Requerimientos de versiones de librerias necesarias para el proyectos

