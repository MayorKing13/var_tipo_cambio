![contributors](https://img.shields.io/badge/contributors-1-green)
# **Valor en Riesgo (VaR) en el Tipo de Cambio en Honduras**
## **Descripción del Proyecto**

Este proyecto explora el análisis del **Valor en Riesgo (VaR)** aplicado al tipo de cambio en Honduras, utilizando diferentes métodos como el VaR Histórico y la Simulación de Montecarlo. La finalidad del proyecto es proporcionar una herramienta que permita a inversores independientes, institutos de previsión o empresas evaluar las posibles pérdidas en sus inversiones en dólares.

El notebook cubre conceptos fundamentales, configuraciones de entorno, obtención y limpieza de datos, visualización, pruebas de normalidad, ajuste de distribuciones estadísticas, y finalmente, la estimación del VaR mediante diferentes enfoques.
Contenido

El proyecto incluye los siguientes secciones:

1. **¿Qué es el VaR?**
* Definición matemática y explicación del Valor en Riesgo.
2. **Configuración del Ambiente**
* Configuración del entorno y verificación de las librerías utilizadas.
3. **Obtención de Datos**
* Extracción de datos del Banco Central de Honduras.
4. **Limpieza de Datos**
* Proceso detallado de transformación y limpieza de los datos.
5. **Visualización de Datos**
* Gráficos que muestran la evolución del tipo de cambio y la distribución de las rentabilidades diarias.
6. **Pruebas de Normalidad**
* Evaluación de la normalidad en la distribución de las rentabilidades, utilizando pruebas estadísticas como Shapiro-Wilk y Kolmogorov-Smirnov.
7. **Fitter**
* Ajuste de las distribuciones a los datos utilizando la librería Fitter para mejorar la precisión en la estimación del VaR.
8. **Estimación del VaR**
* Cálculo del VaR utilizando el método histórico y mediante simulación de Montecarlo, explicando los resultados y comparando ambos métodos.
9. **Conclusiones y Recomendaciones**
* Análisis final sobre los métodos empleados y sugerencias para el uso en la gestión de riesgos.
        
## **Requisitos del Proyecto**

Para ejecutar este notebook, necesitas tener instaladas las siguientes librerías en tu entorno de Python:
* **pandas**
* **numpy**
* **matplotlib**
* **seaborn**
* **scipy**
* **fitter**
* **xlrd**

Puedes instalar estas librerías usando pip:

``` bash
pip install pandas numpy matplotlib seaborn scipy fitter xlrd
```

Uso

1. **Clona el repositorio:**
``` bash
git clone https://github.com/MayorKing13/var_tipo_cambio.git
```

2. **Navega al directorio del proyecto:**
   
``` bash
cd var_tipo_cambio
```

3. **Ejecuta el notebook en Jupyter:**

  Abre el archivo .ipynb en Jupyter Notebook o JupyterLab y sigue las instrucciones en cada celda.

## **Resultados Esperados**

El notebook genera una serie de gráficos y análisis que permiten comprender mejor cómo se comporta el tipo de cambio en Honduras y cómo el VaR puede ayudar a gestionar el riesgo en las inversiones. Además, se proporciona una comparación detallada entre los métodos de VaR, mostrando sus ventajas y limitaciones.

## **Contribuciones**

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto o agregar nuevas funcionalidades, por favor, sigue estos pasos:

1. Haz un fork de este repositorio.
2. Crea una rama para tu característica **(`git checkout -b feature/nueva-caracteristica`)**.
3. Realiza tus cambios y haz un commit **(`git commit -m 'Agregar nueva característica'`)**.
4. Sube tus cambios a tu rama **(`git push origin feature/nueva-caracteristica`)**.
5. Abre un Pull Request.

## **Licencia**

Este proyecto está licenciado bajo la Licencia MIT. Puedes ver más detalles en el archivo LICENSE.

## **Contacto**

Si tienes alguna pregunta o sugerencia sobre este proyecto, no dudes en contactarme a través de mayorking13@gmail.com o abre un issue en GitHub.

