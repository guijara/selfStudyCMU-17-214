# selfStudyCMU-17-214

# Jornada de Engenharia de Software: Padrões, Design e Construção

Bem-vindo ao meu repositório de estudos avançados em Engenharia de Software.

Este projeto documenta a minha jornada autodidata seguindo o currículo rigoroso do curso **17-214: Principles of Software Construction** da **Carnegie Mellon University (CMU)**.

O meu objetivo aqui não é apenas aprender a sintaxe de Java ou TypeScript, mas sim dominar os princípios fundamentais que regem a construção de sistemas robustos, escaláveis e de fácil manutenção no mundo real.

## 🎯 Foco do Aprendizado

Aqui você encontrará implementações, desafios de design e refatorações focadas em:

* **Design Orientado a Objetos Sólido:** Polimorfismo, Encapsulamento e Delegação.
* **Design Patterns (GoF):** Strategy, Factory, Observer, Decorator, entre outros.
* **Qualidade de Código:** Testes Unitários, Integração Contínua e Análise Estática.
* **Sistemas Robustos:** Tratamento de exceções, I/O e Concorrência.

---

## 📚 Projetos e Desafios de Design

Abaixo, documento os desafios práticos que realizei para aplicar os conceitos teóricos.

### 1. Sistema de Notificação (Design Patterns & Polimorfismo)
**O Desafio:** Projetar um serviço de notificações para um e-commerce que fosse extensível (aberto para novos tipos como WhatsApp) sem a necessidade de modificar o código existente (Open/Closed Principle). O design original sofria de alto acoplamento e uso excessivo de condicionais (`switch/case`).

**A Solução:**
* Substituí a lógica condicional por **Polimorfismo** e **Despacho Dinâmico**.
* Criei uma interface de contrato `Notificacao` focada no comportamento (`enviar()`).
* Utilizei **Injeção de Dependência** no serviço para permitir testes mais fáceis e flexibilidade.

**Conceitos Chave:** `Interface Segregation`, `Dynamic Dispatch`, `Loose Coupling`.

[Link para o código deste exercício (se houver pasta específica)](./caminho/para/codigo)

---

### 2. [Nome do Próximo Exercício Futuro]
**O Desafio:** [Breve descrição do problema]
**A Solução:** [Como você resolveu]
**Conceitos Chave:** [Conceitos usados]

---

## 🛠️ Ferramentas Utilizadas

* **Linguagem:** Java (OpenJDK 17+)
* **Build System:** Gradle
* **IDE:** IntelliJ IDEA
* **Controle de Versão:** Git

---
*Nota: Este repositório contém exercícios originais e adaptações pedagógicas. Em respeito à política de integridade acadêmica da CMU, soluções diretas de trabalhos de casa oficiais do curso não são publicadas integralmente.*
