# 🔎Rede Neural Convolucional para segmentação do pulmão
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/Jhones257/CNNPULMAO/blob/main/README.md)


Autor: [Jhones Soares](https://github.com/Jhones257)

# 👩‍💻Rede Neural Convolucional
 Uma Rede Neural Convolucional (CNN, do inglês Convolutional Neural Network) é um tipo de rede neural artificial especialmente eficaz para tarefas de processamento de dados que possuindo uma estrutura em grade, como imagens. A arquitetura das CNNs é inspirada na organização do córtex visual animal e é composta por camadas convolucionais, que aplicam filtros para extrair características importantes dos dados, seguidas por camadas de pooling, que reduzem a dimensionalidade dos dados. Podemos aplicar essas redes em aplicações de visão computacional, como classificação de imagens, detecção de objetos e segmentação semântica.

# Vantagens:
 - Capacidade de capturar padrões locais nos dados
 - Redução de complexidade
 - Habilidade de aprender hierarquias de características

# 🖥Implementação da CNN

Este algoritmo funciona basicamente em 3 etapas:
  - 1 Preparação dos dados, padronizando o tamanho das imagens e transformando todas em grayscale.
  - 2 Definição de métricas para avaliação do modelo, neste caso estou utilizando DICE, IoU e F1 Score para analise do desempenho do modelo
  - 3 Construção do modelo, contendo 9 camadas convolucionais utilizando a função de ativação sigmoid

# 👩‍💻Sobre o Projeto
Para este projeto busco aplicar uma variação da arquirtetura de CNN para segmentação do da área do pulmão, oque no futuro pode facilitar diagnósticos médicos como detecção de COVID-19 através da análise de imagens. A variação escolhida foi a U-net, pois após diversos testes, está mostrou ter o melhor desempenho para a tarefa.

Suas principais funcionalidades incluem:
  - ✨Segmentação da área do pulmão. 
  - ✨Vizualização da área segmentada no output da rede.
  - ✨Métricas que validam o grau de precisão da segmentação.

# Exemplo de outputs e resultados obtidos:

O modelo obteve os seguintes resultados em treino e teste:

Treino:
  - Acurácia: 99,02%
  - Dice: 97,46%
  - F1: 42,80%
  - IoU: 99,22%

Teste:
  - Acurácia: 97,83%
  - Dice: 94,98%
  - F1: 44,77%
  - Iou: 98,65%

![output da rede neural](https://github.com/Jhones257/CNNPULMAO/blob/main/OutputRede.png)

![Gráficos dos resultados](https://github.com/Jhones257/CNNPULMAO/blob/main/graficos_rede.png)

