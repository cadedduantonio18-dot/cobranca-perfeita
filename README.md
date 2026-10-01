# ⚽ Cobrança Perfeita 3D

Jogo de **pênaltis e faltas em 3D** que roda direto no navegador, feito com [Three.js](https://threejs.org/).

## Modos

- **Pênaltis** — 5 cobranças contra o goleiro.
- **Faltas** — 10 cobranças de distâncias e ângulos aleatórios, com barreira que pula e goleiro. Gol vale 100 pts, +50 no ângulo, +25 com efeito.
- Goleiro em três dificuldades: **Fácil**, **Normal** e **Difícil**. Recordes salvos no navegador.

## Como jogar

| Ação | Controle |
|---|---|
| Mirar | Mouse (ou toque) |
| Carregar a força | Segurar o clique ou `Espaço` — solte na hora certa |
| Efeito (curva) | `A` / `D`, setas ou roda do mouse |
| Menu | `Esc` |

Força no vermelho = isolou. Na falta, chute mais leve e mais alto pra passar por cima da barreira.

## Rodar localmente

É um único arquivo, `index.html`. Abra com qualquer servidor estático, por exemplo:

```bash
python -m http.server 8000
```

e acesse `http://localhost:8000`. Precisa de internet para carregar o Three.js pela CDN.
