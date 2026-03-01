---
sidebar_position: 1
---

# Comandos de Grupo

Comandos para administracao e moderacao de grupos do WhatsApp. A maioria exige que o bot seja admin do grupo.

## /anunciar

Anuncia uma mensagem no grupo marcando todos os membros com mencao oculta.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `marcar`, `mencionar` |
| **Permissao** | Admin |
| **Bot Admin** | Sim |

**Uso:**
```
/anunciar <mensagem>
/anunciar (respondendo imagem/video)
```

Marca ate 255 membros por mencao oculta. Suporta texto, imagem e video. Verifica NSFW automaticamente em imagens.

---

## /anunciar-comunidade

Anuncia uma mensagem em todos os subgrupos da comunidade.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |
| **Bot Admin** | Sim |

**Uso:**
```
/anunciar-comunidade <mensagem>
/anunciar-comunidade (respondendo midia)
```

Itera por todos os subgrupos com premium ativado. Verifica NSFW.

---

## /tagall

Anuncia uma mensagem com mencoes **visiveis** de todos os membros.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Admin |
| **Bot Admin** | Sim |

**Uso:**
```
/tagall (com texto ou respondendo midia)
```

Diferente do `/anunciar`, as mencoes (@) ficam visiveis no corpo da mensagem. Limite de 355 mencoes.

---

## /banir

Bane um membro do grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `ban` |
| **Permissao** | Admin |
| **Bot Admin** | Sim |

**Uso:**
```
/ban @usuario
/ban @usuario motivo do ban
/ban (respondendo a mensagem do usuario)
```

Nao pode banir o dono do grupo, o bot ou outros admins. Suporta motivo opcional.

---

## /antighost

Lista membros inativos do grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `ghosts`, `ghost` |
| **Permissao** | Admin |
| **Bot Admin** | Sim |

**Uso:**
```
/antighost
/antighost 14
```

O argumento opcional define o numero minimo de dias de inatividade (padrao: 7). Lista membros com mencao e quantidade de dias inativos.

---

## /grp

Abre ou fecha o grupo (toggle).

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `open`, `close`, `abrirgrp`, `fechargrp` |
| **Permissao** | Admin |
| **Bot Admin** | Sim |

**Uso:**
```
/grp
```

Se o grupo esta aberto, fecha. Se esta fechado, abre.

---

## /linkgrp

Retorna o link de convite do grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `gplink`, `linkgp`, `linkgrupo`, `linkgrup` |
| **Permissao** | Todos |
| **Bot Admin** | Sim |

**Uso:**
```
/linkgrp
```

---

## /regras

Exibe as regras do grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `regra` |
| **Permissao** | Todos |
| **Bot Admin** | Nao |

**Uso:**
```
/regras
```

Mostra regras personalizadas configuradas no painel. Se nao houver regras definidas, exibe a descricao do grupo.

---

## /moderador

Adiciona ou remove moderadores do bot.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Admin |
| **Bot Admin** | Sim |

**Uso:**
```
/moderador adicionar @usuario
/moderador remover @usuario
```

Moderadores do bot podem usar comandos de admin sem serem admin do WhatsApp.

---

## /del

Deleta mensagens do grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `apagar`, `deletar` |
| **Permissao** | Admin |
| **Bot Admin** | Sim |

**Uso:**
```
/del (respondendo a mensagem a ser deletada)
```

Deleta mensagens recentes do usuario mencionado.
