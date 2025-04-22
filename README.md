# Análise de Dados de Vinhos

Este projeto contém scripts para análise de dados de vinhos, utilizando Python e bibliotecas populares de análise de dados.

## Descrição

O projeto inclui scripts para:

- Carregamento e análise de dados de vinhos
- Visualização de dados usando matplotlib
- Geração de histogramas e outras visualizações
- Análises estatísticas e exploração de dados

## Requisitos

Para executar este projeto, você precisará ter instalado:

- Python 3.x
- Poetry (gerenciador de dependências)

## Instalação

1. Clone este repositório:

```bash
git clone [URL_DO_SEU_REPOSITÓRIO]
```

2. Instale as dependências usando Poetry:

```bash
poetry install
```

## Uso

O projeto contém vários scripts de análise:

### Script 1

```bash
poetry run python src/exercicios/script1.py
```

### Script 2

```bash
poetry run python src/exercicios/script2.py
```

Este script:

1. Carrega o conjunto de dados de vinhos
2. Exibe as primeiras linhas do dataframe
3. Gera um histograma da acidez fixa
4. Salva o histograma como 'wine_histogram.png'

### Script 3

```bash
poetry run python src/exercicios/script3.py
```

## Estrutura do Projeto

```
.
├── src/
│   └── exercicios/
│       ├── __init__.py
│       ├── script1.py
│       ├── script2.py
│       └── script3.py
├── .gitignore
└── README.md
```

## Contribuição

Contribuições são bem-vindas! Por favor, sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
