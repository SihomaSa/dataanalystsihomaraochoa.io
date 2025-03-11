# 🚗 Predicción de Accidentes de Tránsito  

Este repositorio contiene los resultados de un modelo de aprendizaje automático que predice la ocurrencia de accidentes de tránsito en Perú, utilizando datos abiertos y técnicas de Machine Learning.  

## 📊 Resultados Visualizados  
Los gráficos generados incluyen:  

- **Matriz de Confusión**: Muestra los aciertos y errores del modelo.  
- **Curva ROC**: Evalúa la capacidad del modelo para distinguir entre accidentes y no accidentes.  

### 🔗 **Ver los resultados en GitHub Pages**  
Puedes ver los resultados directamente en:  
[🔗 https://TU_USUARIO.github.io/NOMBRE_DEL_REPOSITORIO/](https://TU_USUARIO.github.io/NOMBRE_DEL_REPOSITORIO/)  

## 🛠 Herramientas utilizadas  
- **Python** (pandas, scikit-learn, seaborn, matplotlib)  
- **Machine Learning** (Random Forest, SMOTE para balanceo de datos)  
- **Visualización de datos** (matplotlib, seaborn)  
- **GitHub Pages** para publicar los resultados  

## 📂 Archivos en este repositorio  
- `index.html` → Página web con los resultados  
- `matriz_confusion.png` → Imagen de la matriz de confusión  
- `curva_roc.png` → Imagen de la curva ROC  
- `README.md` → Explicación del proyecto  

## 📈 ¿Cómo se generaron los gráficos?  
Los gráficos fueron creados en Python y guardados como imágenes con el siguiente código:  

```python
plt.savefig("matriz_confusion.png")
plt.savefig("curva_roc.png")
