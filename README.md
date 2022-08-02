# leyrisvancosta
# 1. Algoritmo de Chan-Vesse

O modelo Chan-Vese para contornos ativos é um método poderoso e flexível que é capaz de segmentar muitos tipos de imagens, incluindo algumas que
seriam bastante difíceis Neste projeto, será apresentado o modelo (há uma extensão para cor (vetor valorizadas) imagens [4], mas não serão consideradas aqui),
e código MATLAB que  segmentar por meio de segmentação "clássica" - ou seja, usando limiar ou gradiente metodos baseados.

Esse algoritmo foi proposto pela primeira vez por Tony Chan e Luminita Vese, em uma publicação intitulada “An Active Contour Model Without Edges”
Esta implementação do algoritmo é um pouco simplificada no sentido de que o fator de área 'nu' descrito no artigo original não é implementado e é 
adequado apenas para imagens em tons de cinza.
