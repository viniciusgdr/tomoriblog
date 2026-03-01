---
sidebar_position: 4
---

# Comandos de IA

Comandos que utilizam inteligencia artificial para gerar texto, imagens e audio.

## /gpt

Conversa com IA (ChatGPT).

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `gpt-oss`, `chatgpt` |
| **Permissao** | Todos |

**Uso:**
```
/gpt Qual e a capital da Franca?
/gpt Me explique fisica quantica de forma simples
```

- Mantem historico de conversa por usuario e grupo (ate 20 mensagens)
- Limite de 500 caracteres por mensagem
- Pode gerar e retornar imagens
- O nome do usuario e enviado como contexto
- **Analise de imagens:** envie uma imagem junto com o prompt para que a IA descreva ou analise o conteudo

---

## /dalle

Gera imagens com IA (DALL-E).

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `dall-e`, `imagine` |
| **Permissao** | Todos |

**Uso:**
```
/dalle um gato astronauta no espaco
/imagine paisagem cyberpunk com neon
```

Limite de 500 caracteres no prompt. Sempre gera uma imagem como resposta.

---

## /pixart

Gera imagens em alta resolucao com o modelo PixArt.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `pixart-gen` |
| **Permissao** | Todos |

**Uso:**
```
/pixart retrato realista de uma cidade futurista
```

O prompt e traduzido automaticamente para ingles antes da geracao, entao voce pode escrever em portugues.

---

## /tts-ia

Converte texto em audio com vozes de IA.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `ttsia`, `voiser` |
| **Permissao** | Todos |

**Uso:**
```
/tts-ia Ola, como voce esta?
```

Gera audio com voz natural de IA e envia como mensagem de audio no WhatsApp.
