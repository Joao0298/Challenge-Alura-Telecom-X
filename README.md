# 📊 Projeto de Análise de Evasão de Clientes (Churn) - Telecom X

## 🎯 Objetivo do Projeto

Este projeto visa realizar uma **Análise Exploratória de Dados (EDA)** completa sobre o problema de evasão de clientes (Churn) da empresa de telecomunicações fictícia **Telecom X**. O foco é identificar os principais fatores de risco que levam os clientes a cancelar seus serviços, fornecendo *insights* estratégicos para a equipe de Data Science e para a tomada de decisões de retenção.

## 🛠️ Tecnologias e Bibliotecas

*   **Linguagem:** Python
*   **Manipulação de Dados:** Pandas
*   **Análise Numérica:** NumPy
*   **Visualização de Dados:** Matplotlib e Seaborn
*   **Formato de Entrega:** Jupyter Notebook (`TelecomX_Desafio_Final.ipynb`)

## 🚀 Estrutura do Projeto

O projeto segue uma metodologia robusta de análise de dados, abrangendo as seguintes etapas:

1.  **Extração (E):** Carregamento e achatamento (flattening) do dataset original em formato JSON.
2.  **Transformação (T):**
    *   Tratamento de inconsistências e valores nulos.
    *   Conversão de tipos de dados.
    *   Criação de variáveis de engenharia de *features*, como a coluna `Contas_Diarias`.
3.  **Carga (L) e Análise Exploratória (EDA):**
    *   Cálculo da Taxa Geral de Churn.
    *   Análise de variáveis categóricas (Contrato, Serviço de Internet, etc.).
    *   Análise de variáveis numéricas (Tenure, Cobranças Mensais e Totais) vs. Churn.
    *   Geração de visualizações estratégicas (Boxplots e Barplots).
4.  **Relatório Final:** Documentação completa com Introdução, Metodologia, Conclusões e Recomendações.

## 💡 Principais Insights

A análise revelou que os principais *drivers* de Churn estão ligados a:

*   **Tipo de Contrato:** Clientes com contrato **mensal** apresentam o maior risco de evasão.
*   **Tempo de Contrato (Tenure):** A maior parte dos cancelamentos ocorre nos **primeiros meses** de serviço.
*   **Cobrança Mensal:** Clientes com **faturas mais altas** têm maior propensão a cancelar, sugerindo um problema de valor percebido.

## 📈 Como Visualizar

O arquivo principal do projeto é o `TelecomX_Desafio_Final.ipynb`. Para visualizar a análise completa, basta abrir este notebook em qualquer ambiente Jupyter (JupyterLab, VS Code, Google Colab).

---
**Autor:** João Nunes
**Status:** Concluído
**Data:** Janeiro/2026
