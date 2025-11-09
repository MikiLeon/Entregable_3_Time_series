# Entregable 3 — Time Series Multivariada
**Máster en Data Science & AI**

## 📌 Descripción del proyecto
Este entregable se centra en el **análisis y modelado de series temporales multivariantes**.  
El objetivo principal es preparar los datos históricos de ventas de múltiples entidades (`unique_id`), explorar patrones temporales, realizar ingeniería de variables y entrenar modelos capaces de predecir valores futuros (en este caso, ventas de Octubre 2015).

Se busca que el alumno:

- Practique manipulación de datos con **pandas** y análisis de series temporales.  
- Experimente técnicas de **feature engineering**, incluyendo variables derivadas de tendencias, estacionalidad y medias móviles.  
- Aprenda a **validar correctamente modelos de series temporales** evitando data/target leakage.  
- Construya y compare modelos de predicción multivariantes, estableciendo un **benchmark inicial** antes de optimizar.

---
## 📁 Estructura del repositorio
 Entregable_3:Time_series

```python
 
├── data/ # Datasets for the exercise 

├── notebooks/ #Notebooks principales con diferente feuture enginnering
     
├── README.md 

└── requirements.txt # Librerías necesarias.

```


---

## ⚙️ Requisitos e instalación

Recomendado:
- Python 3.8+ (preferible 3.9)  
- Entorno virtual (venv / conda)

Instalación con pip:

```python
git clone https://github.com/MikiLeon/Entregable2_Churn.git
cd Entregable3_Time_series
python -m venv .venv
source .venv/bin/activate   # Linux/Mac
.venv\Scripts\activate      # Windows
pip install -r requirements.txt
```
3. Ejecutar notebook
   
El notebook está documentado para reproducir todo el flujo de limpieza y preprocesado,
desde la carga de datos hasta la exportación del dataset final.

``` python 
   jupyter notebook Entregable_3_....ipynb
```
---
## Licencia

Este proyecto está licenciado bajo la [Licencia Apache-2.0](LICENSE).  
Consulta el archivo LICENSE para más detalles o visita la [descripción oficial de la licencia Apache]( http://www.apache.org/licenses/).

---
  ## 👤 **Autoría**
  
  Miguel Ángel García León
  
  📧 miiguelleon@gmail.com

