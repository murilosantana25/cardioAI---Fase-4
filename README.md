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

Nesta fase do projeto CardioIA foi desenvolvido um protótipo de Visão Computacional para classificação de imagens médicas.
A solução utiliza Redes Neurais Convolucionais (CNNs) para analisar radiografias de tórax e identificar padrões associados à pneumonia. Foram implementadas duas abordagens distintas:
   •	CNN desenvolvida do zero;
   •	Transfer Learning utilizando MobileNetV2.
O objetivo é demonstrar como técnicas de Inteligência Artificial podem auxiliar na análise de exames médicos e apoiar processos de tomada de decisão.


---

## Dataset Utilizado

Dataset: Chest X-Ray Images (Pneumonia)
Origem: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
Características:
   •	Imagens de radiografia de tórax;
   •	Duas classes:
      o	NORMAL
      o	PNEUMONIA
   •	Conjuntos separados em treino, validação e teste.


## Tecnologias Utilizadas

   •	Python 3.11
   •	TensorFlow
   •	Keras
   •	NumPy
   •	Matplotlib
   •	Scikit-Learn
   •	Jupyter Notebook
   •	PyCharm

---

## 📁 Estrutura

```
├── wokwi/
│   ├── sketch.ino              # Código ESP32
│   ├── diagram.json            # Diagrama Wokwi
│   └── libraries.txt           # Bibliotecas
├── node-red/
│   └── flows.json              # Fluxo Node-RED
├── RELATORIO_CARDIO_IA.md      # Fluxo e Resiliência
├── RELATORIO_MQTT_DASHBOARD.md # MQTT e Dashboard
└── README.md
```

---

## 🚀 Quick Start

1. **Wokwi:** Abra `diagram.json` em [wokwi.com](https://wokwi.com)
2. **Node-RED:** Importe `flows.json` e acesse `http://localhost:1880/ui`
3. **Arduino:** Compile e envie `sketch.ino` para o ESP32

---

## 📚 Documentação

- [RELATORIO_CARDIO_IA.md](RELATORIO_CARDIO_IA.md) - Análise técnica completa
- [RELATORIO_MQTT_DASHBOARD.md](RELATORIO_MQTT_DASHBOARD.md) - Guia MQTT + Dashboard

---

## 🗃 Histórico

- **12.05.2026** - v1.0.0: Sistema completo (ESP32 + MQTT + Node-RED)
- **14.04.2026** - v0.1.0: Prototipagem inicial

   

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

> Projeto desenvolvido para fins acadêmicos, seguindo boas práticas de ciência de dados e aprendizado de máquina.

