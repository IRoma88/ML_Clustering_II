# 🥣 Clustering de Cereales Comerciales

Este proyecto aplica técnicas de agrupamiento no supervisado (Clustering) para descubrir similitudes entre cereales comerciales en base a sus valores nutricionales.

📁 Dataset utilizado: `cereal.csv`

---

## 📌 Objetivos del Proyecto

1. Carga y limpieza del dataset
2. Análisis de valores faltantes y columnas innecesarias
3. Visualización mediante dendograma (clustering jerárquico)
4. Clustering aglomerativo con representación gráfica
5. Aplicación del método del codo para determinar el número óptimo de clusters
6. Clasificación final de cereales con K-Means

---

## 📊 Visualizaciones Incluidas

- Dendograma para jerarquía de agrupamientos
- Dispersión por:
  - Calorías vs Proteína (por cluster jerárquico)
  - Calorías vs Proteína (por K-Means)
- Método del codo para definir número óptimo de grupos

---

## ⚙️ Requisitos

```bash
git clone https://github.com/tuusuario/clustering-cereales.git
cd clustering-cereales
python -m venv venv
source venv/bin/activate      # En Windows: venv\Scripts\activate
pip install -r requirements.txt
````

## 🔧 Tecnologías Utilizadas
  . Python 3

  . pandas

  . matplotlib

  . scipy

  . scikit-learn

## 📁 Estructura esperada del proyecto

├── cereal.csv

├── clustering_cereales.ipynb

├── requirements.txt

├── .gitignore

└── README.md

## 📝 Licencia
Este proyecto es de uso educativo. Los datos pertenecen a una recopilación de cereales de consumo comercial.
