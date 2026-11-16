# 🤓 Análise de Vendas - Geek Store

![GitHub License](https://img.shields.io/github/license/seu-usuario/seu-repositorio?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-orange?style=flat-square&logo=pandas)

Este projeto foi desenvolvido para realizar uma análise de dados e engenharia de recursos (feature engineering) sobre a base de vendas de uma loja temática Geek. O script em Python automatiza o cálculo de métricas essenciais de negócios, ajudando a compreender melhor a receita e lucratividade por produto.

## 📌 Funcionalidades

- **Leitura de Dados**: Carga automatizada do histórico de vendas (`vendas_geek_store.csv`).
- **Estatística Descritiva**: Análise rápida das principais métricas estatísticas da base original.
- **Feature Engineering (Engenharia de Recursos)**:
  - **Cálculo de Receita**: `Quantidade_Vendida * Preco_Venda` por transação.
  - **Cálculo de Lucro Unitário**: Margem individual gerada por item (`Preco_Venda - Custo_Fabricante`).
  - **Cálculo de Lucro Final**: Retorno financeiro total líquido por operação comercial.
- **Exportação de Dados**: Geração de um novo arquivo consolidado (`vendas_geek_store_novo.csv`) pronto para integração com ferramentas de BI (Power BI, Tableau) ou dashboards.

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/) (Manipulação e análise de dados estruturados)
- [Jupyter Notebook / Google Colab](https://colab.research.google.com/)

## 📁 Estrutura do Repositório

```bash
├── vendas_geek_store.csv       # Base de dados original (Entrada)
├── vendas_geek_store_novo.csv  # Base de dados enriquecida (Saída)
├── analise_geek_store.ipynb    # Jupyter Notebook com o código desenvolvido
└── README.md                   # Documentação do projeto
🚀 Como Executar o Projeto
Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git
Instale as dependências necessárias (caso execute localmente):

pip install pandas
Abra o notebook no seu ambiente favorito (Jupyter, VS Code ou Google Colab) e execute as células em ordem seqüencial.

📊 Exemplo dos Resultados Calculados
O arquivo final exportado conterá as novas colunas estruturadas para tomada de decisão:

Produto	Categoria	Quantidade_Vendida	Preco_Venda	receita	lucro unidade	lucro final
Action Figure	Colecionáveis	10	R$ 150.00 | R$$ 150.00 | R$ 1500.00	R$ 50.00 | R$$ 50.00 | R$ 500.00		
Desenvolvido com ☕ e paixão pela cultura Geek por https://github.com/AlvaroNCorrea.


### 💡 Dicas para o GitHub:
1. Altere os links de exemplo `seu-usuario` e `seu-repositorio` para apontarem para as suas URLs reais do GitHub.
2. Crie um arquivo chamado `README.md` na raiz do seu repositório do GitHub e cole o código Markdown acima.
