<div style="display: flex; align-items: center; justify-content: space-between; padding: 10px; font-family: Arial, sans-serif;">
  <!-- Logo -->
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Uoc_masterbrand_vertical.png" alt="Logo" style="width: 150px; height: auto;">

  <!-- Detalles -->
  <div style="text-align: right; line-height: 1.6; margin-left: 20px; margin-right: 80px">
    <p style="margin: 0; font-size: 1.2em; font-weight: bold; color: #333;">Proyecto: <span style="color: #878787;">Práctica - Parte 2</span></p>
    <p style="color: #878787;">Juan Luis González Rodríguez - Visualización de datos</span></p>
  </div>
</div>
<br>

# PRA 2 Visualización de datos
En esta práctica se ha realizado un proyecto de visualización sobre el conjunto de datos["Multilevel Monitoring of Activity and Sleep in Healthy People" ](https://physionet.org/content/mmash/1.0.0/). Este conjunto recoje los registros de sueño y actividades de 22 ususarios varones jóvenes.

La visualización se ha desarrollado con Tableau y pueve ser consultada en este [enlace](https://public.tableau.com/views/Vis_pra2/Cuadrodemandosdelsueo?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

La estructura del repositorio es la siguiente

1. **1_get_data**: Descarga y preparación de los datos del estudio MMASH.
2. **2_data_exploration**: Exploración y análisis de los datos de los participantes, incluyendo información demográfica, datos de sueño, muestras de saliva, actividad física, y cuestionarios.
   - `1_user_info_exploration.ipynb`: Análisis de la información demográfica de los usuarios.
   - `2_sleep_exploration.ipynb`: Análisis de los datos de sueño.
   - `3_saliva_exploration.ipynb`: Análisis de las muestras de saliva.
   - `4_RR_exploration.ipynb`: Exploración de los datos de variabilidad de la frecuencia cardíaca.
   - `5_questionnaire_exploration.ipynb`: Análisis de los cuestionarios.
   - `6_activity_exploration.ipynb`: Análisis de los datos de actividad física.
   - `7_actigraph_exploration.ipynb`: Exploración de los datos de actigrafía.
3. **3_visual_analytic_exploration**: Análisis visual y exploración analítica de la relación entre diferentes variables.
   - `1_stress_anxiety_and_sleep.ipynb`: Análisis de la relación entre el estrés, la ansiedad y la calidad del sueño.
   - `2_hormones_changes.ipynb`: Análisis de los cambios hormonales y su relación con el sueño.
   - `3_activity_and_sleep.ipynb`: Análisis de la relación entre la actividad física y el sueño.
   - `4_inclinometer_and_sleep.ipynb`: Exploración de los datos del inclinómetro y su relación con el sueño.
4. **4_visualizations**: Preparación de los datos para la creación de visualizaciones finales y fichero de Tableau con la visualización.

## Requisitos

Para ejecutar los notebooks, asegúrate de tener instaladas las dependencias listadas en `requirements.txt`. Puedes instalarlas usando pip:

```sh
pip install -r requirements.txt
```