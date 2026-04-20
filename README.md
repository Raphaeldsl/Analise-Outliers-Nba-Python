# 🏀 Análise de Dados da NBA – Detecção de Outliers com IQR

## 📌 Sobre o projeto
Este projeto tem como objetivo analisar dados reais de jogadores da NBA, com foco na identificação e tratamento de outliers utilizando o método do Intervalo Interquartil (IQR).

A análise foi realizada em Python no Google Colab, explorando como valores atípicos impactam a distribuição dos dados e a qualidade das análises estatísticas.

## 📂 Base de dados
Dataset utilizado:
https://www.kaggle.com/datasets/damirdizdarevic/nba-dataset-eda-and-ml-compatible

Os dados contêm informações reais de jogadores da NBA, incluindo características físicas como altura.

## 🚀 Tecnologias utilizadas
- Python
- Pandas
- Matplotlib
- Google Colab

## 🔍 Etapas do projeto
- Importação e leitura dos dados
- Introdução de outliers artificiais
- Análise da distribuição com histogramas
- Aplicação do método IQR
- Identificação e remoção de outliers
- Reanálise da distribuição após tratamento

## 📈 Principais insights
- A presença de outliers altera significativamente a distribuição dos dados
- O método IQR é eficaz para detectar valores atípicos
- A remoção de outliers melhora a qualidade da análise estatística
- Nem todos os outliers devem ser removidos sem análise contextual

## 📊 Conclusão
A análise demonstrou como a presença de outliers impacta diretamente a distribuição de dados reais, utilizando como base a altura de jogadores da NBA.

Após a introdução de valores atípicos, foi possível observar distorções significativas na distribuição dos dados, evidenciadas por histogramas com caudas alongadas.

Com a aplicação do método do Intervalo Interquartil (IQR), foram definidos limites que permitiram identificar e remover os outliers. Após essa etapa, os dados apresentaram uma distribuição mais próxima da normal, com menor dispersão e maior concentração em torno da média.

Conclui-se que o método IQR é eficaz na detecção de outliers e essencial para a limpeza de dados. No entanto, a remoção deve ser feita com cautela, considerando o contexto, já que alguns outliers podem representar informações relevantes.

## ▶️ Como executar
1. Baixe o arquivo `.ipynb`
2. Baixe o arquivo da bases de dados do Kaggle `.csv`
3. Abra no Google Colab ou Jupyter Notebook.
4. Execute todas as células.

## 👨‍💻 Autor
Raphael Lima
