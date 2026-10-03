# 🦖 Pixel-Yoshi Runner

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Um jogo de corrida infinita (*Endless Runner*) retrô em 2D desenvolvido inteiramente em **HTML5 Canvas** e **JavaScript puro (Vanilla)**, inspirado nos clássicos jogos de plataforma em pixel art.

---

## 🎮 Sobre o Jogo

Em **Pixel-Yoshi Runner**, o objetivo é ajudar o Yoshi a esquivar-se de obstáculos terrestres e aéreos enquanto corre por um cenário dinâmico. O jogo possui aceleração progressiva de velocidade, efeitos sonoros sintetizados via **Web Audio API** e suporte total para dispositivos móveis e desktop.

---

## ✨ Funcionalidades

- 🎨 **Estética Retro Pixel Art:** Renderização gráfica customizada em Canvas 2D sem dependência de bibliotecas ou engines externas.
- 📱 **Suporte Multiplataforma:** Totalmente responsivo com botões virtuais de toque na tela (*touch*) para telemóveis/celulares e suporte a teclado no PC.
- 🔊 **Efeitos Sonoros Integrados:** Gerador de som dinâmico via `Web Audio API` com suporte a fallback de áudios em MP3.
- 🏆 **Sistema de Recorde (High Score):** Armazenamento local automático via `localStorage` para salvar a melhor pontuação.
- 💥 **Sistema de Vidas e Partículas:** Efeitos visuais de explosão em partículas, tempo de invulnerabilidade e contador de vidas.
- 🚀 **Dificuldade Progressiva:** Aumento gradual da velocidade do jogo ao longo do tempo.

---

## 🕹️ Como Jogar

### **Controles no PC (Teclado):**
| Ação | Teclas |
| :--- | :--- |
| **Pular** | `Espaço` / `Seta para Cima (▲)` |
| **Agachar** | `Seta para Baixo (▼)` / `Tecla S` |
| **Iniciar / Reiniciar** | `Espaço` / `Seta para Cima (▲)` |

### **Controles no Celular / Tablet (Touch):**
- **Lado Esquerdo do Ecrã:** Botão **DUCK** (Agachar)
- **Lado Direito do Ecrã:** Botão **JUMP** (Pular)

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura da aplicação e renderização gráfica via elemento `<canvas>`.
- **CSS3:** Estilização responsiva com Flexbox e suporte a áreas seguras em ecrãs móveis (`safe-area-inset`).
- **JavaScript (ES6+):** Programação Orientada a Objetos (Classes `Yoshi`, `Obstacle`, `Cloud`, `Mountain`), ciclo de renderização `requestAnimationFrame` e algoritmo de colisão AABB (*Axis-Aligned Bounding Box*).
- **Web Audio API:** Sintetizador áudio para efeitos sonoros dinâmicos.
- **LocalStorage API:** Persistência do recorde máximo do jogador.

---

## 🚀 Como Executar o Projeto

Por ser um jogo construído numa arquitetura leve e nativa, não é necessária a instalação de dependências ou gestores de pacotes (`npm` / `yarn`).

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/pixel-yoshi-runner.git](https://github.com/seu-usuario/pixel-yoshi-runner.git)
   
