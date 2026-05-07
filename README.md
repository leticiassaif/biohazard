# ☣ biohazard

uma visual novel de terror baseada no prólogo de *Resident Evil 7: Biohazard*

> *"Welcome to the family, son!"*

Atividade extra de Algoritmos I.

## Sobre o Projeto

Uma visual novel (fan-made) inspirada em *Resident Evil 7*. O jogador assume o papel de **Ethan**, que chega em Dulvey, Louisiana em busca de sua esposa desaparecida, Mia. As escolhas ao longo da narrativa afetam atributos vitais e determinam qual dos múltiplos finais será alcançado.

### Atributos do Personagem

| atributo | valor inicial |
|----------|--------------|
| vida | 100 |
| coragem | 30 |
| sanidade | 100 |
| *segredo* | 0 |

## Finais Disponíveis

- `ending_true` — final verdadeiro, o desfecho canônico visto no jogo
- `ending_giveup` — Ethan "escuta" as palavras iniciais de Mia
- `ending_scared` — Ethan desiste de procurar Mia e volta para casa
- `ending_good_husband` — Ethan decide não atacar Mia de volta
- `ending_chainsaw` — Mia e sua motoserra

## Tech Stack

- **[Fable.js v2](https://github.com/topics/fablejs-v2)** — engine de narrativa interativa
- **[CodeFab v2](https://github.com/topics/codefab-v2)** — plataforma de hospedagem e execução

## Estrutura

```
biohazard/
├── assets/      # imagens, sons e recursos visuais
├── pages/       # cenas e páginas da narrativa
└── fable.xml    # estrutura principal — propriedades, cenas e fluxo
```

---
