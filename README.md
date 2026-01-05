# Análise de Dados Hospitalares do SUS 🏥

Este projeto aplica técnicas de **Data Science** e **Machine Learning** para analisar dados de internações hospitalares (simulados baseados em estrutura do SUS). O objetivo é identificar padrões de custos e prever riscos financeiros para auxiliar na gestão hospitalar.

## Bibliotecas Utilizadas

pandas
numpy
scikit-learn
tensorflow
matplotlib
seaborn
dash
plotly

## 🧠 Técnicas Utilizadas

O projeto foi dividido em três etapas principais:

1.  **Pré-processamento:**
    * Limpeza e normalização de dados (`StandardScaler`).
    * Engenharia de atributos.

2.  **Aprendizado de Máquina:**
    * **Clustering (Não Supervisionado):** Segmentação dos hospitais utilizando *K-Means*, *Gaussian Mixture Models (GMM)* e *Hierarchical Clustering*. A escolha do melhor modelo foi baseada no *Silhouette Score*.
    * **Classificação (Supervisionado):** Comparação de modelos (*Random Forest, KNN, Redes Neurais*) para prever a probabilidade de "Alto Gasto".

3.  **Visualização de Dados:**
    * Desenvolvimento de um **Dashboard Interativo** utilizando a biblioteca **Dash (Plotly)**.
    * Gráficos 3D para clusters, Matriz de Confusão e Curva ROC.

## 🛠️ Tecnologias

* **Linguagem:** Python 3.x
* **Análise de Dados:** Pandas, NumPy
* **ML & AI:** Scikit-Learn, TensorFlow (Keras)
* **Visualização:** Plotly, Seaborn, Matplotlib
* **Web App:** Dash

## 🚀 Como Executar

1.  Clone este repositório.
2.  Instale as dependências:
    ```bash
    pip install pandas numpy scikit-learn tensorflow matplotlib seaborn dash plotly
    ```
3.  Execute o arquivo principal:
    ```bash
    python analise_sus_dashboard.py
    ```
4.  O dashboard ficará acessível no seu navegador em `http://127.0.0.1:8050/`.

---
*Desenvolvido como parte de estudos em Inteligência Artificial e Análise de Sistemas.*
