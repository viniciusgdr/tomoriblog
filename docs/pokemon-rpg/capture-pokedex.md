---
sidebar_position: 2
---

# Captura e Pokedex

## Capturando Pokemon

Use `/captura` (aliases: `catch`, `capturar`) para encontrar e capturar Pokemon selvagens.

```
/captura
```

### Como funciona

1. O bot sorteia um Pokemon da sua regiao atual
2. O spawn e ponderado por **raridade** e **taxa de captura**
3. Existe influencia do **ciclo dia/noite**:
   - Pokemon tipo Ghost tem bonus de aparicao a noite
   - Pokemon tipo Bug tem bonus de aparicao de dia

### Limites

| Recurso | Limite |
|---------|--------|
| Encontros | 5 a cada 30 minutos |

Cada captura consome 1 Pokebola do seu inventario. Compre mais na `/loja`.

## Pokedex

Use `/pokedex` (aliases: `dex`, `progresso`, `status`) para ver suas estatisticas de captura.

```
/pokedex
```

### O que mostra

- Total de Pokemon capturados (unicos) vs total disponivel
- Progresso geral em porcentagem
- Regiao atual
- **Progresso na regiao atual**: X/Y capturados com barra visual
- Lista de Pokemon que faltam capturar na regiao

:::info
Pokemon iniciais e lendarios sao excluidos do calculo de progresso geral.
:::

### Exemplo de saida

```
Pokedex: 45/150 (30%)
Regiao Atual: Kanto

Progresso na Regiao: 12/30 (40%)
[████████░░░░░░░░░░░░] 40%

Faltam: Pidgey, Rattata, Spearow...
```
