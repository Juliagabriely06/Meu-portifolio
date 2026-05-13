# 🗂️ Portfólio Pessoal — Júlia Gabrielly

> *"Desenvolvimento com Propósito"*

Portfólio pessoal desenvolvido com **HTML5 e CSS3 puro**, sem frameworks ou bibliotecas externas. O projeto apresenta minha trajetória, stack tecnológica e projetos desenvolvidos na intersecção entre tecnologia e educação.

---

## 🔗 Acesse o projeto

[![Ver Portfólio](https://img.shields.io/badge/Ver%20Portfólio-0f172a?style=for-the-badge&logo=github)](https://juliagabriely06.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julia-gabrielly-0381933a61)

---

## 📸 Visão Geral

O site é uma **single-page application (SPA)** composta por quatro seções navegáveis:

| Seção | Descrição |
|---|---|
| 🏠 **Início** | Hero com título animado e chamada para ação |
| 👩‍💻 **Sobre** | Apresentação pessoal, formação acadêmica e stack |
| 🚀 **Projetos** | Cards com os principais projetos desenvolvidos |
| 📬 **Contato** | Links para GitHub, LinkedIn e e-mail |

---

## 🛠️ Tecnologias Utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

O projeto foi construído **apenas com HTML5 e CSS3**, sem uso de JavaScript, Bootstrap, Tailwind ou qualquer outra biblioteca. Todas as animações, responsividade e efeitos visuais foram implementados com CSS puro.

---

## ✨ Funcionalidades e Técnicas

### Layout & Estrutura
- **HTML5 semântico** — uso correto de `<header>`, `<main>`, `<section>`, `<footer>` e `<nav>`
- **Flexbox** para alinhamento e distribuição dos elementos
- **CSS Grid** na grade de projetos (`grid-template-columns: repeat(auto-fit, minmax(...))`)
- **One-page navigation** com âncoras e `scroll-behavior: smooth`

### Visual
- Header fixo com `backdrop-filter: blur()` e fundo semitransparente
- Seção hero com fundo em `radial-gradient` e paleta azul marinho
- Seção "Sobre" com fundo em `linear-gradient` e pseudo-elemento `::before` como overlay
- Cards de projeto com efeito `translateY` e `box-shadow` no hover
- Tags de tecnologia estilizadas com `border-radius` e hover interativo

### Animações (CSS puro)
- `@keyframes fadeInUp` — entrada suave com desvanecimento e subida
- Classes `.fade-up`, `.fade-in-delay` e `.fade-in-delay-2` com `animation-delay` em cascata para entrada escalonada dos elementos
- `@keyframes pulsar` — efeito de pulso no botão principal, pausado automaticamente durante o hover via `:not(:hover)` para evitar conflito de `transform`

### Responsividade
- **Media query `max-width: 900px`** — ajustes para tablets
- **Media query `max-width: 768px`** — menu oculto, título reduzido, botões em largura total e cards em coluna única

---

## 📁 Estrutura de Arquivos

```
portfolio/
├── index.html      # Estrutura completa da página
└── style.css       # Todos os estilos, animações e media queries
```

---

## 🎨 Paleta de Cores

| Papel | Cor | Hex |
|---|---|---|
| Fundo escuro principal | Azul marinho | `#0f172a` |
| Fundo secundário | Azul escuro | `#1e293b` |
| Destaque / acento | Azul claro | `#38bdf8` |
| Texto principal | Branco suave | `#f1f5f9` |
| Texto secundário | Cinza azulado | `#94a3b8` |

---

## 🚀 Como rodar localmente

Não é necessário instalar nada. Basta clonar o repositório e abrir o arquivo no navegador:

```bash
git clone https://github.com/juliagabriely06/portfolio.git
cd portfolio
# Abra o index.html no seu navegador
```

Ou, se quiser um servidor local simples com o VS Code, instale a extensão **Live Server** e clique em *"Open with Live Server"*.

---

## 📚 Contexto Acadêmico

Este projeto foi desenvolvido durante minha formação dupla em:

- **Análise e Desenvolvimento de Sistemas (ADS)** — CESMAC
- **Pedagogia** — UFAL

Reflete meu interesse em unir tecnologia e educação, criando interfaces acessíveis e bem estruturadas.

---

## 📬 Contato

- **GitHub:** [github.com/juliagabriely06](https://github.com/juliagabriely06)
- **LinkedIn:** [linkedin.com/in/julia-gabrielly](https://www.linkedin.com/in/julia-gabrielly-0381933a61)
- **E-mail:** gabriellyjulia0604@gmail.com

---

<p align="center">Desenvolvido com 💙 e propósito por <strong>Júlia Gabrielly</strong></p>
