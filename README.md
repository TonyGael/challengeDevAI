# Calendario detallado

## **Bloque 1 — Fundamentos (25 ago – 30 oct)**

**Meta:** Python fluido, matemáticas útiles, Data Science stack, ML clásico básico.

---

### **Semana 1 (25 – 29 ago): Python y herramientas**

* **Tema:** Sintaxis de Python, estructuras de datos, funciones, OOP básico.
* **Datasets:** Ninguno aún, pequeños diccionarios/listas creados a mano.
* **Proyecto mini:** Implementar un analizador de texto sencillo (contar palabras, frecuencia, longitud media).

---

### **Semana 2 (1 – 5 sep): Numpy + Álgebra lineal aplicada**

* **Tema:** Vectores, matrices, operaciones, broadcasting, transpuestas, inversas.
* **Dataset:** `Iris dataset` (scikit-learn).
* **Proyecto mini:** Implementar normalización de features manualmente con Numpy.

---

### **Semana 3 (8 – 12 sep): Pandas + Estadística**

* **Tema:** DataFrames, limpieza de datos, agrupación, descriptores estadísticos.
* **Dataset:** **Titanic** (Kaggle open dataset).
* **Proyecto mini:** Predecir supervivencia con estadística descriptiva (sin ML aún).

---

### **Semana 4 (15 – 19 sep): Visualización + Matplotlib/Seaborn**

* **Tema:** Gráficos, histogramas, scatter plots, heatmaps.
* **Dataset:** **World Happiness Report** (Kaggle).
* **Proyecto mini:** Visualizar correlación entre PIB y felicidad en países.

---

### **Semana 5 (22 – 26 sep): Fundamentos de probabilidad y estadística**

* **Tema:** Distribuciones, media, varianza, desviación estándar, teorema de Bayes.
* **Dataset:** **COVID-19 Data Repository by CSSE (Johns Hopkins)**.
* **Proyecto mini:** Visualizar curvas de casos diarios y modelar con una distribución gaussiana.

---

### **Semana 6 (29 sep – 3 oct): ML clásico I (regresiones)**

* **Tema:** Regresión lineal y logística, métricas (MSE, accuracy, precision/recall).
* **Dataset:** **Boston Housing dataset** (o versión libre `California Housing`).
* **Proyecto mini:** Predecir precio de casas con regresión lineal y visualización de errores.

---

### **Semana 7 (6 – 10 oct): ML clásico II (clasificación y clustering)**

* **Tema:** k-NN, árboles de decisión, random forests, k-means.
* **Dataset:** **MNIST dígitos** (o versión pequeña `sklearn digits`).
* **Proyecto mini:** Clasificar imágenes de dígitos con k-NN y comparar con árbol de decisión.

---

### **Semana 8 (13 – 17 oct): Evaluación de modelos y pipelines**

* **Tema:** Overfitting/underfitting, cross-validation, escalado de features, pipelines de scikit-learn.
* **Dataset:** **Wine Quality dataset**.
* **Proyecto mini:** Predecir calidad de vino con random forest y comparar métricas.

---

### **Semana 9 (20 – 24 oct): Repaso integrador de fundamentos**

* **Meta:** Conectar Python + álgebra + estadísticas + ML clásico.
* **Proyecto integrador:**
  Construir un **dashboard en Jupyter** que:

  * Cargue Titanic dataset
  * Haga limpieza con Pandas
  * Visualice correlaciones
  * Modele con regresión logística y random forest
  * Compare resultados

---

### **Semana 10 (27 – 30 oct): Puente hacia Deep Learning**

* **Tema:** Redes neuronales básicas, perceptrón, backpropagation.
* **Dataset:** **Fashion-MNIST**.
* **Proyecto mini:** Implementar un perceptrón simple en Numpy para clasificar ropa.

---

---

## **Bloque 2 — Avanzado y proyectos (1 nov – 31 dic)**

**Meta:** Deep Learning, IA generativa, agentes, despliegue.

---

### **Semana 11 (3 – 7 nov): Redes neuronales profundas**

* **Tema:** MLPs, optimizadores, PyTorch básico.
* **Dataset:** **MNIST**.
* **Proyecto mini:** Clasificación de dígitos con MLP en PyTorch.

---

### **Semana 12 (10 – 14 nov): CNNs**

* **Tema:** Convoluciones, pooling, dropout, transfer learning.
* **Dataset:** **CIFAR-10**.
* **Proyecto mini:** Clasificar imágenes de aviones, autos y gatos.

---

### **Semana 13 (17 – 21 nov): RNNs y NLP**

* **Tema:** Embeddings, LSTMs, GRUs.
* **Dataset:** **IMDb movie reviews** (sentiment analysis).
* **Proyecto mini:** Clasificador de reseñas positivas/negativas.

---

### **Semana 14 (24 – 28 nov): Transformers + LLMs open-source**

* **Tema:** Self-attention, encoder-decoder, Hugging Face.
* **Dataset:** **Wikitext-2** (corpus libre).
* **Proyecto mini:** Entrenar un mini-transformer para predicción de palabras.

---

### **Semana 15 (1 – 5 dic): Generative AI (GANs, VAEs, difusión)**

* **Tema:** Imagen generativa, autoencoders, stable diffusion.
* **Dataset:** **CelebA (caras)** o **MNIST** reducido.
* **Proyecto mini:** Generar nuevas imágenes de dígitos o caras con GAN.

---

### **Semana 16 (8 – 12 dic): Reinforcement Learning**

* **Tema:** Q-learning, DQN.
* **Entorno:** **OpenAI Gym (CartPole, MountainCar)**.
* **Proyecto mini:** Entrenar un agente a mantener la barra en equilibrio (CartPole).

---

### **Semana 17 (15 – 19 dic): MLOps básico**

* **Tema:** FastAPI, Docker, testing de modelos, CI/CD básico.
* **Dataset:** Reutiliza **Wine Quality** o **Titanic**.
* **Proyecto mini:** API REST que sirva un modelo de clasificación de vino.

---

### **Semana 18 (22 – 26 dic): Proyecto final (capstone)**

* **Tema:** Integración completa.
* **Proyecto:**

  * Toma el **Titanic dataset** (u otro dataset real de Kaggle).
  * Haz pipeline completo:

    * Preprocesamiento (Pandas)
    * Visualización
    * ML clásico vs deep learning (scikit-learn + PyTorch)
    * API con FastAPI
    * Docker para despliegue
  * Opcional: deploy en **Hugging Face Spaces** o **Render.com** (free tier).

---

### **Semana 19 (29 – 31 dic): Wrap-up & presentación**

* Pulir proyecto capstone.
* Documentación en **README** estilo profesional.
* Reflexión sobre qué aprendiste y plan para 2026.

---

## 🔑 Estrategia de proyectos

* Mini-proyectos semanales → refuerzan cada técnica aislada.
* Proyecto integrador intermedio (Semana 9) → une todo lo básico.
* Capstone final → despliegue realista, demuestra nivel “AI engineer junior+”.

---
