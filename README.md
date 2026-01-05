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

## 🚀 Como Executar (Google Colab)

Este projeto foi otimizado para execução no **Google Colab**, utilizando a integração de IFrame para exibição do Dashboard.

1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Faça o upload do arquivo `analise_dos_dados_do_sus_em_python.py` ou cole o código em uma célula.
3. Certifique-se de instalar as dependências necessárias executando em uma célula:
   ```python
   !pip install dash pandas numpy scikit-learn tensorflow matplotlib seaborn plotly
---
*Desenvolvido como parte de estudos em Inteligência Artificial e Análise de Sistemas.*
