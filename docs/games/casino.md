---
sidebar_position: 1
---

# Jogos de Casino

Jogos de aposta que usam Cash do sistema de economia do bot.

## Blackjack (/21)

O classico jogo de 21. Tente chegar o mais proximo de 21 sem passar.

**Aliases:** `blackjack`, `blackjack21`, `jogo21`

```
/21
```

### Regras

- Baralho completo de 52 cartas
- Ases valem 1 ou 11
- Cartas de face (J, Q, K) valem 10
- Voce joga contra o dealer
- Ganhou = recebe o dobro da aposta
- Blackjack natural = bônus extra

### Acoes

Apos receber suas cartas, voce pode:
- **Hit** - Pedir mais uma carta
- **Stand** - Manter suas cartas
- **Double** - Dobrar a aposta e receber uma carta

---

## Doubles

Jogo inspirado no Doubles da Blaze, sincronizado em tempo real.

```
/doubles <cor> <valor>
```

### Cores e multiplicadores

| Cor | Multiplicador |
|-----|---------------|
| Vermelha | 2x |
| Preta | 2x |
| Branca | 14x |

### Exemplo

```
/doubles vermelha 100
```

Aposta 100 Cash no vermelho. Se acertar, recebe 200.

---

## Apostas (/bet)

Sistema de apostas gerenciado pelo administrador do grupo.

**Aliases:** `apostas`, `apostar`

```
/bet
/bet historico
/bet cancelar 1
```

| Sub-comando | Funcao |
|-------------|--------|
| `/bet` | Ver jogos/apostas disponiveis |
| `/bet historico` | Ver historico de apostas |
| `/bet cancelar [n]` | Cancelar uma aposta |

Os administradores criam as apostas pelo painel, definindo as opcoes de aposta. Os membros do grupo participam usando o comando `/bet` e escolhendo a opcao desejada.

:::info
Os jogos de casino utilizam **Cash** do sistema de economia. Voce pode ver seu saldo com `/perfil` e ganhar Cash participando de atividades no grupo.
:::
