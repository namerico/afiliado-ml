# Afiliado ML - Vitrine de Produtos

## What This Is

Uma vitrine de produtos afiliados do Mercado Livre em formato de landing page. Produtos organizados por categorias com abas de navegação, campo de busca, e cards contendo imagem, preço e botão com link de afiliado direto para a página do produto no Mercado Livre. O branding é "namerico".

## Core Value

O usuário deve conseguir encontrar um produto desejado rapidamente e clicar no link de afiliado para o Mercado Livre com zero fricção.

## Requirements

### Validated

(None yet — ship to validate)

### Active

- [ ] Landing page estática responsiva e rápida
- [ ] Produtos organizados por categoria com abas/filtros
- [ ] Campo de busca por nome do produto
- [ ] Cards com imagem, nome, preço e botão "Ver no Mercado Livre"
- [ ] Links usando URLs de afiliado personalizáveis por produto
- [ ] Arquivo de configuração simples (JSON) para adicionar/remover produtos
- [ ] Deploy simples (GitHub Pages ou similar)

### Out of Scope

- Checkout integrado — o redirecionamento é para o Mercado Livre, sem pagamento no site
- Conta de usuário — não precisa de login/registro
- Painel administrativo — a gestão de produtos é feita via arquivo de config
- Multi-loja na v1 — foco exclusivo no Mercado Livre, arquitetura prepara para outras lojas no futuro

## Context

- Vitrine de afiliado com foco no programa de afiliados do Mercado Livre
- Links direcionam para a página do produto no Mercado Livre
- Arquitetura estática (sem backend) para deploy simples e custo zero
- Gerenciamento de produtos via arquivo JSON — adicionar/remover sem tocar código

## Constraints

- **Tech stack**: Site estático (HTML/CSS/JS ou framework leve) — deploy simples em GitHub Pages
- **Performance**: Carregamento rápido — zero dependências pesadas desnecessárias

## Key Decisions

| Decision | Rationale | Outcome |
|----------|-----------|---------|
| Arquivo JSON para produtos | Sem backend, gestão simples via git | — Pending |
| Links externos (ML) | Modelo de afiliado, sem checkout próprio | — Pending |
| Design responsivo | Tráfego vem de mobile e desktop | — Pending |

---

## Evolution

This document evolves at phase transitions and milestone boundaries.

**After each phase transition** (via `/gsd-transition`):
1. Requirements invalidated? → Move to Out of Scope with reason
2. Requirements validated? → Move to Validated with phase reference
3. New requirements emerged? → Add to Active
4. Decisions to log? → Add to Key Decisions
5. "What This Is" still accurate? → Update if drifted

**After each milestone** (via `/gsd-complete-milestone`):
1. Full review of all sections
2. Core Value check — still the right priority?
3. Audit Out of Scope — reasons still valid?
4. Update Context with current state

---
*Last updated: 2026-04-06 after initialization*
