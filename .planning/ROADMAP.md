# Roadmap: Afiliado ML - Vitrine de Produtos

## Phases: 3

### Phase 1: Estrutura Base + Cards

**Goal:** Página funcional com produtos configuráveis via JSON e links de afiliado clicáveis

**Requirements:** PROD-02, PROD-03, PROD-04, UI-01, UI-04, UI-05

**Success Criteria:**
1. Arquivo JSON com pelo menos 3 produtos de exemplo é carregado e os produtos aparecem na página
2. Botão "Ver no Mercado Livre" em cada card abre a URL de afiliado correta
3. Página é responsiva (funciona em telas de 320px a 1920px)
4. Header mostra identificação "namerico"
5. Footer tem disclaimer de afiliado

### Phase 2: Navegação por Categorias + Busca

**Goal:** Usuário filtra por categoria via abas e busca por nome

**Requirements:** UI-02, UI-03, PROD-05

**Success Criteria:**
1. Abas de categoria são geradas automaticamente a partir do JSON
2. Clicar numa aba mostra apenas produtos daquela categoria
3. Aba "Todos" mostra todos os produtos
4. Digitar na busca filtra os cards em tempo real
5. Combinação de busca + filtro de categoria funciona juntos

### Phase 3: Design Final + Deploy

**Goal:** Design polido, pronto para GitHub Pages

**Requirements:** DEPLOY-01, DEPLOY-02

**Success Criteria:**
1. Site abre e funciona corretamente via `file://` (sem servidor)
2. GitHub Actions workflow configurado para deploy automático
3. `README.md` com instruções de como adicionar produtos e deployar

---

*Roadmap created: 2026-04-06*
