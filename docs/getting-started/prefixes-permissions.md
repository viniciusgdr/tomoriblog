---
sidebar_position: 2
---

# Prefixos e Permissoes

## Prefixo de comandos

O prefixo padrao do TomoriBOT e `/` (barra). Todos os comandos sao ativados digitando o prefixo seguido do nome do comando.

**Exemplo:** `/sticker`, `/play`, `/gpt`

### Prefixo personalizado

Voce pode alterar o prefixo no painel de controle do grupo. Prefixos comuns incluem `!`, `.`, `#`.

> Se o prefixo for alterado para `!`, os comandos passam a ser `!sticker`, `!play`, etc.

## Niveis de permissao

O TomoriBOT possui 3 niveis de permissao para comandos:

### Todos os usuarios

A maioria dos comandos pode ser usada por qualquer membro do grupo. Exemplos: `/sticker`, `/play`, `/gpt`, `/captura`.

### Admin do grupo

Comandos de moderacao exigem que o usuario seja **admin do grupo no WhatsApp**. Exemplos:

| Comando | Funcao |
|---------|--------|
| `/ban` | Banir membro |
| `/grp` | Abrir/fechar grupo |
| `/anunciar` | Mencionar todos |
| `/antighost` | Listar inativos |
| `/moderador` | Gerenciar moderadores do bot |

### Bot Admin

Alguns comandos exigem que o **bot seja admin** do grupo para funcionar. Isso e necessario para acoes que modificam o grupo (banir, alterar configuracoes, etc).

## Moderadores do bot

Alem dos admins do WhatsApp, o TomoriBOT tem um sistema proprio de "moderadores do bot". Esses usuarios podem executar comandos de admin sem serem admin do grupo.

Use `/moderador adicionar @usuario` para promover alguem.

## Aliases

Muitos comandos possuem aliases (nomes alternativos). Por exemplo:

- `/sticker` tambem funciona como `/stk`, `/s`, `/fig`, `/figurinha`
- `/play` tambem funciona como `/p`
- `/instagram` tambem funciona como `/ig`, `/igdl`
- `/gpt` tambem funciona como `/chatgpt`

Consulte a [lista de comandos](https://tomoribot.com.br/commands) para ver todos os aliases disponiveis.

## Modulos (desativar comandos por grupo)

Administradores podem desativar comandos individualmente em cada grupo pelo painel de controle. Isso permite personalizar quais funcionalidades estao disponiveis.

Veja mais em [Modulos de Comandos](../how-to-use/modules).
