# Requirements: Afiliado ML - Vitrine de Produtos

**Defined:** 2026-04-06
**Core Value:** O usuário deve conseguir encontrar um produto desejado rapidamente e clicar no link de afiliado para o Mercado Livre com zero fricção.

## v1 Requirements

### Interface

- [ ] **UI-01**: Landing page estática responsiva (mobile-first)
- [ ] **UI-02**: Abas/filtros visíveis por categoria
- [ ] **UI-03**: Campo de busca por nome do produto com filtro em tempo real
- [ ] **UI-04**: Header com identificação da loja "namerico"
- [ ] **UI-05**: Footer com disclaimer de afiliado

### Produtos

- [ ] **PROD-01**: Card com imagem, nome e preço do produto
- [ ] **PROD-02**: Botão "Ver no Mercado Livre" com link de afiliado em cada card
- [ ] **PROD-03**: Categorias configuráveis via arquivo JSON
- [ ] **PROD-04**: Produtos configuráveis via arquivo JSON (nome, imagem, preço, link de afiliado, categoria)
- [ ] **PROD-05**: Aba "Todos" mostrando produtos de todas as categorias

### Deploy

- [ ] **DEPLOY-01**: Site pronto para deploy no GitHub Pages
- [ ] **DEPLOY-02**: Build zero-dependência (sem servidor necessário)

## v2 Requirements

- **ANALYTICS-01**: Rastreamento de cliques (quantos clicks cada produto recebe)
- **SEO-01**: Meta tags por produto para compartilhamento em redes sociais
- **THEME-01**: Modo escuro

## Out of Scope

| Feature | Reason |
|---------|--------|
| Checkout integrado | Redirecionamento é para o Mercado Livre |
| Conta de usuário/autenticação | Não é necessário para vitrine |
| Painel administrativo | Gestão via arquivo JSON é suficiente |
| Multi-loja na v1 | Foco exclusivo em Mercado Livre |

## Traceability

| Requirement | Phase | Status |
|-------------|-------|--------|
| UI-01 | Phase 1 | Pending |
| UI-02 | Phase 2 | Pending |
| UI-03 | Phase 2 | Pending |
| UI-04 | Phase 1 | Pending |
| UI-05 | Phase 1 | Pending |
| PROD-01 | Phase 3 | Pending |
| PROD-02 | Phase 1 | Pending |
| PROD-03 | Phase 1 | Pending |
| PROD-04 | Phase 1 | Pending |
| PROD-05 | Phase 2 | Pending |
| DEPLOY-01 | Phase 3 | Pending |
| DEPLOY-02 | Phase 3 | Pending |

**Coverage:**
- v1 requirements: 12 total
- Mapped to phases: 12
- Unmapped: 0 ✓

---
*Requirements defined: 2026-04-06*
