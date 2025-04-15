# Fiap -  Fase 6 -  Visão Computacional com YOLO e CNN

Este repositório reúne duas entregas obrigatórias da Fase 6 do curso de Inteligência Artificial da FIAP. O projeto simula um sistema de Visão Computacional aplicado a um cliente fictício da FarmTech Solutions, com foco na detecção e classificação de objetos.

Na Entrega 1, utilizamos a arquitetura YOLOv5 customizada para treinar um modelo com imagens rotuladas manualmente. Na Entrega 2, comparamos essa abordagem com uma rede YOLO tradicional (pré-treinada) e uma CNN desenvolvida do zero, avaliando desempenho e aplicabilidade.

## Como executar

### Clonar o repositório
Abra o Google Colab e execute:

```python
!git clone https://github.com/GuCastro81/p6a1-visao-computacional.git 

%cd p6a1-visao-computacional

```
---

## 🎯 Entrega 1 — Sistema de visão computacional com YOLOv5 

Neste projeto fomos desafiados pela FarmTech Solutions a criar um sistema de visão computacional utilizando o modelo YOLOv5. O objetivo era demonstrar na prática a aplicação e eficácia dessa tecnologia em um cenário escolhido livremente pelo grupo.

Escolhemos dois objetos distintos para análise: capacetes de segurança e drones, totalizando 80 imagens divididas igualmente entre os dois conjuntos. Essa seleção foi feita visando explorar a detecção de objetos tanto no contexto de segurança no trabalho quanto em tecnologias de monitoramento.

 
## Introdução

Neste projeto desenvolvido para a fase 6 do curso, fomos desafiados pela FarmTech Solutions a criar um sistema de visão computacional utilizando o modelo YOLO (You Only Look Once). O objetivo era demonstrar na prática a aplicação e eficácia dessa tecnologia em um cenário escolhido livremente pelo grupo.

Escolhemos dois objetos distintos para análise: **capacetes de segurança** e **drones**, totalizando 80 imagens divididas igualmente entre os dois conjuntos. Essa seleção foi feita visando explorar a detecção de objetos tanto no contexto de segurança no trabalho quanto em tecnologias de monitoramento.

### Ferramentas utilizadas

- **Rotulação:** [Make Sense IA](https://www.makesense.ai/)
- **Ambiente de desenvolvimento:** Google Colab conectado ao Google Drive
- **Framework utilizado:** YOLOv5
- **Dataset** - Google Drive
  - **Total de imagens:** 80 imagens
    - 40 imagens de **capacetes de segurança**
    - 40 imagens de **drones**
  - **Divisão do dataset:**
    - Treinamento: 64 imagens (32 por objeto)
    - Validação: 8 imagens (4 por objeto)
    - Testes: 8 imagens (4 por objeto)

- Foram executadas duas simulações de treinamento com números distintos de épocas:
- **Primeira simulação:** 30 épocas
- **Segunda simulação:** 60 épocas

### Notebook Jupyter (Colab)
Acesse o notebook Jupyter através deste link:
- [link]

O notebook contém:
- Células de código executadas e comentadas detalhadamente.
- Células de Markdown com explicações sobre o método utilizado, análises dos resultados obtidos e conclusões sobre pontos fortes e limitações do modelo.

🔗 [Vídeo Demonstrativo no YouTube (até 5 min)](https://www.youtube.com/)  

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

### Equipe desenvolvedora
- [Amandha Nery](https://github.com/insanedays/)(RM560030) 
- Bruno Conterato (RM561048)
- Gustavo Castro (RM560831)
- Kild Fernandes (RM560615)
- Luis Emidio (RM559976)
  
### Professores
- Monitor: Leonardo Ruiz Orabona
- Coordenador: André Godoi




