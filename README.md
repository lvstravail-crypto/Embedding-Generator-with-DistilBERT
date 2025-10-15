
# Gerador de Embeddings com DistilBERT e Cálculo de Similaridade

## Descrição

Este projeto utiliza o modelo **DistilBERT** da Hugging Face para gerar embeddings de texto e calcular a similaridade de cosseno entre um texto de busca fornecido pelo usuário e um conjunto de textos armazenados em um arquivo CSV.

## Funcionalidade

1. **Geração de Embeddings**: Cada texto do arquivo CSV é transformado em um vetor (embedding) utilizando o modelo **DistilBERT**.
2. **Cálculo de Similaridade**: O código calcula a similaridade entre um texto de busca fornecido pelo usuário e os textos armazenados no CSV.
3. **Exibição de Resultados**: Os textos mais similares ao texto de busca são exibidos de forma ordenada no Google Colab.

## Requisitos

- Python 3.x
- Google Colab (para visualização simples)
- Bibliotecas:
  - `transformers`
  - `torch`
  - `pandas`
  - `numpy`

## Instruções de Uso

### 1. Instalar as bibliotecas necessárias:
Execute os seguintes comandos no seu notebook Google Colab:

```python
!pip install transformers
!pip install torch
!pip install pandas
