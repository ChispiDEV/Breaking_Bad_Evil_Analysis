# 🔬 Welcome to _Breaking Bad Evil Analysis'_ Project! 🎭 // 🔬 ¡¡Bienvenido al proyecto de _Análisis de la Maldad en Breaking Bad_!!  🎭
📌 *Natural Language Processing (NLP) | Graph Analysis | Network Analysis*  

---  
# 🌍 English Version  
This repository contains **data and analysis scripts** for studying **Walter White's descent into evil** in *Breaking Bad*, focusing on **Hubris Syndrome** and interpersonal dynamics *(On Progress 🚧)*.  
Specifically generated dictionaries, **Natural Language Processing (NLP)**, **Graph Analysis**, and **Network Analysis** were used.  

---  
## 🎯 Objectives  
- 📈 **Study** the evolution of Walter White's character in relation to **Hubris Syndrome**.  
- 🔍 **Visualize** interpersonal relationships and their impact on the narrative *(In Progress 🚧)*.  

---  
## 📁 Repository Structure  

📂 **Breaking_Bad_Evil_Analysis/**  
├── 📂 *Breaking_Bad_Evil_Analysis_1.0-Capstone*  
│   ├── 📁 *data/*  
│   │   ├── 🗂️ `dialogues.csv` → Processed dialogues from *Breaking Bad*  
│   │   ├── 📊 `hubris_evil_data.csv` → Results of the *Hubris* and *Evil* analysis  
│   │   ├── 📖 `hubris_lexicon.csv` → Dictionary of *Hubris* terms *(On Progress 🚧)*  
│   │   ├── 📖 `evil_lexicon.csv` → Dictionary of *Evil* terms *(On Progress 🚧)*  
│   ├── 📁 *notebooks/*  
│   │   ├── 📜 `analysis.ipynb` → Jupyter Notebook with project analysis  
├── 📂 *Breaking_Bad_Evil_Analysis_2.0*  
├── 📜 `README.md` → Project description and instructions  

---  
## 📝 Data Description  
### 🗂️ `data/dialogues.csv`  
- 📝 **Description:** Contains the **processed dialogues** extracted from the series.  
- 📌 **Columns:**  
  - 📅 `Season`: Season number.  
  - 🎬 `Episode`: Episode number.  
  - 💬 `Line`: The dialogue text.  
  - 🗣️ `Speaker`: The character speaking.  
- 🔗 **Source:** Transcribed using **Whisper** and **diarization** tools.  

### 📊 `data/hubris_analysis.csv`  
- 📝 **Description:** Results of the **NLP analysis** related to *Hubris Syndrome* and *Evil levels*.  
- 📌 **Columns:**  
  - 📅 `Season`: Season number.  
  - 🎬 `Episode`: Episode number.  
  - 📊 `Hubris_Level`: Calculated level of **Hubris** based on the lexicon.  
  - 🔥 `Evil_Score`: Calculated level of **Evil** based on the lexicon.  

### 📖 `data/hubris_lexicon.csv`  
- 📝 **Description:** Dictionary of terms related to the **symptoms of Hubris Syndrome** and their associated characteristics *(In Progress 🚧)*.  
- 📌 **Columns:**  
  - 🔑 `Keyword`: Key term.  
  - 🏷️ `Category`: Symptom of *Hubris* associated with the key term.  

### 📖 `data/evil_lexicon.csv`  
- 📝 **Description:** Dictionary of terms related to **different levels of Evil** *(In Progress 🚧)*.  
- 📌 **Columns:**  
  - 🔑 `Keyword`: Key term.  
  - 🏷️ `Category`: Level of *Evil* associated with the key term.  

---  
## 📊 Analysis Notebooks  
### 📜 `notebooks/analysis.ipynb`  
- 🔍 **Contains code and visualizations for:**  
  - 📉 **Tracking** Walter White's transformation.  
  - 🔗 **Network analysis** of interpersonal relationships *(On Process ⚙️ // Version 2.0)*.  
  - 🔥 **Evolution of variables** such as **Hubris** and **Evil**.  

---  
## 🛠️ Tools Used  
- 🐍 **Python:** Pandas, NetworkX, Matplotlib  
- 📖 **Lexicons:** Custom emotional and categorical lexicons  
- 📊 **Visualization:** Dynamic graphs to track **episode-by-episode evolution**  

---  
## 🚀 Usage Instructions  
1️⃣ **Setup:**  
   ```bash
   git clone https://github.com/ChispiDEV/Breaking_Bad_Evil_Analysis.git
   cd Breaking_Bad_Evil_Analysis
   ```  
2️⃣ **Explore the Data:** 🔍 Review the CSV files in the `data/` folder.  

3️⃣ **Run the Analysis:** 🧪 Open `notebooks/analysis.ipynb` in Jupyter Notebook:  
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```  
4️⃣ **Contribute:** 🤝 Feel free to submit *pull requests* with improvements or new analyses.  

---  
## 📊 Results  
✅ **Identification of patterns** in the character's behavior.  
📈 **Visualizations** illustrating Walter White's transformation.  

---  
## 📜 License  
This project is licensed under the **MIT License**. See the `LICENSE` 📄 file for details.  

---  
## ⚠️ Note  
🚧 **This repository is a work in progress.** Data and scripts will be updated as the project evolves. Stay tuned! 🎬  

---  

---
# 🌍 Versión en Español   
📌 Este repositorio contiene los *datos y scripts de análisis* para estudiar *el descenso a la maldad* de Walter White en *Breaking Bad*, centrándose en el **Síndrome de Hubris** y las dinámicas interpersonales *(Trabajo en curso 🚧)*.  
Para ello se utilizaron diccionarios generados específicamente, técnicas de **Procesamiento del Lenguaje Natural (NLP)**, **Análisis Gráfico** y **Análisis de Redes**. 

---  
## 🎯 Objetivos  
- 📈 **Estudiar** la evolución del carácter de Walter White en relación con el Síndrome de Hubris.  
- 🔍 **Visualizar** las relaciones interpersonales y su impacto en la narrativa *(En Desarrollo 🚧)*.  

---  
## 📁 Estructura del Repositorio  
📂 **Breaking_Bad_Evil_Analysis/**  
├── 📂 *Breaking_Bad_Evil_Analysis_1.0-Capstone*  
│   ├── 📁 *data/*  
│   │   ├── 🗂️ `dialogues.csv` → Diálogos procesados de *Breaking Bad*  
│   │   ├── 📊 `hubris_analysis.csv` → Resultados del análisis de *Hubris* y *Maldad*  
│   │   ├── 📖 `hubris_lexicon.csv` → Diccionario de términos sobre *Hubris*  
│   │   ├── 📖 `evil_lexicon.csv` → Diccionario de términos sobre *Maldad*  
│   ├── 📁 *notebooks/*  
│   │   ├── 📜 `analysis.ipynb` → Notebook con análisis del proyecto  
├── 📂 *Breaking_Bad_Evil_Analysis_2.0*  
├── 📜 `README.md` → Descripción del proyecto e instrucciones  

---  
## 📝 Descripción de los Datos  
### 🗂️ `data/dialogues.csv`  
- 📝 **Descripción:** Contiene los diálogos extraídos de la serie.  
- 📌 **Columnas:**  
  - 📅 `Season`: Número de temporada.  
  - 🎬 `Episode`: Número de episodio.  
  - 💬 `Line`: Texto del diálogo.  
  - 🗣️ `Speaker`: Personaje que habla.  
- 🔗 **Fuente:** Transcrito utilizando **Whisper** y **diarización**.  

### 📊 `data/hubris_analysis.csv`  
- 📝 **Descripción:** Resultados del análisis de *NLP* relacionados con el **Síndrome de Hubris** y los niveles de *Maldad*.  
- 📌 **Columnas:**  
  - 📅 `Season`: Temporada.  
  - 🎬 `Episode`: Episodio.  
  - 📊 `Hubris_Level`: Nivel de *Hubris* según un léxico personalizado.  
  - 🔥 `Evil_Score`: Nivel de *Maldad* según un léxico personalizado.  

---  
## 📊 Notebooks de Análisis  
### 📜 `notebooks/analysis.ipynb`  
- 🔍 **Contiene código y visualizaciones para:**  
  - 📉 Rastrear la transformación de *Walter White*.  
  - 🔗 Análisis de redes de relaciones interpersonales.  
  - 🔥 Evolución de variables como **Hubris** y **Maldad**.  

---  
## 🛠️ Herramientas Utilizadas  
- 🐍 **Python:** Pandas, NetworkX, Matplotlib  
- 📖 **Lexicones:** Diccionarios de emociones y categorías personalizadas  
- 📊 **Visualización:** Gráficos dinámicos por episodio  

---  
## 🚀 Instrucciones de Uso  
1️⃣ **Preparación:**  
   ```bash
   git clone https://github.com/ChispiDEV/Breaking_Bad_Evil_Analysis.git
   cd Breaking_Bad_Evil_Analysis
   ```  
2️⃣ **Explora los Datos:** 🔍 Revisa los archivos CSV en `data/`.  

3️⃣ **Ejecuta el Análisis:** 🧪 Abre `notebooks/analysis.ipynb` en Jupyter Notebook:  
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```  
4️⃣ **Contribuye:** 🤝 Envia *pull requests* con mejoras o nuevos análisis.  

---  
## 📊 Resultados  
✅ Identificación de patrones en el comportamiento del personaje.  
📈 Visualizaciones que ilustran la transformación de *Walter White*.  

---  
## 📜 Licencia  
Este proyecto está bajo la licencia **MIT**. Consulta el archivo `LICENSE` 📄 para más detalles.  

---  
## ⚠️ Nota  
🚧 **Este repositorio está en desarrollo**. Los datos y scripts se actualizarán conforme avance el proyecto. ¡Mantente al tanto! 🎬 

---  

---
