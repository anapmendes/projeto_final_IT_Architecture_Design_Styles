# FIAP Nutrition Store: Modernização Arquitetural 

Repositório destinado à entrega do trabalho final da disciplina de Arquitetura de Software (MBA FIAP) IT Architecture Design and Styles. O projeto documenta a estratégia de modernização arquitetural de um e-commerce de suplementos esportivos, evoluindo de um sistema monolítico para uma arquitetura orientada a microsserviços.

## 👥 Equipe (Grupo)

| Nome | RM |
| :--- | :--- |
| Adriano Silva | RM 362980 |
| Ana Paula da Silva Mendes | RM 361705 |
| Anderson Fiuza de Paula | RM 360714 |
| Gustavo Calderon | RM 364458 |
| Leonam Pereira Dias | RM 360829 |
| Wésley Fonseca Pivoto Dias | RM 364183 |

---

## 📹 Apresentação em Vídeo

[**Clique aqui para assistir ao vídeo de apresentação do projeto**](#) *https://youtu.be/Oj4KLN6fTwc*

> **Nota ao Professor:** No vídeo, todos os integrantes da equipe apresentam os detalhes do projeto, motivações, riscos e a evolução dos desenhos arquiteturais.

---

## 📂 Guia de Navegação dos Entregáveis

Todos os tópicos exigidos para esta entrega foram detalhadamente respondidos e consolidados no documento oficial em PDF e no Deck de Apresentação. Abaixo, o mapeamento de onde encontrar cada item dentro dos arquivos disponibilizados:

### 📄 Documentação Principal
* **`Fiap Nutrition Store - versão final.pdf`**: Documento completo contendo todo o memorial descritivo do projeto.
* **`FIAP Nutrition Store - Slides.pdf`**: Deck utilizado para apoiar a apresentação e o storytelling.
Os diagramas AS-IS e TO-BE estão em .png nesse repositório.

### 📍 Mapeamento dos Requisitos no Documento Final (`versão final.pdf`)

#### 1. Visão de Negócio e Planejamento
* **Storytelling e tema:** Como o crescimento do negócio gerou gargalos no monólito e a necessidade de escalabilidade.
* **Objetivos de aprendizado e perguntas-chave:** O que esperamos aprender e as perguntas que guiaram a transição.
* **Análise de riscos e planos de ação:** Principais ameaças (ex: falha na transição, degradação de performance) e como mitigá-las, incluindo frentes de estudo em Negócio, Tecnologia, Dados, Operação e Arquitetura.
* **Stakeholders e usuários:** Mapeamento de quem é impactado, suas expectativas e o que tentam realizar no sistema.

#### 2. Arquitetura e Requisitos
* **Arquitetura Inicial (Freeform):** Visão inicial da proposta utilizando Canais, API Gateway, Domínios e Estratégia de Transição com Strangler Pattern.
* **Descrição dos componentes:** Detalhamento de cada serviço (Catálogo, Carrinho, Pedido, etc.) e infraestrutura.
* **Requisitos Importantes (ASRs):** Definição de Escalabilidade, Disponibilidade, Desempenho, Segurança, Manutenibilidade, Observabilidade e Resiliência.

#### 3. Reflexões e Padrões (C4 Model)
* **Análise crítica dos diagramas:** Como o diagrama ajudou a equipe, completude, simplificações e identificação do metamodelo.
* **Padrões essenciais e ocultos:** Strangler Pattern, API Gateway, Event-Driven, Anti-corruption layer (ACL), Circuit Breakers, etc.
* **Decisões sob incerteza e discussões da equipe:** Reflexões sobre a estratégia de migração gradual.

---

## 🏗️ Desenhos de Arquitetura (C4 Model)

Os diagramas de arquitetura foram desenvolvidos nas camadas AS-IS (Monolítico) e TO-BE (Microsserviços).

### Nível 1: Contexto
* **AS-IS:** `C1 - AS IS.png`
* **TO-BE:** `C1 - TO BE.png`

### Nível 2: Container
* **AS-IS:** `C2 - AS IS.png`
* **TO-BE:** `C2 - TO BE.png`

### Nível 3: Componente
* **AS-IS:** `C3 - AS IS.png`
* **TO-BE:** `C3 - TO BE.png`

> **Nota:** Todos os diagramas em alta resolução estão disponíveis na pasta entregáveis deste repositório e também foram incluídos na documentação PDF. Todos os arquivos estão na pasta entregáveis.

---

## 📬 Contato / Dúvidas
Este material foi preparado para avaliação do professor Leonardo Pinho.
