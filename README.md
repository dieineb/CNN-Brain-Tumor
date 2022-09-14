# CNN-Brain-Tumor
Rede Neural Convolucional para Classificação de  Imagens de Ressonância Magnética com  Presença de Tumor Cerebral
Dieine Estela Bernieri Schiavon
Universidade Federal de Ciências da Saúde de Porto Alegre
Porto Alegre, Brasil
dieineb@ufcspa.edu.br
Informática Biomédica - UFCSPA
Diagnóstico por Imagem (RAD0010)

Resumo— Um tumor cerebral ocorre quando há um crescimento anormal de células em alguma estrutura do cérebro. O tumor pode apresentar um comportamento benigno, 
sendo menos agressivo e de crescimento lento, ou um comportamento maligno, crescendo mais rapidamente. Ambos podem levar ao prejuízo da função normal do cérebro,
seja pela doença local ou pela compressão de estruturas saudáveis do cérebro, no qual muitas vezes os sintomas iniciais não são percebidos. A classificação do 
tumor cerebral desempenha um papel importante no auxílio ao diagnóstico. O presente trabalho consistiu na construção, desenvolvimento e treinamento de uma rede 
neural convolucional, com base na arquitetura LeNet5,para classificação de um conjunto de imagens de ressonância magnética contendo tumor cerebral. Para tanto, 
as imagens de um dataset de referência Br35H foram utilizadas para treinamento e validação do modelo. O método proposto atingiu acurácia de 98,83% para a base 
de validação e 99,96% para a base de treino, atingindo uma precisão de 98,85% e sensibilidade de 99,65%. Comparando os resultados deste estudo com abordagens 
similares na literatura, observou-se que as métricas encontradas no presente trabalho apresentaramvalores iguais ou melhores aos valores referidos nos estudos publicados. 

Abstract— Brain tumor occurs when there is an abnormal growth of cells in some of the brain’s structure. It can show a 
benign behavior, being less aggressive and slow growing, or a malignant behavior, growing faster. Both can lead to impairment 
of normal brain function, either by local disease or by compression of healthy brain structures, whose initial symptoms are often not 
noticed. The classification of a brain tumor plays an important role in aiding diagnosis. The present work consisted in the 
construction, development, and training of a convolutional neural network, based on the LeNet5 architecture, to classify a set of 
magnetic resonance images containing a brain tumor. For this purpose, images from a Br35H reference dataset were used for 
training and validating the model. The proposed method reached an accuracy of 98.83% for the validation base and 99.96% for the 
training base, reaching a precision of 98.85% and a sensitivity of 99.65%. Comparing the results of this study with similar 
approaches in the literature, it was observed that the metrics found in the present work presented values equal or better than the
values reported in published studies.

Dataset: Hamada, A. Br35H Brain Tumor Detection 2020. Dataset disponível  online: www.kaggle.com/ahmedhamada0/brain-tumor-detection
Para o propósito, foi utilizado o dataset Br35H Brain Tumor Detection, disponível na base de dados Kaggle. O 
dataset conta com 3000 imagens de ressonância magnética com e sem presença de tumor cerebral. A base de dados é 
balanceada, com classificação binária, dividida em 1500 imagens com presença de tumor cerebral e 1500 imagens 
normais. A base não possui um padrão de resolução para as imagens, estão presentes imagens com resoluções de 175 x
167 pixels até 1275 x 1427 pixels. As categorias de interpretação disponíveis são: sem tumor cerebral (no) 
e com presença de tumor cerebral (yes).

