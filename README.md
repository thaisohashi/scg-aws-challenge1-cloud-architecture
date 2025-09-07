# 🚀 Desafio 1: Diagramas AWS (EC2, EBS, S3, Lambda) - Santander Code Girls 2025

Este repositório contém meu primeiro desafio do bootcamp **Santander Code Girls 2025**, em parceria com a **DIO**.  

O objetivo do desafio é **representar visualmente arquiteturas na AWS** utilizando **EC2, EBS, S3 e Lambda**, explorando conceitos fundamentais de computação em nuvem.


## 📝 Sobre o Projeto

Este projeto apresenta arquiteturas simuladas na AWS, com foco em EC2, EBS, S3 e Lambda.  
O objetivo é demonstrar o **fluxo de dados** e o **uso prático de cada serviço**, usando diagramas feitos no [draw.io](http://draw.io/).


## 🎯 Objetivos de Aprendizagem

- Compreender a função de cada serviço AWS utilizado:
  - **EC2 (Elastic Compute Cloud):** servidor virtual na nuvem.  
  - **EBS (Elastic Block Store):** volume de armazenamento persistente ligado ao EC2.  
  - **S3 (Simple Storage Service):** armazenamento de objetos altamente escalável.  
  - **Lambda:** execução de funções sem necessidade de servidor.  
- Criar **arquiteturas práticas** usando draw.io.  
- Documentar a solução no **GitHub**.


## 🖥️ Arquitetura 1 - EC2 + EBS

<img width="1023" height="550" alt="diagrama1" src="https://github.com/user-attachments/assets/eb5fdfe9-d8a3-4f82-9381-41f060963cdd" />

**Explicação:**

1. O **usuário** acessa a aplicação hospedada na instância **EC2**.  
2. A **EC2** processa a requisição do usuário (por exemplo: abrir página, salvar informações ou consultar dados).  
3. Para armazenar ou recuperar dados, a **EC2** se conecta ao **EBS**, que funciona como um disco rígido virtual.  
4. O **EBS** guarda os dados de forma persistente, mesmo que a instância EC2 seja desligada.


## ☁️ Arquitetura 2 - S3 + Lambda

<img width="1181" height="780" alt="diagrama2" src="https://github.com/user-attachments/assets/e46147ad-0ccb-4695-a2fe-f0af43406e8f" />

**Explicação:**

1. O **usuário** envia um arquivo para o **S3 bucket**.  
2. O **S3** detecta o novo arquivo e aciona a **função Lambda**.  
3. A **Lambda** processa o arquivo (por exemplo: redimensiona, valida ou transforma os dados).  
4. A **Lambda** salva o resultado no **S3**, garantindo armazenamento persistente.


## 🛠️ Tecnologias Utilizadas

- **EC2**  
- **EBS**  
- **S3**  
- **Lambda**  
- **Draw.io**
  

## 🔍 Como Visualizar os Diagramas

Os diagramas foram criados no [draw.io](http://draw.io).  
Você pode abrir os arquivos `.drawio` diretamente no site ou no app desktop do draw.io para explorar e editar.
