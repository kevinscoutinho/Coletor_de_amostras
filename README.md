# Coletor de Amostras — Rota das Amostras

Jogo 2,5D no navegador: pilote uma pequena nave com jatos de ar comprimido (física newtoniana) e pouse em cada planeta para coletar amostras.

- Gravidade de cada planeta cai com o quadrado da distância, g(r) = gₛ·(R/r)², e só existe até 1,5 × o diâmetro (3 raios) a partir do centro.
- A gravidade age sobre a nave e as partículas (gás, poeira, destroços), nunca sobre os outros planetas.
- 5 setores, de 1 a 5 alvos cada.

## Como jogar

Abra `index.html` no navegador (precisa de internet para carregar o three.js e as fontes).

| Tecla | Ação |
|---|---|
| S | jato na base: empurra para onde o nariz aponta |
| W | jato no topo: empurra para trás |
| A / D | jatos laterais |
| Q / E | girar anti-horário / horário |
| C | abre o menu (jatos para toque e opções) |
| T | liga/desliga trajetória prevista |
| H | mostra/oculta os painéis |
| P / M / R / Esc | pausa / som / reiniciar / setores |

Pouso válido só com os pés: descida ≤ 2,5 m/s, deriva ≤ 1,5 m/s, inclinação ± 10°, rotação ≤ 15 °/s.
