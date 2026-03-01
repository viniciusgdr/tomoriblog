---
sidebar_position: 7
---

# Comandos de Informacao

Comandos para consultar informacoes, rankings e perfis.

## /perfil

Exibe o perfil do usuario.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `profile` |
| **Permissao** | Todos |

**Uso:**
```
/perfil
/perfil @usuario
```

Mostra nivel, XP, mensagens, saldo e outras estatisticas.

O perfil exibe:
- Nivel e XP total
- Mensagens enviadas
- Saldo de Cash
- Pokemon capturados
- Emblemas e badges
- Posicao no ranking do grupo

---

## /ranking

Ranking de XP do grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `rank`, `rank-xp`, `ranking-xp` |
| **Permissao** | Todos |

**Uso:**
```
/ranking
```

Mostra os membros com mais XP no grupo.

---

## /ranking-mensagens

Ranking de mensagens do grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `rank-mensagens`, `ranking-msg`, `rank-msg` |
| **Permissao** | Todos |

**Uso:**
```
/ranking-mensagens
/ranking-mensagens 100
```

O argumento numerico opcional filtra membros com menos de N mensagens.

---

## /t10menosmsg

Top 10 de quem menos enviou mensagens.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `top-10-menos-msgs`, `top10menosmsg` |
| **Permissao** | Todos |

**Uso:**
```
/t10menosmsg
/t10menosmsg resumido
```

A versao "resumido" mostra formato compacto com mencoes. Versao completa inclui nivel, XP e data de entrada.

---

## /saldo

Consulta seu saldo de Cash.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `cash` |
| **Permissao** | Todos |

**Uso:**
```
/saldo
```

---

## /transferir

Transfere Cash para outro usuario.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `cash` |
| **Permissao** | Todos |

**Uso:**
```
/transferir @usuario 500
```

---

## /topricos

Ranking dos mais ricos do grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/topricos
```

---

## /aniversario

Gerencia aniversarios no grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `aniversario` |
| **Permissao** | Todos |

**Uso:**
```
/aniversario
```

Mostra proximos aniversarios do grupo. Aniversarios podem ser configurados pelo painel ou pelo bot.

---

## /wallpaper

Busca papeis de parede.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `wp`, `papeldeparede`, `papel-de-parede` |
| **Permissao** | Todos |

**Uso:**
```
/wallpaper natureza
/wp anime dark
```

---

## /rab

Consulta ao Registro Aeronautico Brasileiro (ANAC).

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/rab PR-YJF
/rab PTMAY
```

Busca informacoes de uma aeronave pela matricula (5-6 caracteres). Retorna: proprietario, fabricante, modelo, ano, peso maximo de decolagem, numero de passageiros, categoria de registro, status de operacao, situacao de aeronavegabilidade e mais.
