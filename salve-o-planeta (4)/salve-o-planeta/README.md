# 🌱 Salve o Planeta — Agrinho 2026

Jogo educativo em **HTML, CSS e JavaScript puros** (Canvas API), recriando o projeto original em versão sem framework.

## ▶️ Como rodar

1. **Extraia o .zip** (não abra direto de dentro do zip!)
2. Entre na pasta `salve-o-planeta`
3. Dê **duplo clique em `index.html`** — abre no navegador, sem instalar nada

## 🎮 Como jogar

- ⬆️ ⬇️ (ou W/S) — no celular, toque e arraste para mover o herói 🦸
- Colete itens bons: ♻️ 💧 🌱 🍃 (ganha pontos e moedas)
- Desvie da poluição: 🔥 ☠️ 🛢️ ☣️ 🏭 (perde vida)
- Atinja a meta antes do tempo acabar para passar de fase
- São **10 fases**, cada uma mais rápida que a anterior
- Tecla **Espaço** ou **P** para pausar

## 🛠️ Tecnologias

- HTML5 (estrutura)
- CSS3 (estilo, animações, responsivo)
- JavaScript (lógica do jogo)
- Canvas API (renderização)
- localStorage (salva as moedas)

## 📁 Estrutura

```
salve-o-planeta/
├── index.html
├── style.css
├── script.js
└── README.md
```

## ✅ Conceitos aplicados

- Colisão (detecção entre herói e itens)
- Pontuação e moedas
- Cronômetro (40s por fase)
- 10 fases com dificuldade crescente
- Sistema de vidas (3 por fase)
- Loop de jogo com `requestAnimationFrame`

**100% autoral.** Visual desenhado via Canvas (sol, montanhas, árvores, rio, nuvens) — sem imagens externas, apenas emojis Unicode.
