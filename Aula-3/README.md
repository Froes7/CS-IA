# Aula 3 - Fundamentos de Machine Learning

## Conteúdo

- Introdução ao Machine Learning.
- Tipos de aprendizado (supervisionado, não supervisionado, por reforço e semi-supervisionado).
- Conhecendo os datasets Iris, California Housing e Titanic.
- Seleção de features.
- Escalonamento dos dados.
- Pipeline e ColumnTransformer.

## Bibliotecas

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

from sklearn.datasets import load_iris
from sklearn.preprocessing import MinMaxScaler, StandardScaler
```

## Observações

- É importante conhecer os dados antes de treinar um modelo.
- Selecionar boas features pode melhorar o desempenho.
- Alguns algoritmos precisam que os dados sejam normalizados ou padronizados.
- O Pipeline ajuda a organizar o pré-processamento e o treinamento do modelo.
