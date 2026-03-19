# 🧠 Sistema RICON aplicado à Neurociência do Consumo

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

---

## 📌 Descrição

Este repositório contém os dados, códigos e materiais utilizados no estudo:

**“Sistema RICON aplicado à Neurociência do Consumo”**

O projeto investiga o impacto de uma intervenção educativa baseada em **neurociência, educação digital e aprendizado de máquina** na promoção do consumo consciente entre jovens.

A metodologia combina:
- Questionários pré e pós-teste (escala Likert)
- Análise estatística inferencial
- Técnicas de aprendizado de máquina (clusterização com K-Means)

O repositório foi estruturado com foco em **reprodutibilidade científica**, permitindo que outros pesquisadores repliquem integralmente os experimentos realizados.

---

## 🌐 Site do Projeto

O projeto também conta com um ambiente digital educativo com conteúdos e atividades:

🔗 https://sites.google.com/view/neurocienciadoconsumo-reeduc

---

## 📂 Estrutura do Repositório

```
├── LICENSE
├── README.md
├── neurociencia_do_consumo.ipynb
└── datasets/
  ├── neurociencia_do_consumo_preteste.xlsx
  ├── neurociencia_do_consumo_posteste.xlsx
  └── info.txt
```

---

## 📊 Conteúdo

Este repositório contém:

- 📄 Dataset do experimento (pré e pós-teste)
- 📊 Dados de respostas em escala Likert (1 a 5)
- 🧠 Notebook com toda a análise (Python / Google Colab)
- 📈 Processamento estatístico e aprendizado de máquina
- 🔍 Identificação de perfis de consumo via clusterização
- 📑 Estrutura completa para replicação do estudo

---

## 🧪 Metodologia (Resumo)

### 1. Coleta de Dados
- Participantes: 25 estudantes (15–20 anos)
- Instrumento: questionário com 7 itens Likert
- Aplicação em dois momentos:
  - Pré-teste
  - Pós-teste

### 2. Pré-processamento
- Padronização de identificadores (e-mails)
- Remoção de respostas inválidas
- Conversão para valores numéricos (1–5)
- Cálculo da média individual

### 3. Aprendizado de Máquina
- Algoritmo: **K-Means Clustering**
- Normalização: `StandardScaler`
- Escolha de k: **Índice de Silhueta**

➡️ Resultado: identificação de **5 perfis de consumidores**

### 4. Métricas de Avaliação
- Ganho absoluto:
  - Δ = pós − pré
- Ganho normalizado (Hake):
  - Avalia evolução relativa ao máximo possível

### 5. Testes Estatísticos
- Normalidade: Shapiro-Wilk
- Teste: t pareado
- Nível de significância: 5%

---

## 📈 Principais Resultados

- 📊 **68% dos participantes apresentaram evolução positiva**
- 📈 Ganho médio:
  - Absoluto: ≈ 0,60  
  - Normalizado: ≈ 0,35  
- 🧠 Identificação de **5 perfis de consumo**
- 🔄 **28% dos participantes mudaram de perfil comportamental**

➡️ Resultados indicam impacto significativo da intervenção educativa

---

## ▶️ Como Reproduzir a Análise

1. Acesse o Google Colab:  
   https://colab.research.google.com/

2. Faça upload do notebook:

```
neurociencia_do_consumo.ipynb
```

3. Faça upload dos datasets:

```
datasets/neurociencia_do_consumo_preteste.xlsx
datasets/neurociencia_do_consumo_posteste.xlsx
`````

4. Execute as células na ordem

---

## 🧰 Tecnologias Utilizadas

- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib

---

## 🔬 Reprodutibilidade

Este repositório segue os princípios da **Ciência Aberta**, garantindo:

- Transparência metodológica  
- Reprodutibilidade dos experimentos  
- Validação independente dos resultados  

Todos os dados e códigos necessários estão disponíveis publicamente.

---

## 📄 Licença

Este projeto está licenciado sob a licença **CC BY 4.0**.

---

## 💡 Citação

Se utilizar este repositório, cite o artigo correspondente.
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18769862-blue)](https://zenodo.org/records/18769862) 

---


