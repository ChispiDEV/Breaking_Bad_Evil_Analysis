# Breaking Bad Evil Analysis

This repository contains data and analysis scripts for studying Walter White's descent into evil in *Breaking Bad*, focusing on Hubris Syndrome and interpersonal dynamics (On Progress). Techniques such as Natural Language Processing (NLP), graph analysis, and network analysis were used to develop specific dictionaries.

## Objectives
- Study the evolution of Walter White's character in relation to Hubris Syndrome.
- Visualize interpersonal relationships and their impact on the narrative (In Progress).
  
## Repository Structure

Breaking_Bad_Evil_Analysis/ 
├── data/ 
│   ├── dialogues.csv # Processed dialogues from Breaking Bad 
│   ├── hubris_evil_data.csv # Results of the hubris and evil analysis  
│   ├── hubris_lexicon.csv # Dictionary of Hubris terms and their level (On Progress)
│   ├── evil_lexicon.csv # Dictionary of evil terms and their level (On Progress)
├── notebooks/ 
│   ├── analysis.ipynb # Jupyter Notebook with project analysis 
├── README.md # Project description and instructions

## Data Description

### `data/dialogues.csv`
- **Description:** Contains the processed dialogues extracted from the series.
- **Columns:**
  - `Season`: Season number.
  - `Episode`: Episode number.
  - `Line`: The dialogue text.
  - `Speaker`: The character speaking.
- **Source:** Transcribed using Whisper and diarization tools.

### `data/hubris_analysis.csv`
- **Description:** Results of the NLP analysis related to Hubris Syndrome and Evil levels.
- **Columns:**
  - `Season`: Season number.
  - `Episode`: Episode number.
  - `Hubris_Level`: Calculated level of Hubris based on the lexicon.
  - `Evil_Score`: Calculated level of "evil" based on the lexicon.

### `data/hubris_lexicon.csv`
- **Description:** Dictionary of terms related to the symptoms of Hubris Syndrome and their associated characteristics (In Progress).
- **Columns:**
  - `Keyword`: Key term.
  - `Category`: Symptom of Hubris associated with the key term.

### `data/evil_lexicon.csv`
- **Descripción:** Dictionary of terms related to different levels of evil (In Progress).
- **Columnas:**
  - `Keyword`: Key term.
  - `Category`: Level of evil associated with the key term.

## Analysis Notebooks

### `notebooks/analysis.ipynb`
- **Description:** Contains code and visualizations for:
  - Tracking Walter White's transformation.
  - Network analysis of interpersonal relationships (On Process).
  - Evolution of variables such as Hubris and Evil.

## Tools Used
- **Python:** Pandas, NetworkX, Matplotlib
- **Lexicons:** Custom emotional and categorical lexicons
- **Visualization:** Dynamic graphs to track episode-by-episode evolution

## Usage Instructions

1. **Setup:**
   - Clone the repository:
     ```bash
     git clone https://github.com/ChispiDEV/Breaking_Bad_Evil_Analysis.git
     cd Breaking_Bad_Evil_Analysis
     ```

2. **Explore the Data:**
   - Review the CSV files in the `data/` folder.

3. **Run the Analysis:**
   - Open `notebooks/analysis.ipynb` in Jupyter Notebook:
     ```bash
     jupyter notebook notebooks/analysis.ipynb
     ```

4. **Contribute:**
   - Feel free to contribute by submitting pull requests for new analyses or improvements.

## Results
- Identification of patterns in the character's behavior.
- Visualizations illustrating Walter White's transformation.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

**Note:** This repository is a work in progress. Data and scripts will be updated as the project evolves.

---

---

# Análisis de la maldad en Breaking Bad
Este repositorio contiene los datos y scripts de análisis para estudiar la transformación de Walter White en Breaking Bad, enfocándose en el Síndrome de Hubris y las dinámicas interpersonales. Para ello se han utilizado técnicas de Procesamiento de Lenguaje Natural (PLN), grafos y análisis de redes para desarrollar diccionarios específicos.

## Objetivos
- Estudiar la evolución del carácter de Walter White en relación con el Síndrome de Hubris.
- Visualizar las relaciones interpersonales y su impacto en la narrativa (En Proceso).

## Estructura del Repositorio
Breaking_Bad_Evil_Analysis/
├── data/
│   ├── dialogues.csv # Diálogos procesados de Breaking Bad
│   ├── hubris_analysis.csv # Resultados del análisis de hubris y maldad 
│   ├── hubris_lexicon.csv # Diccionario de términos relacionados con Hubris
│   ├── evil_lexicon.csv # Diccionario de términos relacionados con la maldad y su intensidad
├── notebooks/
│   ├── analysis.ipynb # Notebook de análisis del proyecto
├── README.md # Descripción del proyecto e instrucciones

## Descripción de los Datos
### `data/dialogues.csv`
- **Descripción:** Contiene los diálogos procesados extraídos de la serie.
- **Columnas:**
  - `Season`: Número de temporada.
  - `Episode`: Número de episodio.
  - `Line`: Texto del diálogo.
  - `Speaker`: Personaje que habla.
- **Fuente:** Transcrito utilizando herramientas de Whisper y diarización.

### `data/hubris_analysis.csv`
- **Descripción:** Resultados del análisis de NLP relacionados con el Síndrome de Hubris y los niveles de Maldad.
- **Columnas:**
  - `Season`: Número de temporada.
  - `Episode`: Número de episodio.
  - `Hubris_Level`: Nivel calculado de hubris según un léxico personalizado.
  - `Evil_Score`: Nivel calculado de "maldad" según un léxico personalizado.

### `data/hubris_lexicon.csv`
- **Descripción:** Diccionario de términos relacionados con los síntomas del Síndrome de Hubris y las características a la que se asocian (En Proceso).
- **Columnas:**
  - `Keyword`: Palabra clave.
  - `Category`: Síntoma de Hubris al que se asocia dicha palabra clave.

### `data/evil_lexicon.csv`
- **Descripción:** Diccionario de términos relacionados con los diferentes niveles de maldad (En Proceso).
- **Columnas:**
  - `Keyword`: Palabra clave.
  - `Category`: Nivel de maldad al que se asocia dicha palabra clave.

## Notebooks de Análisis

### `notebooks/analysis.ipynb`
- **Descripción:** Contiene código y visualizaciones para:
  - Rastrear la transformación de Walter White.
  - Análisis de redes de relaciones interpersonales.
  - Evolución de variables como Hubris y Maldad.

## Herramientas Utilizadas
- **Python:** Pandas, NetworkX, Matplotlib
- **Lexicones:** Emociones y categorías personalizadas
- **Visualización:** Gráficos dinámicos para la evolución por episodio.

## Instrucciones de Uso

1. **Preparación:**
   - Clona el repositorio:
     ```bash
     git clone https://github.com/ChispiDEV/Breaking_Bad_Evil_Analysis.git
     cd Breaking_Bad_Evil_Analysis
     ```

2. **Explora los Datos:**
   - Revisa los archivos CSV en la carpeta `data/`.

3. **Ejecuta el Análisis:**
   - Abre `notebooks/analysis.ipynb` en Jupyter Notebook:
     ```bash
     jupyter notebook notebooks/analysis.ipynb
     ```

4. **Contribuye:**
   - Contribuye enviando pull requests para nuevos análisis o mejoras.

## Resultados
- Identificación de patrones en el comportamiento del personaje.
- Visualizaciones que ilustran la transformación de Walter White.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---
