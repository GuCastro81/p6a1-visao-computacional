# Fiap -  Fase 6 -  Visão Computacional com YOLO e CNN

Este repositório reúne duas entregas obrigatórias da Fase 6 do curso de Inteligência Artificial da FIAP. O projeto simula um sistema de Visão Computacional aplicado a um cliente fictício da FarmTech Solutions, com foco na detecção e classificação de objetos.

Na Entrega 1, utilizamos a arquitetura YOLOv5 customizada para treinar um modelo com imagens rotuladas manualmente. 
Na Entrega 2, comparamos essa abordagem com uma rede YOLO tradicional (pré-treinada) e uma CNN desenvolvida do zero, avaliando desempenho e aplicabilidade.

## Como executar

#### Clonar o repositório
Abra o Google Colab e execute:

```python
!git clone https://github.com/GuCastro81/p6a1-visao-computacional.git 

%cd p6a1-visao-computacional

```
---

## 🎯 Entrega 1 — Sistema de visão computacional com YOLOv5 

Neste projeto fomos desafiados pela FarmTech Solutions a criar um sistema de visão computacional utilizando o modelo YOLOv5. O objetivo era demonstrar na prática a aplicação e eficácia dessa tecnologia em um cenário escolhido livremente pelo grupo.

Escolhemos dois objetos distintos para análise: capacetes de segurança e drones, totalizando 80 imagens divididas igualmente entre os dois conjuntos. Essa seleção foi feita visando explorar a detecção de objetos tanto no contexto de segurança no trabalho quanto em tecnologias de monitoramento.


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
Acesse o notebook Jupyter através deste [link](https://colab.research.google.com/drive/1AB1_zVO89Xih9t1GqknAmx9thRaxVzO0?usp=sharing)

O notebook contém:
- Células de código executadas e comentadas detalhadamente.
- Células de Markdown com explicações sobre o método utilizado, análises dos resultados obtidos e conclusões sobre pontos fortes e limitações do modelo.

🔗 [[Vídeo Demonstrativo no YouTube )](https://youtu.be/0kCADhcjvhs)

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

## 🔗 Acesso aos Notebooks no Google Colab

- 🎯 [Notebook – YOLOv5 padrão (pré-treinado)](https://colab.research.google.com/drive/17q-kkEWtyHZwq8ZG-6HRv0nD_2VJVJWO)
- 🧠 [Notebook – CNN treinada do zero](https://colab.research.google.com/drive/1hfeOuIF8BI0GSHc0PwNLqh07LUoZ3Rpa)

🔍 A análise crítica está incluída em células Markdown no próprio notebook.

---

## 📁 Estrutura do Repositório

```
├── data/                          # Pasta com dados utilizados para treinamento/teste
├── entrega2_cnn.ipynb            # Notebook com modelo CNN treinado do zero
├── entrega2_yolov5_padrao_comp.ipynb  # Notebook com YOLOv5 pré-treinado (comparação)
├── train_yolo.ipynb              # Notebook de treinamento do modelo YOLO customizado
├── TODO.md                       # Lista de tarefas ou pendências do projeto
├── README.md                     # Documentação principal do repositório
└── .gitignore                    # Arquivos/pastas ignoradas pelo Git

```

---

## 📌 Observações Finais

- O notebook está comentado e organizado conforme as boas práticas de documentação e análise crítica.
- O vídeo demonstrativo está disponível no YouTube, com duração inferior a 5 minutos, apresentando o funcionamento do sistema.
- As imagens de teste e validação utilizadas foram capturadas, organizadas e rotuladas pelo grupo, conforme as orientações do projeto.

---
## 👥 Equipe

- [Amandha Nery](https://github.com/insanedays/)(RM560030) 
- Bruno Conterato (RM561048)
- Gustavo Castro (RM560831)
- Kild Fernandes (RM560615)
- Luis Emidio (RM559976)
  
### Professores
- Monitor: Leonardo Ruiz Orabona
- Coordenador: André Godoi

## 📬 Contato  
Se tiver alguma dúvida, sinta-se à vontade para entrar em contato. 🚀


