# ⚽ Cobrança Perfeita 3D

Jogo de futebol em 3D que roda direto no navegador, feito com [Three.js](https://threejs.org/): pênaltis, faltas, disputa contra o bot, jogadas 3 contra 3 e um modo história com 40 fases.

## Modos

- **🏝️ Ilhas** — 10 ilhas com 4 fases cada (40 no total), cada uma com cenário próprio. Ganhe até 3 estrelas por fase; vencer o chefe libera a próxima ilha e um item exclusivo. Fases mais avançadas têm vento e dificuldade Lendária.
- **🥅 Pênaltis** — 5 cobranças contra o goleiro.
- **🎯 Faltas** — 10 cobranças com barreira (às vezes com "jacaré" deitado atrás) e goleiro. Gol vale 100 pts, +50 no ângulo, +25 com efeito.
- **⚔️ 1 contra 1** — disputa de pênaltis contra o bot: você bate e depois defende. 5 para cada, depois morte súbita.
- **⚡ Jogada** — 3 contra 3 + goleiro: drible, toque para o seu time e finalize. Gol vale 3 pontos + 1 por passe.

Dificuldade **Fácil**, **Médio** ou **Difícil** (moedas ×1, ×1,5 e ×2). Recordes e progresso ficam salvos no navegador.

## Vestiário

Personalize o jogador com moedas ganhas nas partidas: uniformes (inclusive listrados), número, chuteiras, cabelo e cor do cabelo, bola e comemorações de gol. Perfil grátis: pé (destro/canhoto), corpo (masculino/feminino) e tom de pele.

## Como jogar

| Ação | Controle |
|---|---|
| Mirar | Mouse (ou toque) |
| Carregar a força | Segurar o clique ou `Espaço` — solte na hora certa |
| Efeito (curva) | `A` / `D`, setas ou roda do mouse |
| Pular no gol (1 contra 1) | Mirar e clicar (ou `Espaço`) |
| Jogada 3x3 | `WASD` corre, `Shift` arranca, `E` ou botão direito passa, segure o clique pra chutar |
| Menu | `Esc` |

Força no vermelho = isolou. Na falta, chute mais leve e mais alto pra passar por cima da barreira.

## Rodar localmente

É um único arquivo, `index.html`. Abra com qualquer servidor estático, por exemplo:

```bash
python -m http.server 8000
```

e acesse `http://localhost:8000`. Precisa de internet para carregar o Three.js pela CDN.
