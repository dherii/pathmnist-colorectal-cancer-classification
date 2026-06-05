# Classificação de Tecidos Histopatológicos com PathMNIST

## Sobre o Projeto

Este projeto foi desenvolvido para a disciplina de Inteligência Artificial do curso de Sistemas de Informação da UniCatólica de Quixadá.

O objetivo é aplicar técnicas de Aprendizado Profundo (Deep Learning) para classificar imagens histopatológicas de câncer colorretal utilizando o dataset PathMNIST da coleção MedMNIST.

O trabalho percorre uma jornada completa, desde a implementação manual de uma rede neural em NumPy até a utilização de arquiteturas modernas de Visão Computacional, como CNNs profundas e Vision Transformers (ViTs).

---

## Integrantes

- Felipe Freires Da Costa
- Gabriel Samilo Pinto De Oliveira
- Eric Matheus Da Silva Temoteo
- Dherick De Sousa Bomfim
- Gustavo Barros Dampaio

---

## Objetivos

- Implementar uma MLP do zero utilizando NumPy.
- Implementar SGD com Momentum e Gradient Checking.
- Migrar a implementação para PyTorch.
- Construir e comparar modelos CNN.
- Avaliar modelos Vision Transformer (ViT).
- Aplicar técnicas de Explainable AI (XAI).
- Comparar diferentes arquiteturas e hiperparâmetros.
- Produzir um relatório científico com análise dos resultados.

---

## Dataset

Dataset utilizado: PathMNIST (MedMNIST v2)

Características:

- Classificação multiclasse
- 9 classes de tecidos histopatológicos
- Aproximadamente 107.000 imagens
- Resolução: 224x224 pixels
- Formato RGB

---

## Estrutura do Projeto

```text
pathmnist-colorectal-cancer-classification/
├── README.md
├── requirements.txt
├── data/
├── notebooks/
├── src/
├── experiments/
├── figures/
└── report/
```

## Etapas do Projeto

### Etapa 1 – Rede Neural em NumPy

- Forward Propagation
- Backpropagation
- SGD com Momentum
- Gradient Checking

### Etapa 2 – Migração para PyTorch

- MLP equivalente
- DataLoaders
- Transforms
- Normalização

### Etapa 3 – CNNs e Vision Transformers

- CNN própria
- CNNs pré-treinadas
- Vision Transformer

### Etapa 4 – Explainable AI

- Feature Maps
- Grad-CAM
- Interpretação dos resultados

### Etapa 5 – Modelo Final

- Ajuste de hiperparâmetros
- Data Augmentation
- Avaliação final

---

## Reprodutibilidade

Seed utilizada:

```python
SEED = 42
```

As seeds serão fixadas para garantir a reprodutibilidade dos experimentos.

---

## Ambiente de Execução

### Hardware

Preencher após a conclusão dos experimentos.

CPU:
GPU:
RAM:
VRAM:

### Software

Python: preencher

PyTorch: preencher

NumPy: preencher

MedMNIST: preencher

---

## Como Executar

### Instalar dependências

```bash
pip install -r requirements.txt
```

### Executar notebooks

Os notebooks estão disponíveis na pasta:

```text
notebooks/
```

---

## Resultados

Esta seção será atualizada ao longo do desenvolvimento do projeto.

### Melhor Modelo

Em desenvolvimento.

### Métricas

Em desenvolvimento.

### Matriz de Confusão

Em desenvolvimento.

---

## Uso de IA Generativa

Durante o desenvolvimento do projeto foram utilizadas ferramentas de IA generativa como apoio para pesquisa, revisão de código, esclarecimento de conceitos e organização da documentação.

Etapas:
- Auxílio na organização da estrutura do projeto.
- Esclarecimento de conceitos teóricos sobre Deep Learning.
- Revisão gramatical de trechos produzidos pela equipe.
- Apoio na interpretação de resultados experimentais.

---

## Licença

Projeto acadêmico desenvolvido exclusivamente para fins educacionais.

'ainda irei finalizar o readme'