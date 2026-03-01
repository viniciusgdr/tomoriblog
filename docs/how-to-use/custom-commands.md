---
sidebar_position: 4
---

# Comandos Personalizados

O painel web permite criar comandos personalizados para seu grupo com respostas pre-definidas.

## O que sao comandos personalizados?

Comandos que voce cria com respostas pre-definidas. Quando alguem digita o comando no grupo, o bot responde com o conteudo configurado.

## Criando um comando

1. Acesse o [painel de controle](https://tomoribot.com.br/dashboard)
2. Selecione o grupo desejado
3. Va na aba **Comandos**
4. Clique em **Adicionar Comando**
5. Preencha:
   - **Nome** do comando (ex: `regras`, `info`, `link`)
   - **Resposta** em texto
   - **Midia** (opcional): imagem, video ou audio

## Tipos de resposta

| Tipo | Descricao |
|------|-----------|
| Texto | Resposta em texto simples |
| Imagem | Imagem com legenda opcional |
| Audio | Arquivo de audio |
| Video | Arquivo de video |
| Documento | Qualquer arquivo |

## Editando comandos

Na aba de comandos do grupo, clique no comando existente para editar seu nome, resposta ou midia.

## Removendo comandos

Clique no icone de lixeira ao lado do comando para remove-lo.

## Uso pelo bot

Apos criar o comando personalizado, qualquer membro pode usa-lo digitando:

```
/nomeDoComando
```

A resposta configurada sera enviada automaticamente.

## Alterar texto via bot

Admins podem alterar o texto de comandos personalizados pelo WhatsApp. Para isso:

1. Envie a mensagem com o novo texto no grupo
2. **Responda** a essa mensagem com o comando:

```
/alterar-texto-comando nomeDoComando
```

Alias: `atc`

:::info
O novo texto vem da **mensagem citada** (respondida), nao do argumento do comando.
:::
