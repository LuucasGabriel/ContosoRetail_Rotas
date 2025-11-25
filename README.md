# Análise de Otimização de Rotas - Contoso Retail (Planta Sorocaba)

## Motivação

Este projeto foi iniciado a partir de um insight obtido através da análise de dados da `ContosoRetailDW` no Power BI. A análise revelou um número significativo de entregas atrasadas originadas da planta de Sorocaba do ano de 2022, especialmente na categoria de produtos `CA06`, que acumula mais de 13.000 entregas em atraso.

## Objetivo

Com base nesse cenário, o objetivo deste projeto é realizar uma análise de rotas para identificar possíveis causas para os atrasos e propor soluções. A hipótese é que os atrasos podem ser causados por fatores como:

*   Longas distâncias para algumas cidades de destino.
*   Congestionamentos e tráfego intenso.
*   Ocorrência de acidentes nas rotas atuais.

A ferramenta desenvolvida neste projeto busca encontrar uma rota alternativa e mais eficiente para as entregas, visualizando o trajeto proposto em um mapa interativo.

## Funcionamento

O projeto utiliza um notebook Jupyter (`calculo de rotas.ipynb`) para:
1.  Ler os dados de clientes e da planta de Sorocaba.
2.  Utilizar a API do OpenRouteService para calcular a rota otimizada entre a planta e os destinos dos clientes.
3.  Gerar um mapa interativo (`mapa.html`) que exibe a rota sugerida, permitindo uma visualização clara do percurso.

## Arquivos do Projeto

*   `calculo de rotas.ipynb`: Notebook com toda a lógica para o cálculo e visualização das rotas.
*   `Dados/`: Pasta contendo os datasets `custumers.csv` e `plant.csv`.
*   `mapa.html`: Arquivo HTML com o mapa interativo da rota gerada.
*   `requirements.txt`: Lista de dependências Python para executar o projeto.
