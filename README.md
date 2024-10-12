# Projeto Python IA: Inteligência Artificial e Previsões

## Case: Score de Crédito dos Clientes

### Descrição
Este projeto foi desenvolvido para um banco que precisava de uma solução automatizada para avaliar o score de crédito dos clientes. Utilizando algoritmos de Machine Learning, o objetivo foi criar um modelo capaz de prever o score de crédito dos clientes com base em suas informações financeiras e comportamentais. As previsões são classificadas em três categorias: **Ruim**, **Ok**, e **Bom**.

### Objetivo
O objetivo principal é analisar as informações dos clientes do banco e desenvolver um modelo preditivo para classificar automaticamente o score de crédito de novos clientes. Isso auxilia o banco a tomar decisões mais rápidas e assertivas na concessão de crédito, reduzindo os riscos de inadimplência.

### Tecnologias Utilizadas
- **Python**: Linguagem principal para desenvolvimento do projeto.
- **Pandas**: Manipulação e análise de dados.
- **Scikit-Learn**: Criação e avaliação de modelos de Machine Learning.
- **Jupyter Notebook**: Documentação e execução dos experimentos.

### Estrutura do Projeto
- `data/`: Contém o dataset dos clientes e novos clientes.
- `notebooks/`: Notebooks Jupyter com a análise exploratória, pré-processamento dos dados, e desenvolvimento dos modelos.
- `models/`: Modelos treinados para serem utilizados nas previsões.
- `README.md`: Descrição do projeto.
- `requirements.txt`: Lista de bibliotecas necessárias para executar o projeto.

### Metodologia
1. **Coleta de Dados**: Importação do dataset dos clientes do banco, incluindo informações como histórico de crédito, renda, profissão, e comportamento de pagamento.
2. **Análise Exploratória dos Dados (EDA)**: Identificação de padrões nos dados e limpeza de informações inconsistentes ou faltantes.
3. **Pré-processamento**: Transformação de variáveis categóricas usando `LabelEncoder`, normalização e padronização dos dados.
4. **Modelagem**:
   - Modelos testados: Regressão Logística, Naive Bayes, e Árvore de Decisão.
   - Escolha do melhor modelo com base em métricas de avaliação (acurácia, precisão, recall e F1-score).
5. **Validação**: Avaliação do modelo usando um conjunto de teste para garantir que as previsões sejam consistentes e precisas.
6. **Previsão de Novos Clientes**: Utilização do modelo treinado para prever o score de crédito de novos clientes a partir de suas informações.

### Resultados
- O modelo de Árvore de Decisão obteve uma precisão de **X%** na classificação dos scores de crédito.
- O sistema automatizado ajudou a reduzir o tempo de análise manual, permitindo decisões de crédito mais rápidas.
- A análise de crédito se tornou mais precisa, ajudando a minimizar riscos para o banco.

### Como Utilizar
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/ale4souza/Previsoes-usando-IA.git
 
