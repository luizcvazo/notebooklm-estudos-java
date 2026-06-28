# ☕ Java Development Guide: De Fundamentos a APIs RESTful com Spring Boot

## 🎯 Contexto e Objetivos

Este repositório é o resultado de um estudo focado no ecossistema **Java Moderno**, com ênfase na construção de backends robustos utilizando **Spring Boot** e sua integração com tecnologias web (HTML, CSS, JS e Angular). 

Os principais objetivos deste material são:
*   Dominar os fundamentos da linguagem Java e o funcionamento da **JVM**.
*   Aplicar princípios de **Arquitetura Limpa** e **SOLID** para criar sistemas escaláveis.
*   Construir uma **API REST** funcional para operações de CRUD (Create, Read, Update, Delete).
*   Explorar as tendências de mercado para **2026**, como Virtual Threads e integrações com IA.

---

## 📚 Curadoria de Fontes

Para este estudo, foram selecionadas fontes estratégicas que cobrem desde a teoria acadêmica até guias práticos de mercado:

1.  **Deitel, "Java: Como Programar"**: Referência absoluta para o aprendizado progressivo de sintaxe, estruturas de controle e POO.
2.  **Robert C. Martin, "Arquitetura Limpa"**: Fundamental para entender como separar regras de negócio de detalhes técnicos.
3.  **Oracle Brasil, "CRUD REST utilizando Spring Boot 2..."**: Guia prático para a implementação de persistência com JPA e Hibernate.
4.  **Turing, "72 perguntas para entrevistas de emprego Java"**: Uma base de revisão técnica focada em desafios reais de processos seletivos.
5.  **NexuCodePlay, "Roadmap Backend Java 2026"**: Visão atualizada sobre a stack necessária para o nível sênior em 2026.

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

Durante o desenvolvimento deste caderno, diferentes abordagens de interação com a IA foram testadas para extrair o melhor resultado:

*   **Prompt de Visão Geral:** *"Faça um resumo do que pode me ensinar sobre Java."*
    *   **Resultado:** Gerou uma base sólida sobre JVM e POO, mas foi necessário refinar para incluir recursos modernos.
*   **Prompt Estrutural (CRUD):** *"Me ajude a criar um CRUD em java que será consumido como um sistema web."*
    *   **Troubleshooting (Cicatriz):** O primeiro resultado focou apenas no backend. Tive que iterar pedindo especificamente a integração com **Fetch API** no JavaScript para garantir que o front-end pudesse consumir o JSON gerado pelo Spring Boot.
*   **Refinamento para 2026:** Ao perguntar sobre tendências, a IA inicialmente ignorou **Virtual Threads**. Foi preciso cruzar os dados com a fonte da *iMasters* sobre o Java 25 para obter informações sobre ganhos de performance em concorrência.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados

#### **A. Fundamentos e POO**
Java é uma linguagem de tipagem forte que roda na **JVM**, permitindo o conceito WORA (*Write Once, Run Anywhere*). Seu núcleo reside na Programação Orientada a Objetos, baseada em **Abstração, Encapsulamento, Herança e Polimorfismo**.

#### **B. Backend com Spring Boot**
O framework elimina configurações manuais (como XMLs antigos) através do **Spring Initializr**. A arquitetura recomendada é a divisão em camadas: **Controller** (endpoints), **Service** (regras de negócio) e **Repository** (acesso ao banco via Spring Data JPA).

#### **C. Integração Web**
O backend expõe dados em formato **JSON**. O front-end (HTML/JS) utiliza métodos HTTP (GET, POST, PUT, DELETE) para interagir com esses recursos, sendo essencial a configuração de **CORS** para permitir a comunicação entre domínios diferentes.

### 2. Glossário de Conceitos Chave

*   **JVM (Java Virtual Machine):** Máquina virtual que interpreta o bytecode Java em código de máquina nativo.
*   **Spring Data JPA:** Camada de abstração sobre o Hibernate que permite criar consultas ao banco apenas definindo interfaces.
*   **DTO (Data Transfer Object):** Padrão de projeto para trafegar dados entre camadas sem expor a entidade do banco de dados.
*   **SOLID:** Conjunto de 5 princípios (SRP, OCP, LSP, ISP, DIP) que visam tornar o código mais modular e fácil de manter.
*   **REST:** Estilo arquitetural que utiliza o protocolo HTTP para comunicação entre sistemas.

### 3. Prompts Reutilizáveis para Revisão

*   *"Explique como o princípio da Inversão de Dependência (DIP) é aplicado em um repositório Spring Boot."*
*   *"Quais as diferenças práticas entre usar ArrayList e LinkedList em um sistema de alta performance?"*
*   *"Gere um exemplo de validação de dados (@Valid) para um formulário de cadastro de usuários no Java."*
*   *"Como configurar o Spring Security para proteger uma API REST usando JWT?"*

---
*Este material foi gerado com auxílio do NotebookLM para fins educacionais.*
---

Link do notebook: https://notebooklm.google.com/notebook/64942841-8959-434a-ad7c-d35192c3f2e7
