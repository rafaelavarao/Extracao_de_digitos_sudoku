# Sudoku OCR - Instruções para Execução

Este repositório contém um código para a extração de dígitos de imagens de Sudoku utilizando processamento de imagem e OCR (Reconhecimento Óptico de Caracteres). O dataset inclui seis imagens de Sudoku, onde três delas são exemplos em que o algoritmo funciona perfeitamente e três delas são exemplos em que o algoritmo de extração de dados não funciona corretamente.

## Pré-requisitos
Você precisará ter uma conta no Google e acessar o Google Colab para executar este código.
Será necessario fazer o upload da pasta 'Visão Computacional' no seu drive '/content/drive/MyDrive'. Após isso, dentro da pasta você conseguirá seguir os próximos passos.

## Executando o Código
Execute cada célula no notebook sequencialmente para aplicar o algoritmo às imagens do dataset.

## Observações sobre o Dataset
O dataset contém seis imagens de Sudoku, divididas em dois grupos:

- **Grupo 1 - Imagens que Funcionam Corretamente:**

1. `image10.jpg` - Esta imagem é um exemplo em que o algoritmo funciona perfeitamente.

2. `image47.jpg` - Esta imagem é outro exemplo em que o algoritmo funciona corretamente.

3. `image151.jpg` - Mais um exemplo onde o algoritmo opera com precisão.

- **Grupo 2 - Imagens que não Funcionam Corretamente:**

1. `image84.jpg` - Esta imagem faz parte do grupo em que o algoritmo de extração de dados não funciona corretamente devido à qualidade da imagem.

2. `image93.jpg` - Outro exemplo em que o algoritmo não consegue extrair os dados corretamente.

3. `img147.jpg` - Mais uma imagem problemática em que o algoritmo não opera conforme o esperado devido à qualidade da imagem.

Os resultados após a execução das células do notebook serão diferentes para cada imagem, e você poderá verificar o desempenho do algoritmo para cada caso.


## Resultados
Após a execução das células do notebook, você poderá verificar os resultados para cada imagem no dataset. Os resultados são apresentados na forma de uma matriz que representa o estado do Sudoku.


Link GitHub: https://github.com/rafaelavarao/Extracao_de_digitos_sudoku/tree/main
