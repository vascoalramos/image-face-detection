## Papers

Podiamos melhorar em relação a este [Paper 1](https://ieeexplore.ieee.org/abstract/document/1619082) porque eles gostavam de no futuro fazer comparação com NN, ou seja, podiamos fazer uma NN e uma SVM.

Este [Paper 2](https://ieeexplore.ieee.org/abstract/document/7943228) compara 4 algorimtos de deteção de caras em imagens incluindo NN e SVM. Refere o Viola-Jones e o Snow Classifier como sendo os dois melhores, mas como não analisamos na aula secalhar e melhor nao usarmos.

Este [Paper 3](https://ieeexplore.ieee.org/abstract/document/609310) aplica a SVM a face detection e tem bons resultados (cerca de 97% de accuracy) e usa um Kernel polinomial de 2º grau com um C=200. Refere um parte muito interessante de pre processamento das imagens que podemos aplicar (Masking->Illumination gradient correction-> Histogram equalization)

Outra coisa que reparei na análise destes 3 papers é que as SVM têm uma performance muito melhor que os outros algoritmos, mas a accuracy é menor relativamente as NN.

Este [Paper 4](https://ieeexplore.ieee.org/document/8858529) aplica data augmentation a imagens para o estudar o reconhecimento de expressões faciais. Conseguimos constatar que data augmentation melhorou bastante os resultados finais e normalmente consegue-se bons resultados quando conjugada com NN. Neste caso os autore usaram a [libraria Keras](https://machinelearningmastery.com/how-to-configure-image-data-augmentation-when-training-deep-learning-neural-networks/) para realizar a data augmentation e também poderiamos usar no nosso projeto. 

A estrutura deste paper é muito boa, apresentando related work e descrevendo de forma correta a arquitetura da NN por isso podiamo-nos basear nesta estrutura para construir o nosso paper.
