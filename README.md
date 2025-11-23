# Clasificación de Pingüinos

Este proyecto usa el dataset **Palmer Penguins** para construir un modelo de Machine Learning que predice la **especie de un pingüino** a partir de sus características físicas, como el tamaño del pico, la longitud del flipper, la masa corporal, entre otras.

---

##  Datos

- El dataset contiene **344 pingüinos** con mediciones de tres especies: *Adélie*, *Chinstrap* y *Gentoo*. 
- Variables principales:
  - `species`: especie del pingüino.
  - `island`: isla donde fue observado.
  - `bill_length_mm` y `bill_depth_mm`: 
  - `flipper_length_mm`: longitud del flipper (ala). 
  - `body_mass_g`: masa corporal en gramos.  
  - `sex`: sexo del pingüino. 
---

## 🔧 Metodología

1. **Carga y limpieza de datos**  
   - Lectura del dataset .  
   - Identificación de valores faltantes y su tratamiento.  
   - Conversión de variables categóricas ( sexo) a formato numérico o de codificación adecuada.

2. **Análisis exploratorio (EDA)**  
   - Visualización de distribuciones y relaciones entre variables.  
   - Uso de gráficos para entender cómo las características físicas varían según la especie.

3. **Preparación para el modelo**  
   - Selección de las características más relevantes para la predicción.  
   - Escalado o normalización si es necesario.

4. **Entrenamiento del modelo**  
   - División entre datos de entrenamiento y prueba.  
   - Entrenamiento de un modelo de clasificación (puede ser K-NN, RandomForest, SVM, etc., según lo que hayas implementado).


5. **Conclusiones**  
   - Qué características son más útiles para predecir la especie.  
   - Qué tan bien funciona el modelo y qué podría mejorarse.

---

##  Resultados

- El modelo logra una buena precisión para distinguir entre las 4 especies de pingüinos.  
- Se pueden identificar cuáles son las variables más discriminantes (por ejemplo, longitud de flipper o masa corporal).  

---

## 🛠️ Tecnologías y Librerías

- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 📎 Licencia

Este proyecto está pensado para aprendizaje y práctica. Puedes usarlo libremente con fines educativos.

---

## 👤 Autor

**Felipe** — Aspirante a Científico de Datos con interés en aplicar Machine Learning a datasets reales y ecológicos.

