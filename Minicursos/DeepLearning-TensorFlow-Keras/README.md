# Criando Modelos em Deep Learning usando TensorFlow e Keras

### Objetivos

#### Geral
Compreender e construir modelos em Deep Learning aplicado à diferentes domínios usando TensorFlow e Keras 

#### Específicos
* Entender a terminologia e definições básicas do aprendizado de máquina.
* Reconhecer as arquiteturas de redes neurais.
* Compreender o ciclo de treinamento e validação em redes neurais e seus componentes, a saber, funções de ativação, funções de erro (_loss functions_), otimizadores e regularizadores.
* Compreender o fundamento das redes neurais convolucionais (CNN).
* Aplicar redes neurais, tradicionais e convolucionais, para aplicação em classificação.
* Compreender as rotinas de pre-processamento e visualização de dados.

### Domínios de problemas
Temos a priori três super categorias de problemas, a saber:

* **Dados numéricos e categóricos**: a base de dados possui informações acerca de entidades ou fenômenos a partir de uma abstração que os descreve usando números e/ou categorias.

* **Imagens**: a base de dados possui imagens com seu respectivo significado semântico (_target_).
    * **Classificação**: indica se a imagem possui os objetos de interesse.
    * **Localização**: localiza os objetos de interesse na imagem.
    * **Segmentação**: marca exatamente a região (bordas) dos objetos de interesse.

* **Texto**: a base de dados é composta por sentenças textuais, e podem se usadas em:
    * **Classificação**: indicar o sentimento, estilo literário, ou mesmo a língua daquele texto.
    * **Sumarização**: resumir uma sequência de textual indicando suas principais ideias.
    * **Conversação**: apresentar a próxima sentença com o intuito de manter um diálogo.

Estes são os possíveis domínios que podem ser abordados.

### Conteúdo

1. **Aprendizado de Máquina**
    1.1 Definição e Contextualização
    1.2 Supervisionado
    1.3 Não supervisionado
2. **Bases de dados**
    2.1 Tipos de dados
    2.2 Visualização de dados
    2.3 Preparação de dados
3. **Redes Neurais Artificiais**
    3.1 Neurônio - estrutura, função de ativação
    3.2 Arquiteturas (feedfoward, recorrente)
    3.3 Funções de erro (Loss Functions)
    3.4 Otimzadores (SGD, Adam)
    3.5 Regularização (Penalidade e Dropout)
4. **Redes Neurais Convolucionais**
    4.1 Definição e Contextualização
    4.2 Convolução
    4.3 Arquiteturas conhecidas
5. **Aplicações**
    5.1 Benchmarks (MNIST, COCO, CIFAR, ImageNet)
6. **Tecnologias e Ferramentas**
    6.1 Numpy
    6.2 Matplotlib
    6.3 Pandas
    6.4 TensorFlow
    6.5 Keras

### Referências e Links

#### Sites
* [Python](https://www.python.org) - Uma linguagem de programação poderosa e flexível muito usada em Machine Learning.
* [Tensor Flow](https://www.tensorflow.org) - Uma biblioteca para computação numérica usando autograd.
* [Keras](https://keras.io) - Uma API de alto nível para Redes Neurais em geral construída para funcionar em cima do TensorFlow.
* [Numpy](http://www.numpy.org/) - Um pacote fundamental para computação científica em Python
* [Pandas](https://pandas.pydata.org) - Uma biblioteca para manipulação de dados estruturados e análise de dados em Python.
* [Scikit-learn](http://scikit-learn.org) - Uma biblioteca para machine learning em Python
* [Matplotlib](https://matplotlib.org) - Biblioteca para gráficos e visualização de dados

#### Livros
* GOODFELLOW, I; BENGIO, Y; COURVILLE, A; [**Deep Learning Book**](https://www.deeplearningbook.org). The MIT Press, 2017, 775 p.
* HAYKIN, S; [**Neural Networks And Learning Machines**](https://www.amazon.com/Neural-Networks-Learning-Machines-3rd/dp/0131471392/ref=sr_1_1?ie=UTF8&qid=1538743430&sr=8-1&keywords=haykin). 3a. Ed.[S.I.]: Pearson, 2018, 936 p.
* CHOLLET, F; [**Deep Learning With Python**](https://www.amazon.com/Deep-Learning-Python-Francois-Chollet/dp/1617294438/ref=pd_sbs_14_1?_encoding=UTF8&pd_rd_i=1617294438&pd_rd_r=8b567593-c89d-11e8-9fa2-b56c5080678d&pd_rd_w=yewVl&pd_rd_wg=XFzP4&pf_rd_i=desktop-dp-sims&pf_rd_m=ATVPDKIKX0DER&pf_rd_p=53dead45-2b3d-4b73-bafb-fe26a7f14aac&pf_rd_r=D3QTEDZAP7MG9NGBQ1K5&pf_rd_s=desktop-dp-sims&pf_rd_t=40701&psc=1&refRID=D3QTEDZAP7MG9NGBQ1K5). Manning Publications, 2017, 384 p.