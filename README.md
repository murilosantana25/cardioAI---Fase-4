# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

<br>


# Atividade 01- Fiap Inteligência Artificial Cardiologica #

## 👨‍🎓 Integrantes:
- João José Domingues Siva
- William Xavier
- Murílo Santana
- William Ferreira

## 👩‍🏫 Professores:
### Tutor(a)
- Caique Nonato da Silva Bezerra
### Coordenador(a)
- André Godoi

---

## 📜 Descrição

Nesta fase do projeto CardioIA foi desenvolvido um protótipo de Visão Computacional para classificação de imagens médicas.<br>
A solução utiliza Redes Neurais Convolucionais (CNNs) para analisar radiografias de tórax e identificar padrões associados à pneumonia. Foram implementadas duas abordagens distintas:<br><br>
   •	CNN desenvolvida do zero;<br>
   •	Transfer Learning utilizando MobileNetV2.<br>
O objetivo é demonstrar como técnicas de Inteligência Artificial podem auxiliar na análise de exames médicos e apoiar processos de tomada de decisão.<br>


---

## Dataset Utilizado

Dataset: Chest X-Ray Images (Pneumonia) <br>
Origem: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia <br>
Características: <br>
   •	Imagens de radiografia de tórax; <br>
   •	Duas classes: <br>
      o	NORMAL <br>
      o	PNEUMONIA <br>
   •	Conjuntos separados em treino, validação e teste. <br><br>


## Tecnologias Utilizadas

   •	Python 3.11 <br>
   •	TensorFlow <br>
   •	Keras <br>
   •	NumPy <br>
   •	Matplotlib <br>
   •	Scikit-Learn <br>
   •	Jupyter Notebook <br>
   •	PyCharm <br>

---

## 📁 Estrutura

```
├── fase4/
├── dataset/
│   └── chest_xray              # pasta das imagens
├── relatorios/
│   └── relatorio_fase4.pdf
├── README.md      #
├── preprocessamento.ipynb
├── cnn_classificacao.ipynb
└── README.md
```

---

## 🚀 Execução

1. Instalar dependências <br>
pip install tensorflow <br>
pip install numpy <br>
pip install matplotlib <br>
pip install scikit-learn <br>
pip install notebook <br><br>

2. Executar o notebook de pré-processamento <br>
preprocessamento.ipynb <br><br>

3. Executar o notebook de classificação <br>
cnn_classificacao.ipynb <br>

---

## 📚 Documentação

A documentação completa da atividade encontra-se na pasta: <br>
relatorios/ <br>
O relatório apresenta: <br><br>
•	Descrição do dataset; <br>
•	Pipeline de pré-processamento; <br>
•	Arquitetura dos modelos; <br>
•	Métricas de avaliação; <br>
•	Discussão dos resultados; <br>
•	Conclusões. <br>


## 📚 Vídeo
Link do vídeo explicativo: https://www.loom.com/share/522823435b414e779c1e347a0d0d8772


---



   

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

> Projeto desenvolvido para fins acadêmicos, seguindo boas práticas de ciência de dados e aprendizado de máquina.

