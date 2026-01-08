
---

# 🌌 NEON VOID: UNDERTALE TRIBUTE

![Status](https://img.shields.io/badge/Status-Complete-brightgreen) ![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20JS%20%7C%20Canvas-blue) ![License](https://img.shields.io/badge/License-MIT-purple)

> **Um Space Shooter de Sobrevivência "Bullet Heaven" desenvolvido em um único arquivo HTML.**

Este projeto foi criado como parte de um **Desafio Criativo de Desenvolvimento Web**, com o objetivo de construir um jogo completo, performático e visualmente impactante sem o uso de bibliotecas externas ou assets de imagem/áudio. Tudo é gerado via código.

---

## 🎮 Sobre o Jogo

**NEON VOID** coloca o jogador no controle de uma nave experimental no vácuo do espaço. O objetivo é sobreviver a ondas infinitas de inimigos cibernéticos, coletar dados (XP) e evoluir seus sistemas.

Nesta versão **Undertale Tribute**, o jogo conta com uma trilha sonora procedural inspirada em *Megalovania*, gerada em tempo real pelo navegador.

### ✨ Destaques
*   **Zero Assets Externos:** Não há imagens (.png) ou sons (.mp3). Todos os gráficos são desenhados via HTML5 Canvas e todos os sons são sintetizados via Web Audio API.
*   **Roguelite Progression:** Suba de nível e escolha entre upgrades aleatórios (armas, atributos, habilidades passivas).
*   **Trilha Sonora Procedural:** Um sequenciador de áudio interno toca música estilo 8-bit dinamicamente.
*   **Visual Neon Retro:** Efeitos de partículas, *bloom*, aberração cromática (glitch) e *screen shake*.
*   **Sistema de Física:** Inimigos com comportamentos distintos (Kamikazes, Snipers, Tanks e Enxames).

---

## 🕹️ Como Jogar

O jogo roda diretamente no navegador. Não é necessária instalação.

### Controles

| Tecla / Ação | Função |
| :--- | :--- |
| **W, A, S, D** | Movimentar a nave |
| **Mouse** | Mirar (A mira segue o cursor) |
| **Clique (Segurar)** | Atirar (Metralhadora Principal) |
| **ESC** | Pausar / Abrir Configurações |

### Mecânicas
1.  **Destrua Inimigos:** Eles soltam orbes de XP.
2.  **Evolua:** Ao encher a barra de XP, o jogo pausa e oferece 3 cartas de upgrade.
3.  **Sobreviva:** A cada minuto, a onda de inimigos fica mais forte e numerosa.

---

## 🚀 Como Executar

1.  Baixe o arquivo `index.html` (ou o código final gerado).
2.  Clique duas vezes para abrir no seu navegador favorito (Recomendado: **Google Chrome** ou **Firefox** para melhor performance do Canvas).
3.  **Importante:** Clique na tela uma vez para permitir que o navegador inicie o contexto de áudio.

---

## 🛠️ Detalhes Técnicos

O projeto demonstra domínio de JavaScript puro (Vanilla JS) e lógica de desenvolvimento de jogos:

*   **Game Loop:** Utiliza `requestAnimationFrame` para renderização fluida a 60 FPS.
*   **Canvas API:** Uso avançado de `ctx.save()`, `ctx.restore()`, `globalCompositeOperation = 'lighter'` para efeitos de luz aditiva.
*   **Web Audio API:** Criação de osciladores (`OscillatorNode`) e controle de ganho (`GainNode`) para criar música e efeitos sonoros (tiros, explosões) matematicamente.
*   **State Management:** Sistema de estados para gerenciar Menus, Jogo Ativo, Pause e Game Over.
*   **POO (Programação Orientada a Objetos):** Classes separadas para `Player`, `Enemy`, `Projectile` e `Particle`.

---

## 📦 Conteúdo das Ondas (Inimigos)

*   🔴 **Swarm (Vermelho):** Fracos, mas vêm em grande número.
*   🟡 **Kamikaze (Amarelo):** Rápidos e explodem ao contato.
*   🟣 **Tank (Roxo):** Lentos, gigantes e com muita vida.
*   ⚪ **Sniper (Branco):** Mantêm distância e usam mira laser para disparar tiros rápidos.

---

## 🔮 Upgrades Disponíveis

*   🔫 **Rapid Fire:** Aumenta a cadência de tiro do canhão principal.
*   ♻️ **Saw Shield:** Serras orbitais que protegem a nave.
*   ⚡ **Auto Laser:** Raio que atinge automaticamente o inimigo mais próximo.
*   🩸 **Vampirism:** Chance de recuperar vida ao destruir inimigos.
*   🛡️ **Hull Upgrade:** Cura total e aumento de vida máxima.
*   🚀 **Thrusters:** Aumenta a velocidade de movimento.

---

## 📝 Créditos

*   **Desenvolvimento:** Miguel, Emanuel, Pedro Arthur
*   **Inspiração de Gameplay:** *Vampire Survivors*, *Geometry Wars*.
*   **Inspiração Musical:** *Undertale (Toby Fox)*.

---
- Equipe: Pedro Arthur, Miguel Sthevão, Emanuel Rodrigues

*Desafio Criativo – Desenvolvimento de Jogos Web*
