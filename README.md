# Analise-Multi-Variada

Projeto de Analise Multivariada - O objetivo é prever qual grupo de anfibios estao próximos aos reservatórios de água com base em recursos obtidos de sistemas SIG e imagens de satélite.

Meta principal - Explicar com base nos dados quais especies de anfibios se adaptam em quais lugares e em quais circunstancias.

1 - Numero de reservatorio de agua impacta na criacao de anfibios?

2 - Tipo de reservatorio de agua pode favorecer a reproducao de anfibios?

3 - Os arredores dos reservatorios podem ser ambientes adequados para o habitat dos anfibios?

4 - Lugares com a pesca permitida podem favorecer ou nao a presenca de anfibios?

5 - A distancia entre o reservatorio de agua e as estrada impactam na sobrevida dos anfibios?

6 - Um mapa geral de como esta dividida a populacao e as caracteristicas dos anfibios.

7 - Por fim criar um modelo de classificaçao(metricas e acuracia) para prever a existencia de quais especies .

https://archive.ics.uci.edu/ml/datasets/Amphibians

==========================================================================================================================

Um mapa geral sobre como esta dividida a populacao de Anfibios e as caracteristicas.

Com base no Conjunto de Dados coletados em 2 estradas da Polonia sobre Anfibios, fiz uma Analise como as especies se

comportam e em quais lugares se adaptam.

1 - Sapo Verde foi encontrado 108 vezes.

Em sua maioria em lugares onde existem somente um reservatorio de agua do tipo Natural.

Os Arredores dos reservatorios de agua tambem foram observados sendo que Edificios Densos estão entre os lugares preferido do

Sapo Verde.

Em locais com pesca intensa quase não ha presença do Sapo Verde ao contrario da pesca ocasional.

E por ultimo a Distancia do reservatorio de agua de 50m a 500m da estrada estão em sua maioria.

2 - Rã Marrom foi encontrada 148 vezes.

Em sua maioria em lugares onde existem somente um reservatorio de agua do tipo Natural.

Os Arredores dos reservatorios de agua tambem foram observados sendo que Edificios Densos, Estradas/Ruas estão entre os lugares

preferidos da Rã Marrom.

Em locais com pesca intensa quase não ha presença da Rã Marrom ao contrario da pesca ocasional.

E por ultimo a Distancia do reservatorio de agua de 50m a 500m da estrada estão em sua maioria.

3 - Sapo Comum foi encontrado 124 vezes.

Em sua maioria em lugares onde existem somente um reservatorio de agua do tipo Natural.

Os Arredores dos reservatorios de agua tambem foram observados sendo que Edificios Densos, Estradas/Ruas estão entre os lugares

preferidos do Sapo Comum.

Em locais com pesca intensa quase não ha presença do Sapo Comum ao contrario da pesca ocasional.

E por ultimo a Distancia do reservatorio de agua de 50m a 500m da estrada estão em sua maioria.

4 Sapo de Fogo foi encontrada 58 vezes.

Em sua maioria em lugares onde existem um ou mais reservatorios de agua do tipo Natural.

Os Arredores dos reservatorios de agua tambem foram observados sendo que Edificios Densos, Estradas/Ruas , terrenos/baldios

estão entre os lugares preferidos do Sapo de Fogo.

Em locais com pesca intensa quase não ha presença do Sapo de Fogo ao contrario da pesca ocasional.

E por ultimo a Distancia do reservatorio de agua de 50m a 500m da estrada estão em sua maioria.

5 Sapo de Arvore foi encontrada 71 vezes.

Em sua maioria em lugares onde existem somente um reservatorio de agua do tipo Natural.

Os Arredores dos reservatorios de agua tambem foram observados sendo que Edificios Densos, Estradas/Ruas , terrenos/baldios

estão entre os lugares preferidos do Sapo de Arvore.

Em locais com pesca intensa quase não ha presença da Sapo de Arvore ao contrario da pesca ocasional.

E por ultimo a Distancia do reservatorio de agua de 50m a 500m da estrada estão em sua maioria.

6 Salamandra Comum foi encontrada 58 vezes.

Em sua maioria em lugares onde existem somente um reservatorio de agua do tipo Natural.

Os Arredores dos reservatorios de agua tambem foram observados sendo que Edificios Densos, Estradas/Ruas , terrenos/baldios

estão entre os lugares preferidos da Salamandra Comum.

Em locais com pesca intensa quase não ha presença da Salamandra Comum ao contrario da pesca ocasional.

E por ultimo a Distancia do reservatorio de agua de 50m a 500m da estrada estão em sua maioria.

7 Salamandra de Crista foi encontrada 21 vezes.

Em sua maioria em lugares onde existem um ou mais reservatorio de agua do tipo Natural.

Os Arredores dos reservatorios de agua tambem foram observados sendo que Edificios Densos , terrenos/baldios estão entre os

lugares preferidos da Salamandra de Crista.

Em locais com pesca intensa quase não ha presença da Sapo de Arvore ao contrario da pesca ocasional.

E por ultimo a Distancia do reservatorio de agua de 50m a 500m da estrada estão em sua maioria.

===========================================================================================================================

Analise Preditiva

Contrução de varios modelos usando diversos Algoritmos de Classificação.

Avaliação do modelo vou usar função cross_val_score , medida de desempenho relatada pela validação cruzada k -fold é, então,

a média e o desvio padrão dos valores calculados.



