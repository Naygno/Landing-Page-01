# Primeira *Landing Page*

![DIO](https://img.shields.io/badge/DIO-Formação_CSS_Web_Developer-orange)

Uma _landing page_ para geração e conversão de _leads_.

---

## 📖 Sobre o Projeto

Este repositório contém o código fonte da _landing page_ desenvolvida como o **Desafio de Projeto do Módulo 1 - Criando Sua Primeira _Landing Page_ com HTML e CSS**,  do curso **Formação CSS Web Developer** da plataforma [DIO](https://web.dio.me).

O objetivo principal é aplicar de forma prática os conhecimentos adquiridos em HTML5 e CSS3 para construir uma _landing page_ rica, bem estruturada, semântica e responsiva, a partir de uma estrutura básica pré-montada de um layout fornecido por [DIO](https://github.com/digitalinnovationone/trilha-css-desafio-01).

## ✨ Funcionalidades Implementadas

*   **Estrutura Semântica (HTML5):** Uso correto de tags como `<header>`, `<main>`, `<section>`, `<img>` e `<button>` para criar um documento bem estruturado e acessível.
*   **Design Responsivo (Mobile First):** O layout é projetado primeiro para dispositivos móveis e aprimorado para telas maiores (`desktop`) através de Media Queries.
*   **Layout Avançado com CSS Flexbox:** Utilização de `display: flex` para o alinhamento de componentes internos.
*   **CSS Moderno:** Emprego de Pseudo-elementos CSS (`::before`) para um design consistente e de fácil manutenção e seletores avançados.

## 🛠️ Tecnologias e Ferramentas Utilizadas

Este projeto foi construído com uma combinação de tecnologias de codificação e uma metodologia de desenvolvimento assistida por IA.

### Linguagens
*   **HTML5:** Para a estruturação e semântica do conteúdo.
*   **CSS3:** Para estilização, layout e responsividade.

### Design
*   **Figma e Penpot** Utilizados para visualizar o protótipo da *landing page*, que foi disponibilizado pela professora do curso.

### Metodologia e Processo de Desenvolvimento

* **DIO - Digital Innovation One:** Plataforma de *tech education* que tem como pilares fundamentais: comunidade e colaboração, social learning e educação imersiva e gamificada.

*   **Google AI Studio (Gemini):** A plataforma foi utilizada não como uma ferramenta de geração de código, mas como um **mentor de desenvolvimento personalizado**. Através de uma abordagem socrática, o agente foi instruído a não fornecer respostas prontas, mas a guiar o raciocínio com perguntas, analogias e a explicação de conceitos fundamentais de design em CSS. Essa metodologia foi crucial para superar os desafios de forma autônoma e consolidar o aprendizado.

## 🚀 Desafios e Aprendizados

O desenvolvimento deste projeto foi uma jornada de aprendizado prático, superando desafios comuns no desenvolvimento web:

1.  **Layout Responsivo Complexo:** A transição de um layout em html puro para sua versão estilizada com CSS exigiu um entendimento profundo de Flexbox, `::before` e o uso de camadas para que o elemento filho não herdasse a propriedade de transparência definia para o elemento pai.

2.  **Gerenciamento de Espaçamento:** O debate entre `margin` e `padding` vs `gap` para o espaçamento de componentes foi um aprendizado chave, especialmente para evitar "lacunas" indesejadas ao aplicar cores de fundo.

3.  **Cores de Elementos com `radial-gradient` e `linear-gradient` :** A edição do estilo de cor do elemento `header` fornecida no protótipo do Figma foi um desafio bastante relevante. Pois a mesma estava definida com um gradiente linear, mas a tentativa de configurar uma gradiente linear em CSS com esses dados se mostrou insuficiente para alcançar ou se aproximar do resultado esperado. A solução, mais adequada, envolveu o uso em conjunto dos dois gradientes (linear e radial) disponíveis no CSS para simular um efeito hiperbólico, onde (ao longo da horizontal) a cor central (um tom de azul) se move (como se fosse uma onda formada por retas paralelas, os "braços" da hipérbole, e não círculos radias) para as bordas de cima e de baixo criando o efeito próximo do desejado. Esse efeito foi obtido criando um elipse muito larga e muito achatada para ocupar a vertical do elemento e se alargar para fora das laterais dele.

## 📂 Como Visualizar o Projeto

1.  Clone este repositório:
    ```bash
    git clone https://github.com/Naygno/Landing-Page-01.git
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd Landing-Page-01
    ```
3.  Abra o arquivo `index.html` no seu navegador de preferência.

## 👤 Autor

**Naygno Barbosa NOia**

*   **LinkedIn:** www.linkedin.com/in/naygno
*   **GitHub:** https://github.com/Naygno

---
*Este projeto é parte da Formação CSS Web Developer da DIO. Todos os direitos de conteúdo e marcas mencionadas pertencem aos seus respectivos proprietários.*

