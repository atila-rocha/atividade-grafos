# Atividade 1 - Grafos

## Objetivo

O objetivo desse projeto é avaliar se o dataset de relações das páginas do wikipedia com a temática de `crocodilo` é escala livre ou não

### Objetivos secundários

- Histograma do dataset
- Distribuição de graus na escala linear e log-log
- identificação de outliers

## Sobre o dataset
O dataset utilizado neste trabalho ´e o MUSAE Crocodile, disponibilizado pelo Stanford
Network Analysis Project (SNAP). Essa rede representa p´aginas da Wikipedia relacionadas entre si por hyperlinks.
Cada v´ertice corresponde a uma p´agina da Wikipedia e cada aresta representa um
hyperlink entre duas p´aginas.

## Pré-requisitos

É essencial que você tenha as seguintes linguagens/feramentas na sua máquina:

- Python
- Jupyter Notebook
- R

## Como rodar

1. Com o Jupyter Notebook instalado, verifique se o seu kernel tem disponível a linguagem R. Caso contrário, instale.
2. Abra o arquivo `Atividade_01_Grafos.ipynb` e em seguida clique em "Reiniciar sessão e executar tudo".
3. Os outputs de cada célula aparecerá embaixo da respectiva célula

## Dúvidas Frequentes
1. Como instalo o R no kernel do jupyter notebook?
1. 1. Para instalar, o projeto seguiu as instruções do seguinte link: `https://www.datacamp.com/pt/blog/jupyter-and-r-markdown-notebooks-with-r`
2. Esse arquivo de entrada veio daonde?
2. 1. O arquivo veio de uma filtragem a qual foi feita em Java utilizando como base o algoritmo `algs4`. As únicas alterações realizadas no algoritmo foi a remoção de arestas duplicadas a qual aumentava o número de vértices do dataset tratado e dificultava na análise dos gráficos. Também foi alterado o formato de entrada para aceitar arquivos csv mas a estrutura de dados de entrada foi mantida. Link do repostório: `https://github.com/ovictorvale/Atividade01Grafos`
