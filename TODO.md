# P6A1 TODO

## 🎯 ENTREGA 1 — Sistema de Visão Computacional com YOLO

### Etapa 1: Preparação dos Dados

1. Escolher *2 objetos distintos (A e B)* para reconhecimento.  
2. Montar um *dataset com no mínimo 80 imagens*:
   - 40 imagens do objeto A  
   - 40 imagens do objeto B  
3. Separar as imagens em pastas:
   - Treino: 32 imagens por objeto  
   - Validação: 4 imagens por objeto  
   - Teste: 4 imagens por objeto  
4. Armazenar essas pastas no Google Drive pessoal ou do grupo.

### Etapa 2: Rotulagem das Imagens

5. Realizar a *rotulagem (bounding boxes)* usando o site [Make Sense AI](https://www.makesense.ai/).  
6. Exportar os arquivos de rotulagem e salvar também no *Google Drive*.

### Etapa 3: Desenvolvimento no Google Colab

7. Criar um notebook no Colab:
   - Conectado ao Google Drive  
   - Estruturado com *células de Markdown* para descrever o passo a passo  
8. Implementar:
   - *Treinamento da YOLOv5* com suas imagens rotuladas  
   - *Validação e testes*  
9. *Rodar dois treinos com diferentes épocas* (ex: 30 e 60) e comparar:
   - Acurácia  
   - Erro  
   - Desempenho geral  
10. Salvar os resultados do YOLO e verificar os diretórios `runs/detect/expX`.

### Etapa 4: Análise e Apresentação

11. Tirar prints das imagens de teste processadas para mostrar os resultados ao "cliente".  
12. Elaborar as *conclusões* com base nos testes e validações.

### Etapa 5: Entrega no GitHub

13. Criar um repositório GitHub com o nome do grupo.  
14. Subir:
   - Notebook `.ipynb` com nome completo, RM e padrão: `SeuNome_RM_pbl_fase6.ipynb`  
   - README com link do Colab e introdução da solução  
   - Link de vídeo demonstrativo (até 5 min, YouTube não listado) no README  
15. Enviar o link do GitHub via portal FIAP (em PDF, se solicitado).

---

## 🤖 ENTREGA 2 — Comparação entre abordagens

### Etapa 6: Novas Abordagens com Mesmo Dataset

16. Aplicar:
   - *YOLO tradicional* (vista no capítulo 3)  
   - *CNN customizada* (treinada do zero)  
17. Utilizar o mesmo dataset preparado na Entrega 1.

### Etapa 7: Avaliação Comparativa

18. Comparar as três abordagens:
   - YOLO customizada (Entrega 1)  
   - YOLO tradicional  
   - CNN do zero  
19. Critérios:
   - Facilidade de uso/integração  
   - Precisão  
   - Tempo de treinamento  
   - Tempo de inferência

### Etapa 8: Entrega no GitHub

20. Criar outro notebook ou continuar no mesmo, mas:
   - Organizar em seções distintas  
   - Adicionar *avaliações críticas* em Markdown  
   - Mostrar saídas e comparações
