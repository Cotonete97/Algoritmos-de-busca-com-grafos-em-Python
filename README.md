# Algoritmos de busca com grafos em Python

Projeto em Python para cálculo e visualização de rotas em mapa real, utilizando algoritmos de busca em grafos como **A\*** e **Dijkstra**.

## Objetivo

O projeto simula navegação em mapa real na região do Cruzeiro-DF, considerando não apenas distância, mas também fatores que impactam o custo de deslocamento, como:

- velocidade da via
- semáforos
- lombadas
- características do trajeto

## Funcionalidades

- cálculo de rotas com **A\***
- comparação de rotas com **Dijkstra**
- visualização do caminho no mapa
- edição de características das vias diretamente no sistema
- salvamento das edições em arquivo JSON

## Tecnologias utilizadas

- Python
- OSMnx
- NetworkX
- Matplotlib
- JSON

## Arquivos principais

- `Aestrela.py` → arquivo principal do projeto
- `edicoes_mapa.json` → armazena as edições feitas no mapa

## Como executar

1. Clone este repositório
2. Instale as dependências e execute "Aestrela.py":

```bash
pip install -r requirements.txt
