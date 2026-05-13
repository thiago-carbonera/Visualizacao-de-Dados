# Visualização de Dados - Análise de Crimes em Chicago

Análise e visualização interativa dos 15 tipos de crimes mais frequentes em Chicago usando Python, Pandas e Plotly.

## Requisitos

- Python 3.7+
- pandas
- plotly
- kaleido (para exportação de imagens)

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/thiago-carbonera/Visualizacao-de-Dados.git
cd Visualizacao-de-Dados
```

2. Crie um ambiente virtual (recomendado):
```bash
python -m venv venv
source venv/bin/activate 
```

3. Instale as dependências:
```bash
pip install pandas plotly kaleido
```

## Estrutura do Projeto

```
Visualização de Dados/
├── data/
│   └── chicago_crime_sample.csv    # Dataset com amostras de crimes
├── outputs/                         # Gráficos gerados
├── scripts/
│   └── analise_crimes.ipynb        # Notebook de análise
├── .gitignore
└── README.md
```

## Como Usar

1. Abra o notebook:
```bash
jupyter notebook scripts/analise_crimes.ipynb
```

2. Execute todas as células para gerar a visualização

3. O gráfico interativo será exibido e salvo automaticamente em `outputs/top15_crimes.png`

## O que o Script Faz

- **Leitura**: Carrega dados do arquivo CSV
- **Processamento**: Converte datas e conta frequências de crimes
- **Visualização**: Cria gráfico de barras horizontal dos 15 crimes mais frequentes
- **Exportação**: Salva o resultado como imagem PNG

## Saída

Um gráfico interativo mostrando os tipos de crimes mais comuns em Chicago, com:
- Barras horizontais coloridas (escala de vermelhos)
- Contagem de ocorrências
- Ordenação decrescente

## Notas

- O dataset deve estar em `data/chicago_crime_sample.csv`
- As imagens geradas são salvas em `outputs/`
- O notebook pode ser executado diretamente no VS Code com a extensão Jupyter