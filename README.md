# Afiliado ML — Vitrine de Produtos

Uma vitrine de produtos afiliados do Mercado Livre com links de afiliado personalizáveis.

## Como funciona

1. Edite o arquivo [`products.json`](products.json) com seus produtos e links de afiliado
2. Subistitua `SEU_LINK_AQUI` nos links pelos seus links reais de afiliado do Mercado Livre
3. Deploy (GitHub Pages, Netlify, ou qualquer servidor estático)

## Adicionando um produto

Abra `products.json` e adicione um novo item no array `products`:

```json
{
  "id": 9,
  "name": "Nome do Produto",
  "price": "R$ 99,90",
  "image": "https://url-da-imagem.jpg",
  "category": "Tech",
  "featured": false,
  "affiliateLink": "https://mercadolivre.com/sec/SEU_ID"
}
```

| Campo | Descrição |
|-------|-----------|
| `id` | Número único do produto |
| `name` | Nome do produto (aparece no card) |
| `price` | Preço formatado como string |
| `image` | URL da imagem do produto |
| `category` | Categoria (deve estar em `categories`) |
| `featured` | `true` para destacar no card |
| `affiliateLink` | Seu link de afiliado do Mercado Livre |

## Deploy no GitHub Pages

1. Vá em **Settings > Pages** no repositório
2. Em **Source**, selecione `master` branch e pasta `/ (root)`
3. Clique em **Save**
4. Seu site estará em `https://namerico.github.io/afiliado-ml/`

## License

MIT
