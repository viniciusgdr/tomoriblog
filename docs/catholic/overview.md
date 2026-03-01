---
sidebar_position: 1
---

# Comandos Catolicos

O TomoriBOT oferece comandos para a comunidade catolica, com devocional diario, versiculos, santos e intercessao.

## /devocionaldiario

Envia o devocional diario da Palavra de Fe.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `devocional`, `dd` |

```
/devocionaldiario
```

Faz scraping de bibliaon.com e retorna o titulo e texto formatado do devocional do dia. Funciona no grupo e no privado.

---

## /versiculododia

Envia o versiculo do dia.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `vd`, `versiculo` |

```
/versiculododia
```

Busca o versiculo do dia em bibliaon.com. Funciona no grupo e no privado.

---

## /santo

Sorteia um santo para voce ou para alguem.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |

```
/santo
/santo @usuario
```

- Sem mencao: sorteia para voce
- Com mencao: sorteia para o usuario mencionado
- O santo e **persistido** por usuario (sempre o mesmo santo para a mesma pessoa)
- Retorna imagem e descricao do santo

---

## /quemsanto

Adivinhe o santo pelas pistas.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | `quem-santo` |

```
/quemsanto
```

### Como jogar

1. Inicie com `/quemsanto` - o bot mostra uma pista
2. Tente adivinhar respondendo com o nome do santo: `/quemsanto Sao Francisco`
3. Se errar, o bot da uma nova pista
4. Acertar concede +1 XP

### Regras

- Apenas **um jogo ativo por grupo** por vez
- Dicas aleatorias a cada tentativa errada

---

## /interceder

Registra e consulta intercessoes do dia no grupo.

| Propriedade | Valor |
|-------------|-------|
| **Aliases** | nenhum |

### Registrar intercessao

```
/interceder @usuario
```

Registra que voce esta orando pelo usuario mencionado.

### Ver lista do dia

```
/interceder
```

Sem argumentos, mostra todas as intercessoes registradas no dia.

### Regras

- Intercessoes expiram apos **24 horas**
- Cada intercessao mostra quem esta orando por quem
- Funciona apenas em grupos
