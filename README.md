# Predicting Smart Grid Stability with Different Algorithms

## Introdução

Este projeto tem como objetivo criar modelos de aprendizado de máquina para prever a estabilidade da rede elétrica em sistemas de grade inteligente. O problema de classificação binária consiste em determinar se a grade é estável ou instável, com base em um conjunto de variáveis preditivas relacionadas ao sistema.

## Descrição do Problema

As redes elétricas inteligentes (smart grids) são sistemas complexos com múltiplos participantes interconectados, incluindo fornecedores de energia e consumidores. A estabilidade da rede elétrica é crucial para garantir o fornecimento contínuo e confiável de energia elétrica.

## Dataset

O dataset utilizado neste projeto é sintético e contém 60.000 observações geradas a partir de simulações de estabilidade de uma rede em estrela de 4 nós. O conjunto de dados possui 12 variáveis preditivas e a variável dependente "stabf", que indica se a rede é estável ("stable") ou instável ("unstable").

## Modelos de Aprendizado de Máquina

Neste projeto, utilizamos diferentes algoritmos de aprendizado de máquina para prever a estabilidade da rede elétrica. Os algoritmos explorados são:

- Logistic Regression
- XGBoost
- Support Vector Machine (SVM)
- Rede Neural (utilizando a biblioteca Keras com TensorFlow)

## Requisitos de Instalação

Para executar o projeto, é necessário ter instalado as seguintes bibliotecas:

- NumPy
- Pandas
- Seaborn
- Scikit-learn
- Matplotlib
- Keras com TensorFlow

Para instalar as dependências, você pode usar o gerenciador de pacotes pip:

```
pip install numpy pandas seaborn scikit-learn matplotlib keras tensorflow
```

## Executando o Projeto

Para executar o projeto, basta executar o arquivo principal do projeto. Certifique-se de que o dataset "smart_grid_stability_augmented.csv" esteja no mesmo diretório.

```
python main.py
```

## Resultados

Os modelos treinados são avaliados usando métricas de desempenho, como acurácia, precisão, recall e F1-score. Os resultados são armazenados em uma tabela para comparação.

## Contribuições

Contribuições são bem-vindas! Se você quiser contribuir com melhorias, correções de bugs ou novos recursos, fique à vontade para enviar um pull request.

## Licença

Este projeto é licenciado sob a licença MIT - veja o arquivo LICENSE.md para detalhes.
