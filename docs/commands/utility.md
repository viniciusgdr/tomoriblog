---
sidebar_position: 5
---

# Comandos de Utilidade

Ferramentas praticas para o dia a dia no WhatsApp.

## /texto

Extrai texto de imagens (OCR).

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `ocr` |
| **Permissao** | Todos |

**Uso:**
```
/texto (respondendo uma imagem)
```

Usa Azure OCR para extrair texto. Tambem retorna uma descricao da imagem traduzida para portugues.

---

## /transcrever

Transcreve audios para texto.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `stt` |
| **Permissao** | Todos |

**Uso:**
```
/transcrever (respondendo um audio)
```

Usa OpenAI Whisper. Audio deve ter entre 1 e 60 segundos.

---

## /encurtar

Encurta links.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `shorten` |
| **Permissao** | Todos |

**Uso:**
```
/encurtar https://www.exemplo.com/url-muito-longa
```

---

## /tts

Converte texto em audio.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `t2a`, `text2audio` |
| **Permissao** | Todos |

**Uso:**
```
/tts Texto para ser convertido em audio
```

Gera audio usando text-to-speech e envia como mensagem de voz.

---

## /ping

Checa a velocidade e status do bot.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `velocidade` |
| **Permissao** | Todos |

**Uso:**
```
/ping
```

Mostra: tempo de resposta do bot e tempo de processamento.

---

## /clima

Consulta o clima de uma cidade.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/clima Sao Paulo
/clima Tokyo
```

Mostra temperatura, sensacao termica, minima/maxima, umidade, pressao, vento e mais. Se houver multiplos resultados, permite selecao.

---

## /metar

Relatorio meteorologico de aeroportos (codigo ICAO).

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/metar SBGR
/metar SBGR,SBSP
/metar --taf SBGR
```

Aceita multiplos codigos ICAO separados por virgula. A flag `--taf` inclui a previsao TAF.

---

## /wame

Gera link direto para conversa no WhatsApp.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `whatsappme`, `whatsapp-me` |
| **Permissao** | Todos |

**Uso:**
```
/wame
```

Retorna o link `https://wa.me/<seu-numero>`.

---

## /8d

Adiciona efeito de audio 8D em um audio.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/8d (respondendo um audio)
```

Aplica efeito 8D com eco tridimensional e pulsacao estereo. O audio citado e processado e enviado de volta com o efeito.

---

## /bass

Adiciona efeito de bass boost em um audio.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/bass (respondendo um audio)
```

Aumenta significativamente os graves do audio citado.

---

## /esquilo

Adiciona efeito de voz de esquilo (chipmunk) em um audio.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/esquilo (respondendo um audio)
```

Aumenta o pitch do audio em 1.5x sem alterar a velocidade. Se o audio tiver menos de 15 segundos, envia como mensagem de voz.

---

## /inverter

Inverte um audio de tras para frente.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/inverter (respondendo um audio)
```

O audio citado e tocado ao contrario. Se tiver menos de 15 segundos, envia como mensagem de voz.

---

## /tomp3

Converte video para audio MP3.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `mp3` |
| **Permissao** | Todos |

**Uso:**
```
/tomp3 (respondendo um video)
/mp3 (respondendo um video)
```

- Converte video para audio MP3 em 128kbps estereo
- Se a entrada for audio, alterna entre modo de voz e arquivo de audio
- Aceita videos, audios e documentos
- Limite: 200MB por arquivo

---

## /status30s

Corta video em segmentos de 30 segundos para status do WhatsApp.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `30s` |
| **Permissao** | Todos |

**Uso:**
```
/status30s (respondendo um video)
/30s (respondendo um video)
```

- Ideal para postar videos longos no status do WhatsApp (que aceita max 30s)
- Cada parte e enviada com legenda "Parte X de Y"
- Video precisa ter mais de 30 segundos de duracao
- Limite: 200MB por arquivo

---

## /tourl

Converte imagens para URL publica.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/tourl (respondendo uma imagem)
```

Faz upload da imagem e retorna o link publico. No celular, envia com botao de copiar. Verifica NSFW automaticamente.

---

## /whois

Consulta WHOIS de um dominio.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/whois google.com
/whois exemplo.com.br
```

Retorna informacoes de registro do dominio (proprietario, datas, servidores DNS, etc).

---

## /ephoto360

Cria efeitos de texto sobre imagens.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/ephoto360 <tema> <texto>
```

**Temas disponiveis:**

| Tema | Efeito |
|------|--------|
| `hacker` | Avatar hacker com neon ciano |
| `glass` | Texto em vidro molhado |
| `glass-cat` | Texto escrito a mao em vidro embaçado |
| `natal` | Texto 3D de Natal com brilhos |
| `glow` | Efeitos de brilho avancados |
| `blackpink` | Logo estilo BLACKPINK |
| `starswars` | Logo estilo Star Wars |

**Exemplo:** `/ephoto360 glass Texto Exemplo`

Texto entre 4 e 30 caracteres.
