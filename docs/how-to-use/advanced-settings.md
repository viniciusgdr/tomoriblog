---
sidebar_position: 5
---

# Configuracoes Avancadas

Funcionalidades avancadas disponiveis no painel de controle e via comandos.

## Ativacoes do Grupo

No painel web, a aba de **Ativacoes** permite ligar/desligar funcionalidades do bot. Cada ativacao e um toggle on/off.

### Protecao e Moderacao

| Ativacao | O que faz |
|----------|-----------|
| **Anti Link** | Bane membros que enviam qualquer tipo de link. Excecoes podem ser configuradas no painel |
| **Anti Link (WhatsApp)** | Bane membros que enviam links do WhatsApp (convites de grupo, etc) |
| **Anti Spam** | Bane membros que enviam mais de 6 mensagens em menos de 15 segundos |
| **Anti Estrangeiros** | Bane membros cujo numero de telefone nao e do Brasil. Excecoes configuraveis |
| **Anti Pornografia** | Detecta e bane envio de imagens NSFW (pornograficas) |
| **Anti Pagamento/Status** | Bane membros que publicam comprovantes de pagamento ou status (prevencao de golpes) |
| **Moderacao de Conteudo (Beta)** | Analisa textos e imagens via IA; se conteudo prejudicial e detectado, o membro recebe advertencia |

### Automacao e Conteudo

| Ativacao | O que faz |
|----------|-----------|
| **Bem Vindo** | Envia mensagem de boas-vindas quando um novo membro entra. Mensagem configuravel no painel |
| **Sim Simi** | O bot responde mensagens dos membros automaticamente como chatbot conversacional |
| **Auto Sticker** | Converte automaticamente imagens enviadas no grupo em figurinhas |
| **Auto Texto** | Transcreve audios enviados no grupo para texto automaticamente |
| **Datas Comemorativas** | Envia mensagem as 07:00 em datas especiais (feriados, datas comemorativas) |
| **Modo de Noticias** | Envia noticias do dia periodicamente no grupo. Categorias configuraveis |

### Gamificacao

| Ativacao | O que faz |
|----------|-----------|
| **Modo de XP, Level, Rank e Diversao** | Ativa sistema de gamificacao: membros ganham XP, sobem de nivel e competem no ranking. Configuracoes de nivel no painel |
| **Bau de Diversao** | O bot envia "baus" aleatorios para membros abrirem. Baus podem conter Cash |

### Contagem de violacoes

No painel de comandos do grupo, voce pode definir **quantas infracoes de ativacoes** um membro pode cometer antes de ser punido, ajustando a tolerancia.

---

## Blacklist

Membros na blacklist sao impedidos de usar o bot no grupo.

### Via bot

```
/adicionarblacklist @usuario
```

Aliases: `blacklist`, `bloquear`

### Via painel

Na aba de comandos do grupo, gerencie a blacklist de usuarios.

---

## Antilink — Configuracao

Quando ativado, o bot deleta automaticamente mensagens com links. No painel, voce pode:

- Configurar **excecoes** (dominios permitidos)
- Definir a **acao** (avisar, deletar ou banir)
- Combinado com [Acoes Condicionais](./actions), membros de nivel alto podem ser isentos

---

## Regras do grupo

Configure regras personalizadas que serao exibidas com `/regras`:

1. Acesse o grupo no painel
2. Va na aba de comandos
3. Defina as regras no campo dedicado

---

## Banir usuario

```
/banirusuario @numero_completo
```

Bane um usuario de **todos os grupos** onde o bot esta e adiciona a blacklist. Diferente do `/ban`, que remove apenas do grupo atual.

---

## Infracoes

Sistema de advertencias para membros:

### Dar infracao

```
/infracao @usuario motivo
```

Aliases: `infracao`, `adv`, `advertencia`

### Ver infracoes

```
/infracoes
```

### Remover infracao

```
/removerinfracao @usuario
```
