---
sidebar_position: 3
---

# Comandos de Download

Baixe musicas e videos de diversas plataformas diretamente no WhatsApp.

## /play

Baixa musicas do YouTube por busca.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `p` |
| **Permissao** | Todos |

**Uso:**
```
/play nome da musica
/play https://youtube.com/watch?v=...
```

Se receber uma URL direta, redireciona para `/ytmp3`. Limite de 35MB. Arquivos maiores que 15MB sao enviados como documento.

---

## /ytmp3

Baixa musicas do YouTube em MP3.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `mp3` |
| **Permissao** | Todos |

**Uso:**
```
/ytmp3 https://youtube.com/watch?v=...
/ytmp3 nome da musica
/ytmp3 --document https://youtube.com/watch?v=...
```

A flag `--document` forca envio como documento. Suporta selecao numerada marcando a mensagem de resultados.

---

## /ytmp4

Baixa videos do YouTube em MP4.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `mp4` |
| **Permissao** | Todos |

**Uso:**
```
/ytmp4 https://youtube.com/watch?v=...
/ytmp4 nome do video
```

Baixa na melhor qualidade disponivel. Limite de 128MB.

---

## /instagram

Baixa conteudo do Instagram.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `igdl`, `ig` |
| **Permissao** | Todos |

**Uso:**
```
/ig https://www.instagram.com/p/...
/ig https://www.instagram.com/reel/...
```

Suporta posts, reels, stories e IGTV.

---

## /tiktok

Baixa videos do TikTok sem marca d'agua.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `tk` |
| **Permissao** | Todos |

**Uso:**
```
/tk https://vm.tiktok.com/...
/tk https://www.tiktok.com/@user/video/...
```

Remove marca d'agua automaticamente. Suporta carrossel de imagens.

---

## /facebook

Baixa videos do Facebook.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `fbdl`, `fb` |
| **Permissao** | Todos |

**Uso:**
```
/fb https://www.facebook.com/user/videos/123456
```

Videos maiores que 15MB sao enviados como documento.

---

## /twitter

Baixa videos e imagens do Twitter/X em HD.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `tw`, `x` |
| **Permissao** | Todos |

**Uso:**
```
/tw https://twitter.com/user/status/...
/x https://x.com/user/status/...
```

Aceita URLs de twitter.com e x.com.

---

## /spotify

Baixa musicas do Spotify.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/spotify nome da musica
/spotify https://open.spotify.com/track/...
```

Permite selecao numerada nos resultados de busca.

---

## /soundcloud

Baixa musicas do SoundCloud.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `sddl`, `scl`, `scloud`, `soundcld`, `soundclddl` |
| **Permissao** | Todos |

**Uso:**
```
/soundcloud nome da musica
/soundcloud https://soundcloud.com/artist/track
```

---

## /threads

Baixa conteudo do Threads.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |
| **Permissao** | Todos |

**Uso:**
```
/threads https://www.threads.com/...
```

Suporta imagens e videos.
