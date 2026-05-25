# MPI — Clareza de Produto

Skill para Claude Code que guia alunas do **MPI (Meu Primeiro Infoproduto)** pelo processo de encontrar o nome e definir a promessa do produto.

Metodologia: **Branding.Lab**

---

## Como instalar

1. Crie a pasta da skill no seu projeto ou globalmente:
```bash
mkdir -p ~/.claude/skills/mpi-clareza
```

2. Copie o arquivo `SKILL.md` para essa pasta:
```bash
curl -o ~/.claude/skills/mpi-clareza/SKILL.md \
  https://raw.githubusercontent.com/branding-lab/mpi-clareza-skill/main/SKILL.md
```

3. Reinicie o Claude Code. A skill aparece automaticamente.

---

## Como usar

Digite `/mpi-clareza` em qualquer sessão do Claude Code.

**MODO GUIA** — sem contexto prévio: Claude faz perguntas em ordem com máximo 2 por vez, seguindo os frameworks PPEL, PMD, Linguagem Proprietária e Pontos de Indignação.

**MODO EXECUÇÃO** — chegue com os dados prontos:
```
Formato: [tipo do produto]
Público: [público-alvo]
Nome: [nome pensado]
Promessa: [promessa definida]
```
Claude avalia cada dimensão com nota e sugestões.

---

## O que a skill entrega

1. **Avaliação do nome** (Clareza / Memorização / Curiosidade / Percepção / Diferenciação)
2. **Avaliação da promessa** (Clareza / Emoção / Benefício / Especificidade / Credibilidade)
3. **5 variações de nome + 5 reescritas da promessa**
4. **Canvas de Criação do Produto** — HTML imprimível, preenchido com seus dados
5. **Calendário 30 Dias de Antecipação** — HTML imprimível, 30 micromovimentos para Instagram

---

## Arquivos de contexto (`/context`)

Referências da metodologia Branding.Lab usadas pela skill:

| Arquivo | Conteúdo |
|---|---|
| `01_IDENTIDADE_E_COMPORTAMENTO.md` | Persona, tom, princípios |
| `02_METODO_MPI_E_RCP.md` | PPEL, Cliente Colecionador, PMD, Linguagem Proprietária |
| `03_FRAMEWORK_NAMING_PROMESSA.md` | Critérios de avaliação de nome e promessa |
| `04_FRASES_E_LINGUAGEM.md` | DNA Branding.Lab — frases de ancoragem |
| `05_FLUXOS_E_DECISOES.md` | Fluxo de perguntas e regras de condução |

---

Branding Lab — meajuda@brandinglab.com.br
