---
sidebar_position: 3
---

# Batalhas

O sistema de batalha permite enfrentar outros jogadores (PvP) e NPCs da sua regiao.

## Batalha PvP

Use `/batalha` (aliases: `battle`, `pvp`) para desafiar outro jogador.

```
/batalha @oponente
```

### Regras

- Batalha 6x6 (time completo)
- Usa os atributos: HP, Attack, Defense, Speed e CP
- Nao pode batalhar contra si mesmo
- **Limite:** 40 batalhas por dia

### Recompensas

Vitorias concedem XP e Cash proporcionais ao nivel do oponente.

---

## Batalha NPC

Use `/batalha-npc` (aliases: `battle-npc`, `npcbattle`, `batalhanpc`) para enfrentar NPCs da sua regiao.

```
/batalha-npc
```

### Dificuldades

| Dificuldade | Forca do NPC | Multiplicador |
|-------------|-------------|---------------|
| Facil | 75-82% | 0.8x |
| Medio | 82-88% | 1.0x |
| Dificil | 88-100% | 1.2x |

- **Limite:** 30 batalhas NPC por dia
- Voce precisa estar em uma regiao para batalhar

### Recompensas

XP e Cash baseados na dificuldade escolhida. Dificuldade mais alta = mais recompensa.

---

## Cooldowns

Use `/tempo` (aliases: `cooldown`, `cd`) para verificar seus tempos de espera:

```
/tempo
```

Mostra contagem regressiva para:
- Captura (5 encontros a cada 30 min)
- Trocas gratuitas (2 por dia)
- Batalhas (40 PvP + 30 NPC por dia)
