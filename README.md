# 🧙‍♂️ RPG com Pygame — Premium Deluxe Master Edition

Bem-vindo ao projeto **RPG com Pygame**, uma aventura 2D desenvolvida em Python usando a biblioteca **Pygame**. Este jogo foi criado com foco em aprendizado, criatividade e diversão — e está em constante evolução!

## 🎮 Sobre o Jogo

Neste RPG 2D, o jogador explora um mundo cheio de NPCs, inimigos, batalhas e escolhas. Interaja com personagens, colete armas, poções e escudos, e enfrente desafios únicos enquanto avança na jornada.

### Principais Funcionalidades:

- 👾 Sistema de inimigos com atributos (vida, ataque, defesa, velocidade)
- 🧍‍♂️ NPCs interativos com menu de itens (espadas, poções, escudos)
- 🧠 Frases motivacionais após interações com NPCs
- 🎬 Animação de introdução em vídeo com som
- 💀 Tela de "Game Over"
- 💾 Estrutura modular com classes separadas (`player`, `npc`, `mapa`, etc.)

## 📂 Estrutura de Pastas

```bash
.
├── main.py                     # Arquivo principal do jogo
├── Roda_o_jogo.py             # Classe Game que gerencia a lógica principal
├── npc.py                     # Lógica dos NPCs
├── player_class.py            # Classe do jogador
├── mapa.py                    # Carregamento e lógica do mapa
├── frases_motivacionais.py   # Lista de frases motivacionais
├── graphics/                  # Recursos gráficos (sprites, vídeo de introdução, fontes)
│   ├── videointro.mp4
│   └── fonts/
│       └── PressStart2P-Regular.ttf
└── README.md
