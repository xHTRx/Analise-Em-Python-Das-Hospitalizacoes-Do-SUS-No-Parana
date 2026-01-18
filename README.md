# Análise de Dados Hospitalares do SUS - Paraná 🏥

Este projeto aplica técnicas avançadas de **Data Science** e **Machine Learning** para analisar dados reais de internações hospitalares do SUS no estado do Paraná. O objetivo é identificar padrões de custos e prever riscos financeiros através de modelos preditivos e prescritivos.

> 🚀 Este projeto consome os dados automaticamente via Pipeline direta do GitHub, permitindo execução imediata no Google Colab.

## 🧠 Técnicas Utilizadas

O projeto percorre o pipeline completo de um Cientista de Dados:

1. **Pré-processamento e ETL:**
   * Limpeza e normalização de dados brutos de Excel.
   * Tratamento de missing values e padronização com `StandardScaler`.

2. **Aprendizado de Máquina (Analytics):**
   * **Clustering (Não Supervisionado):** Segmentação de entidades utilizando *K-Means*, *Gaussian Mixture Models (GMM)* e *Hierarchical Clustering*. A validação do número ideal de clusters foi feita através do **Silhouette Score** e **Método do Cotovelo (Elbow Method)**.
   * **Classificação (Supervisionado):** Treinamento e comparação de modelos (*Random Forest, KNN, Redes Neurais*) para prever o risco de "Alto Gasto". Avaliação via Matriz de Confusão e **Curva ROC/AUC**.

3. **Visualização e BI:**
   * Desenvolvimento de um **Dashboard Interativo** utilizando **Dash (Plotly)**.
   * Visualizações complexas como dispersão 3D de clusters e indicadores de performance (KPIs).

## 🛠️ Tecnologias e Bibliotecas

* **Linguagem:** Python 3.x
* **Data Manipulation:** `Pandas`, `NumPy`
* **Machine Learning:** `Scikit-Learn`, `TensorFlow/Keras`, `Statsmodels`
* **Visualização:** `Plotly`, `Seaborn`, `Matplotlib`
* **Web App:** `Dash`

## 🚀 Como Executar (Google Colab)

Este projeto foi otimizado para execução no **Google Colab**, utilizando integração de IFrame para renderizar o dashboard.

1. Acesse o código através do arquivo `.py` ou `.ipynb` neste repositório.
2. Abra o [Google Colab](https://colab.research.google.com/).
3. Instale as dependências necessárias executando:
   ```python
   !pip install dash pandas numpy scikit-learn tensorflow matplotlib seaborn plotly
4. Execute o código: Os dados serão baixados automaticamente deste repositório e o Dashboard será carregado diretamente na célula de saída.

Desenvolvido por Heitor Augusto Andrade - Analista de Sistemas focado em IA e Dados.

*Desenvolvido como parte de estudos em Inteligência Artificial e Análise de Sistemas.*
