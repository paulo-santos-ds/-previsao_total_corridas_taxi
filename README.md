# 🚗 Previsao total corridas Taxi


## 📋 Sobre o Projeto

Foi desenvolvido um modelo preditivo específico para atrair mais motoristas durante o horário de pico. Prever a quantidade de pedidos de táxi para a próxima hora.

## 🛠️ Tecnologias Utilizadas

### Principais Ferramentas
- **Python** - Linguagem base para desenvolvimento
- **Pandas & NumPy** - Manipulação e análise de dados
- **Scikit-learn** - Construção de modelos de machine learning
- **Matplotlib & Seaborn** - Visualização de dados
- **statsmodels** - Análise de séries temporais

### Requisitos
```
pandas>=1.2.0
numpy>=1.19.0
scikit-learn>=0.24.0
matplotlib>=3.3.0
seaborn>=0.11.0
statsmodels>=0.12.0
```

## 📊 Estrutura dos Dados

### Dataset
O conjunto de dados contém as seguintes colunas:
- `datetime`: Data e hora do pedido
- `num_orders`: Número de pedidos por hora

## 🔍 Metodologia

### 1. Análise Exploratória de Dados (EDA)
- Importação e configuração das bibliotecas
- Carregamento e visualização inicial dos dados
- Análise estatística descritiva

### 2. Análise Temporal
- Decomposição da série temporal
  - Tendência
  - Sazonalidade
  - Resíduos
- Análise de média móvel
- Identificação de padrões temporais

### 3. Preparação dos Dados
- Divisão em conjuntos de treino e teste
- Feature engineering
- Normalização dos dados
- Tratamento de dados faltantes

### 4. Modelagem
- Implementação e comparação de modelos:
  - Regressão Linear
  - Random Forest
- Otimização de hiperparâmetros
- Avaliação de métricas de performance

## 📈 Principais Aprendizados

1. **Análise de Dados**
   - Extração de insights de grandes volumes de dados
   - Identificação de padrões e tendências

2. **Machine Learning**
   - Preparação de dados para modelagem
   - Seleção e otimização de modelos
   - Avaliação de performance

3. **Desenvolvimento**
   - Construção de funções modulares
   - Documentação efetiva
   - Versionamento de código

4. **Negócio**
   - Aplicação de regras de negócio
   - Tomada de decisão baseada em dados
   - Interpretação de resultados

## 🚀 Como Usar

1. Clone o repositório
```bash
 git clone https://github.com/paulo-santos-ds/previsao_total_corridas_taxi
```

2. Instale as dependências
```bash
pip install -r requirements.txt
```

3. Execute o notebook principal
```bash
Modelo_Preditivo_Corrida_Taxi.ipynb
```


