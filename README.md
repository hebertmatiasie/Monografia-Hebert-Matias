# Monografia-Hebert-Matias
Scripts em Python para análise VAR dos impactos das mudanças climáticas no IPCA-Alimentos e na Selic. Inclui pré-processamento, estimação VAR e funções impulso-resposta (IRF)

## 📁 Estrutura do projeto

- **Pré-processamento**: limpeza, junção e transformação das séries temporais.
- **Modelagem VAR**: estimação de modelos Vetoriais Autorregressivos.
- **Função Impulso-Resposta (IRF)**: análise dos efeitos dinâmicos de choques climáticos em indicadores econômicos.
- **Exportação**: gráficos e resultados em PDF e Excel.

## 📦 Requisitos

- Python 3.10+
- `pandas`, `matplotlib`, `statsmodels`, `seaborn`, `openpyxl`, `fpdf` etc.

> (Você pode criar um arquivo `requirements.txt` com `pip freeze > requirements.txt` se quiser facilitar a instalação.)

## 🔁 Reprodutibilidade

Para replicar os resultados:
1. Clone o repositório.
2. Instale as dependências.
3. Execute os scripts na ordem: pré-processamento → VAR → IRF.

---

