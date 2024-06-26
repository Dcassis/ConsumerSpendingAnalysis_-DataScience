# Trabalho Prático TPD Bootcamp

Este repositório contém o trabalho prático desenvolvido durante o Bootcamp de Data Science, focado na análise de dados de consumidores do setor de atacado. Utilizamos técnicas de manipulação e visualização de dados com as bibliotecas Python `pandas`, `numpy`, `seaborn` e `matplotlib`.

## Descrição do Projeto

O projeto envolve a análise de um conjunto de dados contendo informações sobre os gastos anuais de consumidores com diferentes categorias de produtos. As etapas do projeto incluem:

1. **Importação e Visualização dos Dados**:
    - Carregamento dos dados a partir de um arquivo CSV.
    - Visualização das primeiras linhas do dataset para entender sua estrutura.

2. **Exploração e Limpeza dos Dados**:
    - Verificação do formato dos dados e contagem de valores nulos.
    - Análise descritiva das colunas para identificar estatísticas importantes como média, mediana, valores máximos e mínimos.

3. **Análise de Outliers**:
    - Identificação de valores anômalos para cada uma das categorias de produtos.

## Bibliotecas Utilizadas

```python
import numpy as np  # Trabalhar com vetores
import pandas as pd  # Manipulação de dataframes
import seaborn as sns  # Criação de gráficos mais "bonitos"
import matplotlib.pyplot as plt  # Criação de gráficos estilo Matlab
```

## Dados

O dataset utilizado contém as seguintes colunas:

1. **FRESH**: Total anual gasto em produtos frescos.
2. **MILK**: Total anual gasto em produtos derivados do leite.
3. **GROCERY**: Total anual gasto em produtos de supermercado.
4. **FROZEN**: Total anual gasto em produtos congelados.
5. **DETERGENTS_PAPER**: Total anual gasto em produtos de limpeza.
6. **DELICATESSEN**: Total anual gasto em produtos de delicatessen.
7. **CHANNEL**: Tipo do canal de compra do consumidor (1 - Horeca(hotel/restaurante/cafés), 2 - Varejo).
8. **REGION**: Região do consumidor.

## Análise

A análise realizada no projeto aborda questões como:

- Quantidade de colunas e linhas no dataset.
- Quantidade de valores nulos presentes.
- Descrição estatística dos dados.
- Identificação de outliers nos dados.

## Como Usar

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. Navegue até o diretório do projeto:
   ```sh
   cd seu-repositorio
   ```

3. Instale as dependências necessárias:
   ```sh
   pip install -r requirements.txt
   ```

4. Execute o Jupyter Notebook:
   ```sh
   jupyter notebook trabalho_pratico_TPD_bootcamp.ipynb
   ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

