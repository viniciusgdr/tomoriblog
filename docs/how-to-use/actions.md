---
sidebar_position: 12
---

# Acoes Condicionais

Crie regras automatizadas com logica condicional "SE/ENTAO" para aplicar protecoes baseadas em atributos dos membros.

## Como funciona

As acoes condicionais permitem criar regras como: "Se o nivel do usuario for maior que 5, permitir enviar links". Assim, membros mais ativos podem ter privilegios extras.

## Como criar

1. Acesse o **painel do grupo**
2. Va em **Acoes**
3. Clique em **Criar Acao**
4. Preencha o formulario

## Formulario

### Nome da acao

De um nome descritivo para identificar a regra.

### Condicoes (SE)

| Tipo de condicao | Descricao |
|------------------|-----------|
| **Nivel do Usuario** | Nivel de XP do membro |
| **Mensagens do Membro** | Quantidade total de mensagens enviadas |
| **Dinheiro do Membro** | Saldo de Cash do membro |

**Tipos de comparacao:** Maior que / Menor que / Igual a

Voce pode adicionar **multiplas condicoes** a mesma acao. Todas devem ser satisfeitas para a acao ser aplicada.

### Acao resultante (ENTAO)

| Acao | Descricao |
|------|-----------|
| **Anti-link** | Permitir ou Banir links |
| **Anti-Spam** | Permitir ou Banir mensagens em excesso |
| **Anti-Pornografia** | Permitir ou Banir imagens NSFW |

## Exemplos de uso

| Regra | Condicao | Acao |
|-------|----------|------|
| Membros ativos podem enviar links | Nivel > 5 | Anti-link: Permitir |
| Novatos nao podem enviar muitas mensagens | Mensagens < 50 | Anti-Spam: Banir |
| Membros ricos tem mais liberdade | Dinheiro > 1000 | Anti-link: Permitir |

## Painel de estatisticas

Na tela de acoes, voce ve cards com:
- Total de acoes criadas
- Acoes de permissao (Permitir)
- Acoes de banimento (Banir)
