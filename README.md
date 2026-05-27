# Visualização de Dados - Análise de Crimes em Chicago

Análise e visualização interativa das seguintes perguntas de pesquisa:
- Quais são os tipos de crimes mais frequentes?
- Como a quantidade de crimes varia ao longo do tempo (anos, meses e horários)?
- Quais regiões apresentam maior incidência de crimes?
- Existe relação entre o tipo de crime e a ocorrência de prisão?


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

2. Execute todas as células para gerar as visualizações

3. Os gráficos interativos serão exibidos e salvos automaticamente em `outputs/`

## O que o Script Faz

- **Leitura**: Carrega dados do arquivo CSV
- **Processamento**: Efetua pré processamentos
- **Visualização**: Gera as visualizações
- **Exportação**: Salva os resultado html em `outputs/`

## Saída

Gera quatro visualizações interativas: 
- Visualização de barras horizontais Animado (Bar Chart Race)
- Visualização de mapa de calor espacial (Geographic Heatmap) 
- Visualização de diagrama de sankey (Sankey Diagram)
- Visualização de uma matriz de densidade temporal (Heatmap Bidimensional)

## Notas

- O dataset deve estar em `data/chicago_crime_sample.csv`
- As imagens geradas são salvas em `outputs/`
- O notebook pode ser executado diretamente no VS Code com a extensão Jupyter