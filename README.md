# 📷 Proyecto de Estimación de Edad por Imágenes

👋 ¡Hola! Soy Víctor, Data Scientist Junior.  
Te comparto un resumen sencillo del proyecto que predice la edad de personas a partir de sus fotos.

---

## 🔍 Introducción  
Exploramos un conjunto de casi 7 600 imágenes con edades reales, revisamos su calidad y construimos un modelo de aprendizaje profundo para estimar la edad.

---

## 🎯 Objetivos  
- 🔎 **Analizar** la distribución de edades y posibles sesgos en los datos.  
- 🛠️ **Preparar** pipelines de carga y aumento de imágenes para entrenar en GPU.  
- 🤖 **Diseñar** y entrenar un modelo de redes neuronales que prediga la edad con alta precisión.

---

## 📌 Hallazgos Clave  
1. La mayoría de las imágenes corresponde a personas de 20–30 años, con pocas muestras en extremos (niños y mayores).  
2. No hay valores faltantes ni problemas de formato en los datos.  
3. La diversidad visual es buena, pero es vital equilibrar los grupos de edad al entrenar.  
4. El modelo personalizado superó a arquitecturas estándar y alcanzó un MAE cercano a la meta.

---

## 🚀 Conclusiones  
- 🧩 El balance de rangos de edad es crucial para mejorar la precisión en extremos.  
- ⚙️ Las técnicas de aumento y callbacks (ReduceLROnPlateau y EarlyStopping) optimizaron el entrenamiento.  
- 📈 El modelo logró un MAE de ~8.65 años, mostrando que la estrategia funcionó, aunque aún hay espacio para mejorar.  
- 🔄 Futuras mejoras: equilibrar datos, ajustar arquitecturas y explorar nuevas técnicas de preprocesamiento.

---

💡 Todo el código y los detalles están disponibles en este repositorio. ¡Gracias por tu interés!  
