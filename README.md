

[![DOI](https://zenodo.org/badge/412814864.svg)](https://zenodo.org/badge/latestdoi/412814864)



# Polígonos de vias da Cidade de São Paulo

Repostitório destinado ao desenvolvimento e publicação do método para geração do polígono de vias para a Cidade de São Paulo, assim como seus resultados

## Motivação

Esses métodos e resultados publicados aqui fazem parte da pesquisa AndaSampa: A rede de rotas caminháveis (e cadeiráveis) na cidade de São Paulo, que tem como objetivo estudar a cidade à partir da perspectiva da pedestre.
Portanto, a motivação de manter esse repositório vem do fato de que as vias são elementos adjacentes ou ainda barreiras de transposição para rotas caminháveis.

As vias de circulação normalmente são representadas por uma redes de linhas que se conectam por pontos e representam os logradouros e seus atributos por segmento de linha.

No entanto algumas vezes pode ser necessário a utilização de um polígono ou de polígonos que representem segmentos de via. Podem ser usados para mensurar área dos leitos carroçáveis, operações espaciais ou até mesmo informações de sua topologia como a largura da via.

## Objetivo

O principal objetivo desse repositório portanto foi de desenvolver um método para calcular e eleborar os polígonos de via da cidade de São Paulo, assim como publicar os resultados obtidos para qualquer um que necessite utiliza-los.

## Materiais e Métodos

Basicamente utilizam-se dados abertos disponíveis no GeoSampa, como quadras viárias, áreas de rios e represas, limites administrativos, eixos de logradouros e quadras fiscais para processar os polígonos de vias utilizando Python, GeoPandas e Shapely.

## Resultados

Os resultados, separados por distrito, estão disponibilizados na pasta resultados desse repositório.
