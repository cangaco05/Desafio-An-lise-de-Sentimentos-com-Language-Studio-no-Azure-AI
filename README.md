# 📊 Azure Sentiment Analysis – Opinion Mining com Language Studio

![Static Badge](https://img.shields.io/badge/📅_Finalizado-13/08/2025-green)

![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Azure AI](https://img.shields.io/badge/Azure%20AI-Language%20Studio-0078D4?logo=microsoftazure)
![License](https://img.shields.io/badge/license-MIT-blue)

Projeto prático para demonstrar o uso do serviço **Analyze Sentiment and Mine Opinions** no **Azure AI Language Studio**, como parte do Bootcamp **Microsoft Azure AI Fundamentals** (DIO).

---

## 🗂 Índice
1. [🚀 Objetivo](#-objetivo)
2. [🛠 Procedimento](#-procedimento)
3. [📈 Resultados](#-resultados)
4. [💡 Conclusão](#-conclusão)


---

## 🚀 Objetivo
Realizar análise de sentimentos e mineração de opiniões em um texto, explorando as funcionalidades de **NLP (Natural Language Processing)** disponíveis no **Azure Language Studio**.

---

## 🛠 Procedimento

### 1️⃣ Criar recurso no Azure
```text
Azure Portal → Create Resource → Language Service → Deploy
```
<img width="762" height="524" alt="01" src="https://github.com/user-attachments/assets/44241162-3d50-4762-b668-933ce6668588" />

<img width="634" height="765" alt="03" src="https://github.com/user-attachments/assets/db6939bf-86b9-4c09-b101-84b7cb04b561" />

### 2️⃣ Conectar ao Language Studio
Abrir o Language Studio

<img width="1000" height="622" alt="04" src="https://github.com/user-attachments/assets/69a16f1f-b13e-4527-ac7d-174c8a7fe6eb" />


Selecionar o recurso criado no passo anterior
<img width="1000" height="622" alt="05" src="https://github.com/user-attachments/assets/9d415478-f82e-4e13-bb39-2f6b4d89fcc3" />


### 3️⃣ Rodar o serviço
Acessar Classify text → Analyze sentiment and mine opinions
<img width="1020" height="583" alt="06" src="https://github.com/user-attachments/assets/c99b90cf-e872-4e63-bab3-88d3b0b94167" />

## 📈 Resultados
No serviço, é possível enviar o texto para análise, definir o idioma e habilitar a função Opinion Mining.
Neste teste, foi utilizado um capítulo do evangelho de Mateus, contido na Bíblia.

<img width="1716" height="784" alt="07" src="https://github.com/user-attachments/assets/c9f314d3-d3ba-4828-b044-72c647a316ae" />

A análise indicou 65% de negatividade, mas com apenas 25% de confiança, variando entre sentenças com alta e baixa precisão.
<img width="473" height="256" alt="08" src="https://github.com/user-attachments/assets/31e69cfa-77c8-45e2-bb49-d219ea499816" />

<img width="649" height="288" alt="09" src="https://github.com/user-attachments/assets/1503a97d-bbe1-4329-b166-e25a34e3ddae" />

<img width="662" height="265" alt="10" src="https://github.com/user-attachments/assets/6feb6db9-b166-4435-aace-ef1ebe800c9c" />


## 💡 Conclusão 

>
> Ferramentas de análise de sentimentos e mineração de opiniões representam componentes valiosos na automação de processos de avaliação de feedbacks em serviços e produtos. Embora apresentem alta acurácia em textos explicitamente opinativos — como comentários e avaliações de consumidores —, sua eficácia tende a ser reduzida em conteúdos cuja carga emocional ou intenção subjetiva não se apresenta de forma explícita. Essa limitação decorre, em grande parte, do fato de que o mecanismo de análise processa sentenças de maneira isolada, sem realizar uma interpretação contextual abrangente do documento. A adoção de modelos capazes de estabelecer relações semânticas entre sentenças e inferir significado a partir de um contexto global provavelmente resultaria em diagnósticos mais precisos e consistentes.






