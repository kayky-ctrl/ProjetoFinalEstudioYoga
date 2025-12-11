# 🧘‍♀️ Estúdio Serenidade - Website Institucional

> "Descubra o equilíbrio entre o corpo e mente."

## 📋 Sobre o Projeto

Este projeto consiste no desenvolvimento de um website responsivo para o **Estúdio Serenidade**, um novo espaço de Yoga localizado no bairro da Graça, em Salvador/BA. 

O site foi criado atendendo ao **Projeto 6 (Desafio de Front-End)**, com o objetivo de apresentar as modalidades, exibir a grade de horários e captar novos alunos através do agendamento de aulas experimentais.

## 🎯 Cenário e Objetivos

**Cliente:** Sofia Pereira, instrutora certificada há 10 anos.
**Situação:** Inauguração de um novo estúdio que busca ser um oásis urbano.
**Objetivo do Site:**
1.  Apresentar o estúdio e a filosofia de bem-estar.
2.  Detalhar as modalidades oferecidas (Hatha Yoga, Vinyasa Flow).
3.  Disponibilizar a grade de horários semanal.
4.  Captar leads através de um formulário de "Aula Experimental Gratuita".

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico:** Uso correto de tags como `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>` e `<table>`.
* **CSS3:**
    * **Mobile First:** Desenvolvimento focado inicialmente em dispositivos móveis.
    * **Flexbox & Grid:** Para layout de cards e formulários.
    * **Media Queries:** Para adaptação responsiva em Tablets e Desktops.
    * **Variáveis CSS (`:root`):** Para gerenciamento consistente de cores e fontes.
* **Fontes:** Google Fonts (*Playfair Display* para títulos e *Roboto* para corpo).
* **Ícones:** Font Awesome.

## 📂 Estrutura do Projeto

O projeto é composto por 3 páginas principais interligadas:

1.  **`index.html` (Home):**
    * Hero section com imagem de impacto.
    * Apresentação dos benefícios da prática do Yoga.
    * Chamadas para ação (CTA).
2.  **`modalidades.html`:**
    * Detalhamento das práticas (Vinyasa Flow e Hatha Yoga).
    * Design em cards intercalados (texto/imagem).
3.  **`aulaExperimental.html`:**
    * Formulário de cadastro com validação HTML5.
    * Tabela (`<table>`) responsiva com a grade de horários das aulas.

## 🎨 Identidade Visual

O design segue uma linha "Zen", priorizando a calma e a leitura agradável.

* **Paleta de Cores:**
    * 🟢 **Verde Sálvia (`#5a7d68`):** Cor primária, remetendo à natureza e equilíbrio.
    * 🔵 **Azul Suave (`#f0f6ff`):** Fundo das páginas, trazendo leveza.
    * 🍑 **Pêssego (`#ffeadd`):** Detalhes orgânicos e formas de fundo.
    * ⚫ **Cinza Escuro (`#2c3e50`):** Rodapés e contrastes.
* **Tipografia:**
    * *Playfair Display (Serif):* Elegância e sofisticação nos títulos.
    * *Roboto (Sans-serif):* Legibilidade moderna para textos longos.

## 📱 Responsividade

O site foi desenhado seguindo a técnica **Mobile First**:
* **Mobile:** Layout em coluna única, menu simplificado e elementos empilhados.
* **Desktop (`min-width: 768px`):** O layout se expande, utilizando o espaço lateral para colocar imagens ao lado de textos e o menu torna-se horizontal.

## 🚀 Como Executar

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/kayky-ctrl/ProjetoFinalEstudioYoga.git](https://github.com/kayky-ctrl/ProjetoFinalEstudioYoga.git)
    ```
2.  Abra a pasta do projeto no VS Code.
3.  Abra o arquivo `index.html` no seu navegador ou utilize a extensão **Live Server**.

## 📄 Requisitos Técnicos Atendidos

- [x] HTML5 Semântico.
- [x] CSS Externo com design "clean".
- [x] Layout Responsivo (Media Queries).
- [x] Uso de `<table>` estilizada para os horários.
- [x] Formulário de Agendamento com checkboxes e inputs adequados.
- [x] Acessibilidade (Contraste de cores e estrutura lógica).

---
Desenvolvido por **kayky & André Jacobino** como parte do desafio de Front-End.