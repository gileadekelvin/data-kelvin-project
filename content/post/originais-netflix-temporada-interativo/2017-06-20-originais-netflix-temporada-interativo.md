+++
title = "Uma visão interativa sobre as Séries Originais Netflix"
slug = "series-netflix-interativo"
description = "Uma visão interativa sobre a avaliação das Séries Originais Netflix ao longo de suas temporadas."
tags = [
    "Análise de dados",
    "R",
    "Data science",
    "htmlwidgets"
]
date = "2017-06-20"
categories = [
    "R",
]
nomenu = "main"
image= "defimg/series-netflix-sense8.jpg"
comments = "TRUE"
+++

**Análise realizada em 20/06/2017 para a disciplina de Análise de Dados 1 (Curso de Computação - UFCG)**

## Como a avaliação das séries se comporta ao longo das temporadas?

Nós selecionamos seis séries Originais Netflix e com base no ratings (notas) atribuídas aos episódios de cada série traçamos um gráfico de linha interativa que mostra como as notas dos episódios se comportam à medida que a série e suas temporadas vão avançando. A fonte dos dados é o IMDB, um banco de dados online com informação sobre música, filmes, **séries**, cinema, jogos, programas e comerciais de TV, atualmente percente a Amazon.

<iframe width="100%" height="700px" src="series_temporada.html" frameborder="0" allowfullscreen></iframe>

A visualização nos mostra como algumas séries como 13 Reasons Why, Sense8 e Stranger Things parecem ter uma tendência maior de crescimento nas avaliações conforme a série avança. Apesar dos picos, os episódios em geral, melhoram de avaliação conforme as temporadas avançam e a série também.

É possível perceber como dentro de uma série as temporadas são distintas com relação ao formato das linhas na evolução das notas. Narcos, por exemplo, tem uma segunda temporada com maior amplitude na variação dos episódios do que na primeira temporada.

House of Cards parece ter variações maiores entre episódios que são adjuntos (vizinhos), ou seja, existe uma maior amplitude na linha traçada quando comparada a outras séries como Narcos. Entenda amplitude como a distância entre as melhores avaliações e as piores. Quanto maior a amplitude e quanto mais frequente é a presença de picos entre episódios vizinhos maior é variação, segundo o critério adotado para esta análise.

Outras informações podem ser retiradas ao interagir com a visualização como o nome do episódio, sua nota e o número de votos que ele recebeu no IMDB.

#### Considerações

Através da visualização é possível explorar sobre os episódios das séries originais Netflix selecionadas e materializar como é a evolução da avaliação dos episódios conforme a temporada vai avançando. É possível observar tendências de subidas em algumas séries e maior variação (picos, altos e baixos em episódios vizinhos, maior amplitude) em outras.

Espero que você possa ter tido outros insights legais sobre a análise e até a próxima!!!



