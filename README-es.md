# **Curso de Analítica Web - Universidad Carlos III de Madrid (UC3M)**  
## **Repositorio del Curso**

📌 **[Información del Curso](https://aplicaciones.uc3m.es/cpa/generaFicha?&est=350&plan=392&asig=16507&idioma=1)** | 🏛 **[UC3M](https://www.uc3m.es/Home)**  

[Versión en inglés (English version of README)](./README.md)

Este repositorio contiene mi trabajo para el curso de **Analítica Web** en la **Universidad Carlos III de Madrid (UC3M)**, que completé durante mi estancia de estudios en el extranjero desde **septiembre 2024 hasta diciembre 2024** como parte de mi **grado en Informática**. El curso se centró en la **recuperación, procesamiento y análisis de datos** utilizando **APIs, web scraping y técnicas de visualización de datos**. En la UC3M, este curso forma parte del programa de grado en **Ciencia e Ingeniería de Datos**.

Durante el curso, trabajé principalmente en un **grupo de tres estudiantes**, colaborando en **proyectos y prácticas** que exploran **conjuntos de datos reales, automatización y técnicas analíticas**.

---

## 📁 **Contenido del Repositorio**
Este repositorio incluye **7 prácticas y proyectos principales**, cada uno aplicando conceptos clave de **ciencia de datos** y **analítica web**:

---

### **1. Introducción al Web Scraping**  
✔ **Objetivo de la Práctica**: Aprender conceptos fundamentales de web scraping y extracción ética de datos.  
✔ **Temas Clave**:  
   - Comprensión de la **estructura HTML** y **selectores CSS**.  
   - Uso de **Requests** y **BeautifulSoup** para extraer texto y datos estructurados.  
   - Análisis de **tablas y listas** en formatos estructurados como CSV y JSON.  
   - Respeto del archivo `robots.txt` y directrices éticas de web scraping.  

📌 **Ver Cuaderno de Práctica** ➝ [`Introduction_to_Web_Scraping_Lab.ipynb`](./Introduction_to_Web_Scraping_Lab.ipynb)  

---

### **2. Web Scraping con BeautifulSoup**  
✔ **Objetivo de la Práctica**: Extraer y analizar datos estructurados de sitios web.  
✔ **Temas Clave**:  
   - Uso de **`requests`** y **`BeautifulSoup`** para web scraping.  
   - Navegación por **estructuras DOM HTML** para extraer información.  
   - Implementación de **técnicas de limpieza de datos** para datos web.  
   - **Consideraciones éticas** del web scraping.  

📌 **Ver Cuaderno de Práctica** ➝ [`Beautiful_Soup_Lab.ipynb`](./Beautiful_Soup_Lab.ipynb)  

---

### **3. Web Scraping con Selenium**  
✔ **Objetivo de la Práctica**: Automatizar interacciones del navegador y extraer contenido dinámico de sitios web con uso intensivo de JavaScript.  
✔ **Temas Clave**:  
   - **Selenium WebDriver** para automatización del navegador.  
   - Interacción con **elementos renderizados por JavaScript** y datos cargados por AJAX.  
   - Manejo de **cookies, autenticación de inicio de sesión y envío de formularios**.  
   - Extracción de **datos en tiempo real** de ofertas de trabajo, sitios de comercio electrónico y tablas dinámicas.  

📌 **Ver Cuaderno de Práctica** ➝ [`Selenium_Lab.ipynb`](./Selenium_Lab.ipynb)  

---

### **4. Práctica con la API del Banco Mundial**  
✔ **Objetivo de la Práctica**: Recuperar y analizar **indicadores económicos reales** de la **API del Banco Mundial**.  
✔ **Temas Clave**:  
   - **Extracción de datos** basada en API usando `requests`.  
   - Recuperación y procesamiento de **respuestas JSON**.  
   - Análisis de **tendencias económicas globales** (p.ej., PIB, emisiones de CO₂, distribución de ingresos).  
   - Clasificación de países por **emisiones de CO₂, crecimiento del PIB y estadísticas de población**.  

📌 **Ver Cuaderno de Práctica** ➝ [`Worldbank_API_Lab.ipynb`](./Worldbank_API_Lab.ipynb)  

---

### **5. Práctica de Teoría de Grafos**  
✔ **Objetivo de la Práctica**: Aplicar **conceptos de teoría de grafos** en **análisis de redes**.  
✔ **Temas Clave**:  
   - **Estructuras de grafos**: Nodos, aristas, matrices de adyacencia.  
   - **Algoritmos de camino más corto**: Dijkstra y búsqueda A*.  
   - **Centralidad en redes**: Grado, intermediación, cercanía.  
   - **Análisis basado en grafos** para redes sociales y aplicaciones web.  

📌 **Ver Cuaderno de Práctica** ➝ [`Graph_Theory_Lab.ipynb`](./Graph_Theory_Lab.ipynb)  

---

### **6. Práctica de Visualización de Datos**  
✔ **Objetivo de la Práctica**: Explorar técnicas para la **visualización de datos** para comunicar efectivamente ideas.  
✔ **Temas Clave**:  
   - Creación de visualizaciones **interactivas** y **estáticas**.  
   - Uso de **Matplotlib, Seaborn y Plotly** para gráficos avanzados.  
   - Técnicas de **visualización geoespacial**.  
   - Aplicación de **mejores prácticas** para la presentación de datos.  

📌 **Ver Cuaderno de Práctica** ➝ [`Data_Visualization_Lab.ipynb`](./Data_Visualization_Lab.ipynb)  

---

### **7. Proyecto Final de Analítica Web**  
✔ **Objetivo del Proyecto**: **Desarrollar un sistema de recomendación de empleo** utilizando **TF-IDF** y **Similitud del Coseno** para relacionar usuarios con ofertas de trabajo.  
✔ **Temas Clave**:  
   - **API de Adzuna**: Extracción dinámica de ofertas de trabajo.  
   - **TF-IDF y Similitud del Coseno**: Clasificación de la relevancia de empleos.  
   - **Preprocesamiento de datos**: Manejo de valores faltantes, tokenización de texto.  
   - **Análisis de tendencias salariales históricas** para categorías de empleo.  
   - **Visualización de datos** de tendencias laborales y demanda del mercado.  
   - **Colaboración**: Este proyecto se completó como un **trabajo en grupo** y requirió un amplio trabajo en equipo.  

📌 **Ver Cuaderno del Proyecto** ➝ [`Web_Analytics_Final_Project.ipynb`](./Web_Analytics_Final_Project.ipynb)  

---

## 🔧 **Tecnologías Utilizadas**  
- **Lenguaje de Programación**: **Python**
- **Bibliotecas y Herramientas**:  
  - `requests`, `BeautifulSoup` - Web scraping  
  - `Selenium WebDriver` - Automatización del navegador  
  - `matplotlib`, `seaborn`, `plotly` - Visualización de datos  
  - `scikit-learn`, `nltk`, `pandas`, `numpy` - Análisis de datos e IA  
  - `networkx` - Teoría de Grafos  
  - `TF-IDF` y `Similitud del Coseno` - Sistema de recomendación de empleo  

## 💻 **Cómo Usar**  
- ¡Abre Jupyter Notebook o Google Colab para explorar los archivos .ipynb!
- Algunos archivos de datos de entrada no están incluidos en este repositorio. Si necesitas acceso a estos archivos o te gustaría una demostración funcional del código, por favor contáctame a través de mi sitio web personal en [Marcos-Sanson.github.io](https://marcos-sanson.github.io)

## 🔗 **Enlaces Útiles**
- 📖 [Plan de Estudios del Curso](https://aplicaciones.uc3m.es/cpa/generaFicha?&est=350&plan=392&asig=16507&idioma=1)
- 🏛 [Universidad Carlos III de Madrid](https://www.uc3m.es/Home)
- 📊 [Documentación de la API del Banco Mundial](https://datahelpdesk.worldbank.org/knowledgebase/topics/125589-developer-information)
- 🛠 [API de Adzuna para Datos del Mercado Laboral](https://developer.adzuna.com/overview)
