---
sidebar_position: 4
---

# Sistema de XP

O TomoriBOT possui um sistema de experiencia (XP) que recompensa a participacao nos grupos.

:::info
Para usar o sistema de XP, o administrador precisa ativar **"Modo de XP, Level, Rank e Diversao"** nas [Ativacoes do grupo](../how-to-use/advanced-settings).
:::

## Como ganhar XP

| Atividade | XP |
|-----------|----|
| Enviar mensagens no grupo | Variavel |
| Vencer batalhas Pokemon PvP | Variavel |
| Vencer batalhas Pokemon NPC | Variavel |
| Acertar no Quem Santo | +1 |
| Participar de jogos | Variavel |

## Niveis

Conforme voce acumula XP, seu nivel sobe. Niveis mais altos desbloqueiam:

- Acesso a **regioes Pokemon** com nivel minimo
- Maior visibilidade no **ranking**
- Status no **perfil**
- Isencao de regras via [Acoes Condicionais](../how-to-use/actions)

## Rankings

### Ranking de XP

```
/ranking
```

Mostra os membros com mais XP no grupo. Aliases: `rank`, `rank-xp`, `ranking-xp`.

### Ranking de mensagens

```
/ranking-mensagens
```

Mostra os membros que mais enviaram mensagens. Aceita numero de posicoes como argumento (ex: `/ranking-mensagens 100`). Aliases: `rank-mensagens`, `ranking-msg`, `rank-msg`.

### Top 10 menos ativos

```
/t10menosmsg
```

Lista os 10 membros que menos enviaram mensagens. Util para limpar grupos.

## Perfil

Use `/perfil` para ver todas as suas estatisticas:

```
/perfil
/perfil @usuario
```

O perfil exibe:
- Nivel e XP atual
- Total de mensagens enviadas
- Saldo de Cash
- Pokemon capturados
- Emblemas e badges conquistados
- Posicao no ranking

## Top ricos

```
/topricos
```

Ranking dos membros com mais Cash no grupo.

## Configuracao

O administrador pode configurar o sistema de XP e niveis pelo [painel de controle](https://tomoribot.com.br/dashboard), na aba de **Ativacoes** do grupo.
