---
sidebar_position: 5
---

# Economia e Trocas

O RPG Pokemon possui um sistema completo de economia com Cash, loja, mercado de trocas e Wonder Trade.

## Inventario

Use `/inventario` (aliases: `inventory`, `pokemon`, `meus`) para gerenciar seus Pokemon.

```
/inventario
```

### O que mostra

- Pokemon na Party (time ativo)
- Pokemon no PC (armazenamento)
- Quantidade de Pokebolas
- Nivel maximo atingido
- Insignias conquistadas

### Trocar Pokemon entre Party e PC

```
/inventario trocar 3 7
```

Move o Pokemon da posicao 3 da Party para a posicao 7 do PC (e vice-versa).

---

## Loja

Use `/loja` (aliases: `store`, `comprar`) para comprar itens.

```
/loja
```

### Itens padrao

| Item | Preco |
|------|-------|
| 1 Pokebola | 50 Cash |
| 5 Pokebolas | 230 Cash |
| 10 Pokebolas | 450 Cash |
| Rare Candy | 500 Cash |

### Comprar

```
/loja buy 1
```

Admins do grupo podem adicionar itens personalizados via painel web.

---

## Mercado de Trocas

### Ver mercado

Use `/banco` (aliases: `mercado`, `market`, `trade`) para listar Pokemon disponiveis para troca.

```
/banco
```

Mostra nome do Pokemon, nivel e quem doou.

### Realizar trocas

Use `/trocarbanco` (aliases: `trademarket`, `comprar`, `vender`):

```
/trocarbanco pegar 3
/trocarbanco doar 5
/trocarbanco cancelar 2
```

| Acao | Comando |
|------|---------|
| Pegar Pokemon | `/trocarbanco pegar [numero_do_mercado]` |
| Doar Pokemon | `/trocarbanco doar [numero_do_inventario]` |
| Cancelar doacao | `/trocarbanco cancelar [numero_do_mercado]` |

**Limite:** 2 trocas gratuitas por dia.

---

## Wonder Trade

Use `/wondertrade` (aliases: `wt`, `wonder`) para trocar um Pokemon por outro aleatorio.

```
/wondertrade 3
```

O numero corresponde a posicao do Pokemon no inventario (use `/inventario` para ver).

### Regras

- **1 troca por dia** (cooldown 24h)
- O Pokemon recebido tera nivel similar ao enviado
- E necessario estar em uma regiao
- A troca e irreversivel

---

## Saldo e Transferencias

### Consultar saldo

```
/saldo
```

### Transferir Cash

```
/transferir @usuario 500
```

### Como ganhar Cash

| Atividade | Cash |
|-----------|------|
| Vencer batalhas PvP e NPC | Variavel |
| Acertar no jogo da forca | +100 |
| Acertar no anagrama | Variavel |
| Abrir baus (`/bau`) | Aleatorio (+/-) |
| Acertar no jogo do espelho | +100 |
| Errar no jogo do espelho | -80 |

## Loja personalizada do grupo

Administradores podem criar itens personalizados na [Loja do Grupo](../how-to-use/store) pelo painel de controle. Membros compram itens com Cash e podem ganhar emblemas (badges) que aparecem no perfil.

## Substituir Pokemon

```
/substituir <posicoes>
```

Substitui Pokemon do inventario por um novo aleatorio. As posicoes correspondem aos numeros do `/inventario`.
