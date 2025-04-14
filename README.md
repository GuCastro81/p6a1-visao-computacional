# Visão Computacional com YOLO e CNN – Fase 6

Este repositório reúne duas entregas obrigatórias da Fase 6 do curso de Inteligência Artificial da FIAP. O projeto simula um sistema de Visão Computacional aplicado a um cliente fictício da FarmTech Solutions, com foco na detecção e classificação de objetos.

Na Entrega 1, utilizamos a arquitetura YOLOv5 customizada para treinar um modelo com imagens rotuladas manualmente. Na Entrega 2, comparamos essa abordagem com uma rede YOLO tradicional (pré-treinada) e uma CNN desenvolvida do zero, avaliando desempenho e aplicabilidade.

---

## 🎯 Entrega 1 — Sistema de Visão Computacional com YOLO Customizada

- **Objetivo:** Demonstrar o funcionamento de um sistema de detecção de objetos com YOLOv5, utilizando imagens reais e rotuladas no Make Sense AI.
- **Dataset:** Composto por 80 imagens de dois objetos distintos (40 de cada), separadas em treino, validação e teste.
- **Processos realizados:**
  - Rotulagem manual com bounding boxes.
  - Treinamento com 30 e 60 épocas.
  - Avaliação de desempenho do modelo com imagens reais.
  - Prints dos resultados do diretório `runs/detect/expX`.

🔗 [Vídeo Demonstrativo no YouTube (até 5 min)](https://www.youtube.com/)  
📘 [Notebook no Google Colab](https://colab.research.google.com/)

---

## 🤖 Entrega 2 — Comparação entre Abordagens

- **Objetivo:** Avaliar o desempenho de três abordagens de detecção/classificação:
  1. YOLOv5 customizada (Entrega 1)
  2. YOLOv5 tradicional (pré-treinada)
  3. CNN do zero com Keras/TensorFlow
- **Critérios de comparação:**
  - Facilidade de uso
  - Precisão do modelo
  - Tempo de treinamento
  - Tempo de inferência

📘 [Notebook com Avaliação Comparativa](https://colab.research.google.com/)  
🔍 A análise crítica está incluída em células Markdown no próprio notebook.

---

## 📁 Estrutura do Repositório

```
├── data/                # Pastas para organização local (ex: train, val, test)
├── imgs/                # Prints dos testes
├── yolov5/              # Repositório clonado da YOLOv5 (opcional)
├── gustavo_rocha_rmXXXXXX_pbl_fase6.ipynb
├── README.md
└── .gitignore
```

---

## 📌 Observações Finais

- O notebook está comentado e organizado conforme as boas práticas de documentação e análise crítica.
- O vídeo demonstrativo está disponível no YouTube, com duração inferior a 5 minutos, apresentando o funcionamento do sistema.
- As imagens de teste e validação utilizadas foram capturadas, organizadas e rotuladas pelo grupo, conforme as orientações do projeto.

---

**FIAP | Fase 6 – Projeto de Inteligência Artificial | 2025**
