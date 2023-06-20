# Atividade-Python-Github
**Universidade do Vale do Itajaí**                                                
* Curso: Ciência da Computação Disciplina: Introdução a Ciência da Computação          
* Professor: Felipe Viel Avaliação – Linguagem Python            
* Alunos: Lucas Vieira da Silva (8065594), Rhichyllie Baptista Stefen (6614620)
                  
Este código é um exemplo de treinamento de uma rede neural convolucional simples
(CNN) para classificar imagens CIFAR. Com a API Keras Sequential, você pode construir e
treinar seu modelo com apenas algumas linhas de código.
Redes neurais convolucionais são técnicas de aprendizado profundo comumente usadas
em tarefas de classificação de imagens. O conjunto de dados CIFAR consiste em imagens
de 32 x 32 pixels divididas em 10 classes diferentes.
O código começará a importar as bibliotecas necessárias, como conjuntos de dados
Keras e CIFAR. Um modelo sequencial, que é uma pilha linear de camadas de rede neural,
é então construído.
Este modelo consiste em uma camada convolucional que extrai características da
imagem e uma camada de pooling que reduz a dimensionalidade dos dados. Depois, há
uma camada densa responsável pela classificação da imagem.
Depois de criar o modelo, o treinamento é feito usando o conjunto de dados CIFAR. O
treinamento é feito em lotes, cada lote contendo um conjunto de imagens e suas
respectivas classes. Durante o treinamento, o modelo é ajustado para minimizar a função
de perda, que é uma medida da diferença entre a aula prevista e a aula real. O processo de
treinamento é repetido várias vezes até que o modelo atinja uma precisão satisfatória.
O modelo é então avaliado em relação a um conjunto de dados de teste que não foi
usado durante o treinamento. A precisão do modelo é calculada e exibida na tela.
Por curiosidade e no contexto do tema, as redes neurais descrevem o comportamento
individual. Os algoritmos genéticos tentam otimizar os parâmetros da rede. A IA genética é
baseada na teoria da evolução/seleção natural e evolui ao longo do tempo com
características dominantes que a distinguem de outras gerações. Portanto, precisamos
treinar a rede neural antes de aplicá-la à análise de fotos. Sobre este tema vale a pena ler
os seguintes artigos: Survival Shooter NPC Algoritmo Genético, NEAT Snake:Abordagens
de adaptação evolutiva e de rede neural.
Em resumo, este código é um exemplo simples de como usar a API Keras Sequential
para criar e treinar uma rede neural convolucional para classificar imagens CIFAR. Obtenha
resultados precisos e eficientes com apenas algumas linhas de código.
