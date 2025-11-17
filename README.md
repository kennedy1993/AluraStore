# 📊 AluraStore – Análise de Prejuízo nas Lojas

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![DataScience](https://img.shields.io/badge/Data%20Science-Insights-orange)

Este projeto foi desenvolvido como parte dos estudos em **Ciência de Dados**, utilizando **Python** para analisar dados de vendas e identificar quais lojas estavam gerando maior prejuízo.

## 🚀 Tecnologias Utilizadas
- **Python 3**
- **Pandas**: Manipulação e análise de dados.
- **NumPy**: Operações matemáticas.
- **Matplotlib / Seaborn**: Visualização gráfica.
- **Jupyter Notebook**: Ambiente interativo para análise.

## 📚 Objetivo do Projeto
O objetivo é aplicar conceitos de **Data Science** para:
- Carregar e tratar dados de vendas.
- Calcular métricas financeiras.
- Identificar lojas com maior prejuízo.
- Gerar visualizações para apoiar decisões.

## 🖥️ Funcionalidades
- Leitura e limpeza dos dados.
- Cálculo de lucro/prejuízo por loja.
- Ranking das lojas com maior prejuízo.
- Gráficos para análise visual.

## 📂 Estrutura do Projeto
```
AluraStore/
├── data/
│   └── vendas.csv
├── notebooks/
│   └── analise_prejuizo.ipynb
├── src/
│   └── analise.py
└── README.md
```

## 🔗 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/kennedy1993/AluraStore.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook:
   ```bash
   jupyter notebook notebooks/analise_prejuizo.ipynb
   ```

## 📊 Exemplo de Gráfico
![Exemplo de Gráfico](https://img.shields.io/badge/Gráfico-Exemplo-lightgrey)

```python
import pandas as pd
import matplotlib.pyplot as plt

# Exemplo simples de gráfico
lojas = ['Loja A', 'Loja B', 'Loja C']
prejuizos = [15000, 23000, 12000]

plt.bar(lojas, prejuizos, color=['red', 'orange', 'blue'])
plt.title('Prejuízo por Loja')
plt.xlabel('Lojas')
plt.ylabel('Prejuízo (R$)')
plt.show()
```

## 🛠️ Melhorias Futuras
- Implementar dashboard interativo com **Streamlit** ou **Dash**.
- Adicionar previsão de vendas usando **Machine Learning**.
- Criar alertas automáticos para lojas com prejuízo.

## 👨‍💻 Autor
**Kennedy Monteiro de Lima**  
[LinkedIn](https://www.linkedin.com/in/kennedymonteirodelima/) | [GitHub](https://github.com/kennedy1993)
