# **📁 Challenge TelecomX - Predicción de Cancelación de Clientes (Churn Analysis)**  

**Repositorio:** [github.com/Sebas1020h/Challenge-TelecomX-pt-2](https://github.com/Sebas1020h/Challenge-TelecomX-pt-2)  

## **📌 Descripción**  
Este repositorio contiene un análisis predictivo de **cancelación de clientes (churn)** para una empresa de telecomunicaciones. Se implementaron modelos de Machine Learning (Regresión Logística y Random Forest) para identificar los principales factores que influyen en la rotación de clientes y se proponen estrategias de retención basadas en los resultados.  

---

## **🔍 Contenido del Repositorio**  
| Archivo | Descripción |  
|---------|------------|  
| 📄 **`TelecomX_LATAM_pt2.ipynb`** | Notebook principal con EDA, preprocesamiento, modelado y análisis. |  
| 📊 **`TelecomX_Data.csv`**  | Dataset utilizado para el análisis  |  

---

## **🚀 Resultados Clave**  
✅ **Factores que más influyen en el churn:**  
- **Contratos mensuales** (3.2x más probabilidad de cancelación).  
- **Altos cargos mensuales** (`MonthlyCharges`).  
- **Falta de servicios adicionales** (seguridad online, soporte técnico).  
- **Baja antigüedad del cliente** (`Tenure`).  

📉 **Rendimiento de Modelos:**  
| Modelo | Precisión | Recall (Churn) | F1-Score |  
|--------|-----------|----------------|----------|  
| Regresión Logística | 78% | 72% | 75% |  
| Random Forest | 82% | 76% | 79% |  

---

## **🛠️ Instalación y Uso**  
1. **Clonar el repositorio:**  
   ```bash
   git clone https://github.com/Sebas1020h/Challenge-TelecomX-pt-2.git
   ```  
2. **Ejecutar el notebook:**  
   - Abrir `TelecomX_LATAM_pt2.ipynb` en Jupyter Notebook o Google Colab.  
   - Instalar dependencias (si es necesario):  
     ```bash
     pip install pandas numpy scikit-learn matplotlib seaborn
     ```  

---

## **📊 Estructura del Análisis**  
1. **Preprocesamiento:**  
   - Limpieza de datos.  
   - Codificación de variables categóricas.  
2. **Modelado:**  
   - Entrenamiento de Regresión Logística y Random Forest.  
   - Evaluación con matriz de confusión y curvas ROC.  
3. **Análisis de Variables:**  
   - Importancia de características (coeficientes y feature importance).  
4. **Propuestas de Retención:**  
   - Estrategias basadas en insights del modelo.  

---

## **💡 Aprendizajes y Conclusiones**  
🔹 **Los clientes con contratos a corto plazo y alto gasto son los más propensos a cancelar.**  
🔹 **La falta de servicios de valor agregado (soporte técnico, seguridad) aumenta el riesgo de churn.**  
🔹 **Random Forest superó a Regresión Logística en precisión, pero ambos identificaron factores similares.**  

**📌 Recomendación:**  
> *"Implementar campañas de fidelización para clientes con contratos mensuales y alto gasto, ofreciendo descuentos en planes anuales o servicios gratuitos."*  

---

## 🙌 Créditos

Este proyecto fue desarrollado como parte del curso de análisis de datos con Python impartido en **Alura LATAM**.

---

## 🧑‍💻 Autor

**Sebastián Urrego**  
📫 GitHub: [@Sebas1020h](https://github.com/Sebas1020h)

--- 

**🌟 ¡Si te resulta útil, deja una ⭐ en el repositorio!**  

--- 

**🔗 Más proyectos:** [Portafolio](https://github.com/Sebas1020h)  
