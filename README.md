# 📊 Análise de Desempenho Escolar – TIMSS 2023
**Explorando fatores familiares, hábitos e atividades extracurriculares que influenciam o desempenho em matemática de alunos do 4º ano.**

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)

---

## 📑 Tabela de Conteúdos
- [📘 Sobre o Projeto](#-sobre-o-projeto)
- [🧠 Contexto e Objetivo](#-contexto-e-objetivo)
- [📂 Dados Utilizados](#-dados-utilizados)
- [🚀 Como Executar](#-como-executar)
- [📊 Principais Insights](#-principais-insights)
- [📁 Estrutura do Repositório](#-estrutura-do-repositório)
- [👨‍💻 Autores](#-autores)
- [🏆 Certificação](#-certificação-i-sacede)

---

## 📘 Sobre o Projeto
Este projeto realiza uma análise exploratória dos dados do **TIMSS 2023** (*Trends in International Mathematics and Science Study*), focando no desempenho matemático de alunos do **4º ano**.

A análise relaciona:
- contexto familiar  
- hábitos de leitura  
- uso de tecnologia  
- atividades extracurriculares  
- fatores socioeconômicos  

Com o objetivo de identificar padrões associados ao desempenho acadêmico.

---

## 🧠 Contexto e Objetivo
A partir de milhares de registros do TIMSS, investigamos:

✔️ A frequência de leitura em casa impacta o desempenho?  
✔️ Possuir computador próprio melhora os resultados?  
✔️ Hábitos lógicos (como “contar coisas”) influenciam na performance?  

O trabalho fez parte do curso de **Inteligência e Análise de Dados – Senai Suíço-Brasileira** e foi **aprovado para apresentação no I SACEDE**.

---

## 📂 Dados Utilizados

Os datasets necessários **não estão no repositório** devido ao tamanho.  
Você deve baixá-los manualmente:

📁 **Link para download dos dados (Google Drive):**  
https://drive.google.com/drive/folders/13KzaWSVe9vycb-7eHRqC90gYN_5YH5KP?usp=sharing

**Arquivos obrigatórios:**
- `home-context-grade-4.csv`
- `student-achievement-grade-4.csv`
- `student-context-grade-4.csv`

> Após baixar, mova todos para a **raiz do projeto**, onde está o arquivo `timss.ipynb`.

---

## 🚀 Como Executar

### 1️⃣ Instalar dependências
```bash
pip install pandas numpy matplotlib seaborn jupyter
2️⃣ Executar Jupyter Notebook
```
Abra o arquivo:

`timss.ipynb`

E execute tudo com:

``Kernel → Restart & Run All``

### 📊 Principais Insights

## 🧩 1. Hábitos e Desempenho
Alunos que contam coisas no dia a dia ou têm pais que leem frequentemente para eles tendem a obter notas mais altas.

## 📖 2. Leitura em Casa
Pais de alta performance: leem frequentemente.

Pais de baixa performance: nunca leem.

<img width="989" height="590" alt="download (1)" src="https://github.com/user-attachments/assets/48d219f7-59d6-44d8-887a-ff488aa737e1" />


## 💻 3. Tecnologia
Apenas possuir um computador não foi um diferencial determinante no desempenho matemático.

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/15dbd7dc-55d2-4138-be39-6292a8bfdf8f" />

### 📁 Estrutura do Repositório
bash
Copiar código
📦 timss-2023-analysis
├── 📄 README.md
├── 📓 timss.ipynb
├── 📁 /datasets   (você deve criar e inserir os CSVs aqui ou na raiz)
└── 📁 /images     (gráficos exportados opcionalmente)
👨‍💻 Autores
Nome	GitHub
Davi Vieira Nakaharada	—
Erick Cardoso Martins	—

### 🏆 Certificação (I SACEDE)
Este trabalho foi aceito para apresentação no
I Seminário Acadêmico e Científico de Educação a Distância e Ensino Online, realizado em outubro de 2025.

<img width="1011" height="643" alt="aceite" src="https://github.com/user-attachments/assets/fa2801a3-3404-49ff-8448-0b26f58f3741" />
