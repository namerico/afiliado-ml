# Features Research — Affiliate Product Showcase

## Table Stakes (P0 — Ship First)

- **Product cards** — imagem, nome, preço e botão CTA ("Ver no Mercado Livre")
- **Abas de categoria** — navegação por segmento com filtro automático
- **Campo de busca** — filtro de texto client-side em tempo real
- **Design responsivo** — funciona em mobile e desktop
- **Carregamento rápido** — site estático, sem frameworks pesados
- **Disclaimer de afiliado** — nota no footer (obrigação legal)
- **Links funcionais** — abrem URL de afiliado em nova aba
- **Configuração via JSON** — adicionar/remover produtos sem editar código
- **Deploy simples** — GitHub Pages, sem backend

## Differentiators (P1/P2 — Improve Conversions, then Growth)

- **Seção de destaques** — "Ofertas do dia" ou "Mais clicados"
- **Badges de preço** — "Melhor custo-benefício", "Promoção"
- **Ordenação** — por preço (menor/maior), relevância
- **Contador por categoria** — mostra quantos produtos em cada aba
- **Descrições curtas** — destaque de 1-2 linhas por produto
- **Estrelas de avaliação** — rating visual sem backend
- **SEO + Open Graph** — meta tags para compartilhamento em redes
- **Modo escuro** — preferência do usuário

## Anti-Features (Dont Build)

- **Carrinho/checkout** — quebra o modelo de afiliado
- **Contas de usuário** — alto abandono, já fora do escopo
- **Painel admin/CMS** — JSON via git é mais simples
- **Multi-loja na v1** — dilui o foco
- **Histórico de preços** — precisa de backend
- **Scraping automático de preços** — serviço externo, inviável para estático
- **Comentários/avaliações** — moderação onerosa, majoritariamente spam
- **Lista de desejos** — precisa de estado de usuário, não gera cliques

## Dependencies & Complexity

| Feature | Complexity | Dependencies |
|---------|-----------|--------------|
| Cards + JSON | Baixa | — |
| Abas de categoria | Baixa | JSON com categorias |
| Busca | Baixa | Cards renderizados |
| Destaques | Média | JSON com flag 'featured' |
| Ordenação | Baixa | Dados de preço |
| Modo escuro | Baixa | CSS variables |
| SEO/OG tags | Baixa | HTML structure |
