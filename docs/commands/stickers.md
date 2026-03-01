---
sidebar_position: 2
---

# Comandos de Sticker

Comandos para criar, converter e buscar figurinhas no WhatsApp.

## /sticker

Transforma imagens ou videos em figurinha.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `stk`, `s`, `f`, `fig`, `figurinha`, `roubar`, `rename` |
| **Permissao** | Todos |

**Uso:**
```
/s (com imagem ou video)
/s nome_pacote + nome_autor
/s --no-background
```

- Converte imagem para WebP ou video para WebP animado (max 5 segundos, 512x512)
- Flag `--no-background` remove o fundo da imagem
- Alias `roubar`/`rename` permite renomear figurinhas existentes
- Verifica NSFW automaticamente

---

## /sticker2

Figurinha em formato quadrado (sem padding transparente).

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `stk2`, `s2`, `f2`, `fig2`, `figurinha2` |
| **Permissao** | Todos |

**Uso:**
```
/s2 (com imagem ou video)
/s2 --no-background
```

Mesmo funcionamento do `/sticker`, mas mantendo formato quadrado.

---

## /sticker-circular

Figurinha com recorte circular.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `stickercircular`, `stkcircular`, `stkc`, `sc`, `s-circular`, `s-c` |
| **Permissao** | Todos |

**Uso:**
```
/sc (com imagem ou video)
```

Aplica recorte circular com canal alpha via ffmpeg.

---

## /togif

Converte figurinhas animadas em GIF.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `gif`, `g`, `figurinhagif`, `figurinhag` |
| **Permissao** | Todos |

**Uso:**
```
/togif (respondendo um sticker animado)
```

Funciona apenas com stickers animados. Para stickers estaticos, use `/toimage`.

---

## /toimage

Converte figurinhas em imagem.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `imagem`, `img`, `figurinhaimagem`, `figurinhai` |
| **Permissao** | Todos |

**Uso:**
```
/toimage (respondendo um sticker)
```

Se o sticker for animado, delega automaticamente para `/togif`.

---

## /attp

Texto para figurinha animada.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/attp Texto aqui
```

Gera uma figurinha animada (GIF) a partir do texto fornecido. Funciona no privado.

---

## /ttp

Texto para figurinha estatica.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/ttp Texto aqui
```

Gera uma figurinha estatica (imagem branca com texto). Funciona no privado.

---

## /stickers

Busca figurinhas no Sticker.ly.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `stickerly` |
| **Permissao** | Todos |

**Uso:**
```
/stickers gato
/stickers bom dia
```

Busca pacotes no Sticker.ly e envia ate 5 figurinhas aleatorias do resultado.

---

## /removerfundo

Remove o fundo de imagens.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `removebg`, `removebackground`, `removerbackground`, `removerbg` |
| **Permissao** | Todos |

**Uso:**
```
/removerfundo (respondendo uma imagem ou sticker)
```

Se responder um sticker, cria uma nova figurinha sem fundo automaticamente.

---

## /emoji

Converte um emoji em figurinha.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/emoji 🤡
/emoji 🎉
```

Busca a imagem do emoji na Emojipedia, converte para figurinha WebP e envia.

---

## /pack

Cria um pacote de figurinhas para o WhatsApp.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/pack (respondendo figurinhas)
```

Agrupa figurinhas em um pacote para compartilhar no WhatsApp.
