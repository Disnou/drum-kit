# drum-kit
An interactive and responsive virtual drum kit built with HTML5, CSS3, and pure JavaScript (Vanilla JS).


# 🥁 Virtual JavaScript Drum Kit

[Clique aqui para ler em Português](#-versão-em-português) | [Click here to read in English](#-english-version)

---

## 🇧🇷 Versão em Português

Um kit de bateria interativo, responsivo e com visual moderno construído utilizando HTML5, CSS3 e JavaScript puro (Vanilla JS). O projeto captura os eventos de teclas físicas do teclado, reproduz o áudio correspondente de forma imediata e ativa efeitos visuais dinâmicos em tempo real com animações neon de impacto.

### 🚀 Funcionalidades
* **Resposta Sonora Imediata:** Controle de áudio que reseta o tempo de reprodução atual a cada clique (`currentTime = 0`), permitindo batidas rápidas e sem atrasos (delay).
* **Feedback Visual Dinâmico:** Animações fluidas no CSS que aumentam o tamanho das teclas (`transform: scale(1.1)`) e aplicam um brilho estilo "neon" customizado.
* **Layout Responsivo:** Centralização baseada em Flexbox combinado com um fundo imersivo de alta resolução adaptado para diferentes tamanhos de tela.

### 🛠️ Tecnologias Utilizadas
* **HTML5 Semântico:** Estruturação limpa do documento, uso de tags nativas `<audio>` e mapeamento de chaves físicas por meio de atributos customizados (`data-key`).
* **CSS3 Avançado:** Alinhamentos com Flexbox, efeitos de brilho com `box-shadow` na cor amarela dourada (`#ffc600`) e transições suaves (`transition: all 0.07s ease`).
* **JavaScript Puro (ES6+):** Captura de eventos globais do teclado (`window.addEventListener('keydown')`), manipulação dinâmica de classes do DOM (`classList`) e uso do evento `transitionend` para remover efeitos visuais de forma limpa.

---

## 🇺🇸 English Version

An interactive, responsive, and modern-looking virtual drum kit built using semantic HTML5, CSS3, and pure JavaScript (Vanilla JS). This web application captures physical keyboard events from the user, plays the corresponding sound immediately, and triggers dynamic visual feedback in real-time with polished neon effects and smooth animations.

### 🚀 Features
* **Instant Audio Response:** Advanced audio control that resets the playback timeline on every keystroke (`currentTime = 0`), allowing fast, repetitive, and lag-free drumming.
* **Dynamic Visual Feedback:** Fluid CSS transitions that scale buttons up (`transform: scale(1.1)`) and apply a customized glowing "neon" border when active.
* **Responsive Layout:** Clean layout alignment powered by Flexbox combined with an immersive high-resolution concert background that scales across multiple devices.

### 🛠️ Built With
* **Semantic HTML5:** Structured markup using native audio elements (`<audio>`) and hardware key mapping utilizing custom data attributes (`data-key`).
* **Advanced CSS3:** Layout positioning with Flexbox, outer glowing strokes using `box-shadow` in a golden yellow tone (`#ffc600`), and quick scaling transition curves (`0.07s ease`).
* **Pure JavaScript (ES6+):** Global window event listening targeting hardware triggers (`keydown`), dynamic DOM class manipulation, and animation synchronization using native lifecycle event hooks (`transitionend`).

---

## 📂 Estrutura do Projeto / Project Structure
├── drum.html    # Estrutura semântica e elementos de áudio / Markup and media sources
├── style.css    # Estilização completa e efeitos neon / Layout design and neon lighting
└── drum.js      # Lógica de controle de eventos e animações / Event listening logic

## 💻 Como Executar / How to Run

1. Abra o arquivo `drum.html` diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
2. Clique em qualquer lugar da página para focar e comece a tocar pressionando as teclas **A, S, D, F, G, H, J, K ou L** do seu teclado!
1. Open the `drum.html` file in any modern web browser.
2. Click anywhere on the webpage to focus and start playing by hitting the **A, S, D, F, G, H,
