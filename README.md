
# Practical-ml-for-cybersecurity

En este repositorio se muestran más de veinte ejercicios prácticos diferentes aplicados a conjuntos de datos reales para la solución de distintos problemas dentro del ámbito de la seguridad de la información mediante la aplicación de técnicas de Machine Learning.

Los ejercicios forman parte de  curso de UDEMY [**_Machine Learning desde cero: Proyectos reales en Python 3._**](https://www.udemy.com/course/machine-learning-desde-cero/?referralCode=008FE3DCE6F9C5EDA6DC)

En este curso de 30 horas de vídeo se presentan los fundamentos del Machine Learning desde una perspectiva eminentemente práctica. Cada uno de los ejercicios prácticos presentados en este repositorio, se sustentan en un conjunto de fundamentos teóricos y matemáticos que se exponen a lo largo del curso comenzando con la explicación de los conceptos básicos, al alcance de cualquier persona, y construyendo intuiciones hasta la presentación de técnicas complejas.

# Instalación

Para la ejecución de estos ejercicios se recomienda la instalación de la distribución [Anaconda](https://www.anaconda.com/distribution/), donde se incluyen todas las utilidades necesarias.

Una vez instalado Anaconda, pueden descargarse los ejercicios mediante el siguiente comando:
```
git clone https://github.com/shramos/practical-ml-for-cybersecurity.git
```

Con la utilidad [Jupyter Notebook](https://jupyter.org) incluida en Anaconda pueden visualizarse y ejecutarse los ficheros descargados.

**IMPORTANTE:** Para aquellas personas que no dispongan de un entorno adecuado para la instalación de Anaconda, pueden ejecutar los ejercicios en la nube de Google: [Google Colaboratory](.research.google.com) pulsando en el enlace que aparece al comienzo de todos los ejercicios:
  
# Índice de los casos prácticos

1. **Librerías de Machine Learning**  
	1.1. [Introducción a Numpy](1_Introducción%20a%20NumPy.ipynb)  
	1.2. [Introducción a Pandas](2_Introducción%20a%20Pandas.ipynb)   
	1.3. [Introducción a Matplotlib](3_Introducción%20a%20Matplotlib.ipynb)  
2. **Regresión y Clasificación**  
	2.1. [Regresión Lineal: Predicción del coste de un incidente de seguridad](4_Regresión%20Lineal%20-%20Predicción%20del%20coste%20de%20un%20incidente%20de%20seguridad.ipynb)  
	2.2. [Regresión Logística: Detección de correos de SPAM](5_Regresión%20Log%C3%ADstica%20-%20Detección%20de%20SPAM.ipynb)  
3. **Creación de un proyecto de Machine Learning**  
	3.1. [Visualización del conjunto de datos](6_Visualización%20del%20conjunto%20de%20datos.ipynb)  
	3.2. [División del conjunto de datos](7_División%20del%20conjunto%20de%20datos.ipynb)  
	3.3. [Preparación del conjunto de datos](8_Preparación%20del%20conjunto%20de%20datos.ipynb)  
	3.4. [Creación de Pipelines y Transformadores personalizados](9_Creación%20de%20Transformadores%20y%20Pipelines%20personalizados.ipynb)   
	3.5. [Evaluación de los resultados](10_Evaluación%20de%20resultados.ipynb)   
4. **Support Vector Machines (SVM)**  
	4.1. [SVM: Detección de URLs maliciosas](11_Support%20Vector%20Machine%20-%20Detección%20de%20URLs%20maliciosas.ipynb)  
5. **Árboles de decisión**  
	5.1. [Árboles de decisión: Detección de malware en Android](12_Árboles%20de%20decisión%20-%20Detección%20de%20malware%20en%20Android.ipynb)  
	5.2. [Random Forest: Detección de malware en Android](13_Random%20Forests%20-%20Detección%20de%20Malware%20en%20Android.ipynb)  
6. **Selección y Extracción de características**  
	6.1. [Técnicas de selección de características](14_Técnicas%20de%20selección%20de%20caracter%C3%ADsticas.ipynb)  
	6.2. [PCA: Técnicas de extracción de características](15_PCA%20-%20Extracción%20de%20caracter%C3%ADsticas.ipynb)  
	6.3. [Técnicas de selección del modelo](16_Técnicas%20de%20selección%20del%20modelo.ipynb)  
7. **Clustering**  
	7.1. [KMEANS: Detección de transacciones bancarias fraudulentas](17_KMEANS%20-%20Detección%20de%20transacciones%20bancarias%20fraudulentas.ipynb)  
	7.2. [DBSCAN: Detección de transacciones bancarias fraudulentas](18_DBSCAN%20-%20Detección%20de%20transacciones%20bancarias%20fraudulentas.ipynb)  
8. **Algoritmos probabilísticos**  
	8.1. [Naive Bayes: Detección de correos de SPAM](19_Naive%20Bayes%20-%20Detección%20de%20SPAM.ipynb)  
9. **Detección de Anomalías**  
	9.1. [Distribución Gaussiana: Detección de transacciones bancarias fraudulentas](20_Distribución%20Gaussiana%20-%20Detección%20de%20transacciones%20bancarias%20fraudulentas.ipynb)  
	9.2. [Isolation Forest: Detección de transacciones bancarias fraudulentas](21_Isolation%20Forest%20-%20Detección%20de%20transacciones%20bancarias%20fraudulentas.ipynb)   
10. **Redes Neuronales Artificiales**  
	10.1. [RNAs: Detección de transacciones bancarias fraudulentas](22_Redes%20Neuronales%20Artificiales%20-%20Detección%20de%20transacciones%20bancarias%20fraudulentas.ipynb)  


# Descarga de los conjuntos de datos

* [2007 TREC Public Spam Corpus](https://plg.uwaterloo.ca/cgi-bin/cgiwrap/gvcormac/foo07): Conjunto de correos electrónicos de SPAM y legítimos.
* [NSL-KDD](https://iscxdownloads.cs.unb.ca/iscxdownloads/NSL-KDD/#NSL-KDD): Conjunto de datos con flujos de tráfico de red maliciosos y legítimos.
* [URL-2016](https://www.unb.ca/cic/datasets/url-2016.html): Conjunto de datos de URLs maliciosas y legítimas.
* [CICAAGM](https://www.unb.ca/cic/datasets/android-adware.html): Conjunto de tráfico de red producido por aplicaciones Android legítimas y maliciosas.
* [Creditcard](https://www.kaggle.com/mlg-ulb/creditcardfraud#creditcard.csv): Conjunto de datos con transacciones bancarias legítimas y fraudulentas.

**Para más conjuntos de datos relacionados con el ámbito de la seguridad de la información:**
* [Awesome Cybersecurity Datasets](https://github.com/shramos/Awesome-Cybersecurity-Datasets)
