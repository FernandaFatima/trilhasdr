# 🚀 Trilha de Aprendizagem SDR 

## ⚠️ Status do Projeto: Em Desenvolvimento Contínuo

O projeto está atualmente em **fase de desenvolvimento e lapidação contínua**. O objetivo é garantir a máxima eficácia e usabilidade dos recursos.

O foco da próxima iteração será aprimorar a seção **🏆 Hall da Fama**, refinando a lógica e usabilidade.

---

## 💡 Overview do Projeto

Esta **Trilha de Aprendizagem SDR** é um recurso técnico e prático, projetado para o desenvolvimento contínuo de profissionais de Sales Development Representative (SDRs) educacionais. O foco é proporcionar uma experiência de evolução, através de módulos de conteúdo aplicável, ferramentas indispensáveis e desafios gamificados.

O projeto é um **aplicativo de página única (SPA) estático**, com persistência de dados via *LocalStorage* para a seção de reconhecimento (`Hall da Fama`), garantindo alta disponibilidade e velocidade de carregamento (Publicação via GitHub Pages).

---

## 🏗️ Estrutura e Funcionalidades

O conteúdo está organizado em módulos que cobrem todo o ciclo de pré-vendas, desde a inteligência de prospecção até o *mindset* de alta performance.

### 1. 🔧 Ferramentas Indispensáveis
Módulo dedicado ao **enriquecimento e prospecção de dados B2B**. Detalha o uso e as funcionalidades de ferramentas críticas para um SDR de alto volume, focando em:
* **Lusha:** Captura e validação de contatos corporativos em plataformas como LinkedIn.
* **Apollo:** Plataforma de inteligência de dados, busca por ICP (Ideal Customer Profile) e automação de fluxos.
* **Hunter.io / Snov.io:** Busca e verificação de padrões de e-mail e criação de cadências inteligentes.

### 2. 📚 Biblioteca de Aprofundamento
Curadoria de multimídia (vídeos e podcasts) para aprimoramento técnico em:
* **Cold Call e Qualificação:** Técnicas avançadas para domínio da ligação fria.
* **Objeções B2B:** Estratégias para contornar barreiras e objeções comuns.
* **Mindset e Cadências:** Foco em resiliência, gestão de pipeline e sequências de follow-up eficazes.

### 3. 📄 Cardápio de Abordagens (Recurso Colaborativo)
Um repositório externo de **modelos e scripts prontos** para aplicação imediata. O diferencial deste recurso é o seu caráter **colaborativo**, onde o time é incentivado a contribuir com novas abordagens e *templates* validados, acelerando o aprendizado coletivo.

### 4. 🎮 Módulos de Gamificação
Elementos práticos para consolidação do conhecimento:
* **Escape Room – SDR Ninja:** Desafio interativo que testa a precisão na qualificação e contorno de objeções em um ambiente simulado.
* **Jornada SDR Master Challenge:** Trilha guiada para dominar técnicas e desbloquear um certificado de conclusão.

### 5. 🏆 Hall da Fama (Top SDR Awards)
Um sistema de reconhecimento de **performance e boas práticas**.
* **Status:** O módulo é funcional, mas está em **processo de lapidação**, visando aprimorar a persistência e visualização dos dados.
* **Funcionalidade Atual:** Permite o envio e o ranking de conquistas (melhor ligação, melhor abordagem, reativação) via um formulário que utiliza **JavaScript (Vanilla JS)** para processamento e **LocalStorage** para persistência de dados.
* **Engajamento:** Implementa um sistema de *likes* com efeitos visuais (`anime.js` para partículas) para promover o reconhecimento e engajamento do time.

---

## 🛠️ Stack Tecnológico e Deploy

| Componente | Tecnologia | Observações Técnicas |
| :--- | :--- | :--- |
| **Estrutura** | HTML5 (Semântico) | Base estática do conteúdo. |
| **Estilo** | CSS3 (Responsivo) | Design otimizado via Media Queries e variáveis CSS. |
| **Interatividade**| JavaScript ES6+ | Lógica do formulário e ranking do Hall da Fama (Local Storage). |
| **Animações** | Anime.js | Biblioteca leve para efeitos de partículas no sistema de *likes*. |
| **Hospedagem**| GitHub Pages | Publicação contínua (`deploy`) via GitHub Actions (Static HTML workflow). |
| **Status** | **Publicado** | O site está no ar e acessível publicamente. |

### Link de Acesso

A Trilha de Aprendizagem está disponível no endereço fornecido pelo GitHub Pages:

**Acesse aqui:** [https://fernandafatima.github.io/trilhasdr/](https://fernandafatima.github.io/trilhasdr/)

---

Desenvolvido por **Fernanda Fátima da Silva** | 2025
