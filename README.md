FIAP - Faculdade de Informática e Administração Paulista


Atividade 04 - CardioIA: Classificação de Imagens Médicas com Visão Computacional
Integrantes
•	João José Domingues Silva
•	William Xavier
•	Murilo Santana
•	William Ferreira
Professores
Tutor(a)
•	Caique Nonato da Silva Bezerra
Coordenador(a)
•	André Godoi
________________________________________
Descrição
Nesta fase do projeto CardioIA foi desenvolvido um protótipo de Visão Computacional para classificação de imagens médicas.
A solução utiliza Redes Neurais Convolucionais (CNNs) para analisar radiografias de tórax e identificar padrões associados à pneumonia. Foram implementadas duas abordagens distintas:
•	CNN desenvolvida do zero;
•	Transfer Learning utilizando MobileNetV2.
O objetivo é demonstrar como técnicas de Inteligência Artificial podem auxiliar na análise de exames médicos e apoiar processos de tomada de decisão.
________________________________________
Dataset Utilizado
Dataset: Chest X-Ray Images (Pneumonia)
Origem: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
Características:
•	Imagens de radiografia de tórax;
•	Duas classes:
  o	NORMAL
  o	PNEUMONIA
•	Conjuntos separados em treino, validação e teste.
________________________________________
Tecnologias Utilizadas
•	Python 3.11
•	TensorFlow
•	Keras
•	NumPy
•	Matplotlib
•	Scikit-Learn
•	Jupyter Notebook
•	PyCharm
________________________________________
Pré-processamento
As seguintes etapas foram aplicadas às imagens:
  •	Redimensionamento para 224x224 pixels;
  •	Normalização dos valores dos pixels;
  •	Organização dos conjuntos de treino, validação e teste;
  •	Carregamento por meio do ImageDataGenerator.
________________________________________
Modelos Implementados
CNN Desenvolvida do Zero
Arquitetura composta por:
  •	Camadas Convolucionais;
  •	Camadas MaxPooling;
  •	Flatten;
  •	Camadas Dense;
  •	Dropout.
Resultado obtido:
  •	Accuracy: 69%
Transfer Learning - MobileNetV2
Utilização de pesos pré-treinados da MobileNetV2 para extração de características das imagens.
Resultado obtido:
  •	Accuracy: 79%
________________________________________
Estrutura do Projeto
fase4/
│
├── dataset/
│   └── chest_xray/
│       ├── train/
│       ├── test/
│       └── val/
│
├── relatorios/
│   └── relatorio_fase4.pdf
│
├── preprocessamento.ipynb
├── cnn_classificacao.ipynb
│
└── README.md
________________________________________
Execução
1. Instalar dependências
pip install tensorflow
pip install numpy
pip install matplotlib
pip install scikit-learn
pip install notebook
2. Executar o notebook de pré-processamento
preprocessamento.ipynb
3. Executar o notebook de classificação
cnn_classificacao.ipynb
________________________________________
Resultados
Comparação dos modelos:
Modelo	Accuracy
CNN do Zero	69%
MobileNetV2	79%
Os resultados demonstraram que o modelo baseado em Transfer Learning apresentou desempenho superior ao modelo desenvolvido do zero, evidenciando a eficiência da reutilização de pesos pré-treinados para tarefas de classificação de imagens médicas.
________________________________________
Relatório
A documentação completa da atividade encontra-se na pasta:
relatorios/
O relatório apresenta:
•	Descrição do dataset;
•	Pipeline de pré-processamento;
•	Arquitetura dos modelos;
•	Métricas de avaliação;
•	Discussão dos resultados;
•	Conclusões.
________________________________________
Considerações Finais
O projeto demonstrou a aplicação prática de Visão Computacional na área da saúde, utilizando técnicas de Deep Learning para classificação de exames médicos.
Os resultados obtidos indicam que abordagens baseadas em Transfer Learning podem oferecer desempenho superior quando comparadas a modelos treinados do zero, especialmente em cenários com recursos computacionais limitados.
________________________________________
Licença
Projeto desenvolvido para fins acadêmicos na FIAP, como parte das atividades da disciplina de Inteligência Artificial aplicada à saúde.
