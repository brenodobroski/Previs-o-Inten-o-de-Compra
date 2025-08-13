# 🛒 Previsão de Intenção de Compra em E-commerce 🛍️

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-black?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006699.svg?style=for-the-badge&logo=xgboost&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0.svg?style=for-the-badge&logo=seaborn&logoColor=white)

## 🎯 Visão Geral do Projeto

Este projeto aborda um dos desafios mais críticos para o varejo online: **entender o comportamento do cliente para prever a sua intenção de compra**. Utilizando um dataset com mais de 12.000 sessões de utilizadores num site de e-commerce, o objetivo é construir um modelo de Machine Learning capaz de classificar se uma sessão terminará em uma compra ou não.

O trabalho demonstra um fluxo completo de ciência de dados para um problema de classificação, incluindo pré-processamento de dados, uma análise exploratória detalhada para gerar insights, e a comparação de múltiplos algoritmos para encontrar o modelo com a melhor performance preditiva.

---

## ✨ Destaques do Projeto

* **Análise Exploratória de Dados (EDA):** Investigação aprofundada sobre como diferentes features (como tipo de visitante, mês da visita e métricas de navegação) se correlacionam com a probabilidade de compra.
* **Pré-processamento Robusto:** Tratamento de variáveis categóricas com `OneHotEncoder` e padronização de features numéricas com `StandardScaler` para otimizar a performance dos modelos.
* **Comparação Abrangente de Modelos:** Avaliação e comparação de 2 algoritmos de classificação diferentes: `Regressão Logística` e `Random Forest`.
* **Métricas de Avaliação de Classificação:** Uso de métricas apropriadas como Acurácia, Precisão, Recall e F1-Score.
* **Otimização com `GridSearchCV`:** Busca sistemática dos melhores hiperparâmetros para o modelo campeão, maximizando sua capacidade preditiva.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Bibliotecas Principais:**
    * `Pandas` & `NumPy` para manipulação de dados.
    * `Matplotlib` & `Seaborn` para visualização.
    * `Scikit-learn` para pré-processamento, modelagem e avaliação.
    * `Logistic Regression` e `RandomForest` para o modelo de gradient boosting.
* **Ambiente:** Jupyter Notebook

---

## 🤖 Performance do Modelo Campeão

Após a comparação e otimização, o modelo **RandomForest** foi coroado o campeão, demonstrando a melhor combinação de métricas de performance para prever a intenção de compra.

| Métrica       | Score (Random Forest Otimizado) |
|---------------|---------------------------|
| **Acurácia** | **89.71%** |
| **Precisão** | **65.87%** |
| **Recall** | **62.68%** |
| **F1-Score** | **64.24%** |

A performance robusta do RandomForest, especialmente o alto valor de acurácia, confirma a sua capacidade de distinguir eficazmente entre sessões que resultarão em compra e as que não resultarão.

---

## 🚀 Como Executar o Projeto

1.  **Clone este repositório:**
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    ```
2.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```
3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```
    *(**Nota:** Você precisará criar um ficheiro `requirements.txt` com as bibliotecas do seu projeto. Pode fazer isso com o comando `pip freeze > requirements.txt` no seu terminal)*

4.  **Execute o Jupyter Notebook:**
    ```bash
    jupyter notebook "Previsão_de_Intenção_de_Compra_de_Clientes_em_Loja_Web.ipynb"
    ```

---

## 👨‍💻 Autor

Breno Dobroski
Linkedin: linkedin.com.br/in/brenodobroski
* **[Seu Nome Completo]**
* **LinkedIn:** [Seu Link do LinkedIn aqui]
* **GitHub:** [Seu Link do GitHub aqui]
