# BRS Brokers Imóveis — Site institucional

Landing page de conversão para a **BRS Brokers Imóveis** (CRECI 041332-J), imobiliária em Guarulhos/SP com nota 5.0 no Google (+170 avaliações).

**Endereço:** Rua São Bento Trairi, 49 — Jardim São João, Guarulhos/SP
**WhatsApp:** (11) 99479-8739 · **Fixo:** (11) 5197-7362
**Google Maps:** [ver ficha da empresa](https://www.google.com/maps/search/?api=1&query=BRS%20Brokers%20Im%C3%B3veis&query_place_id=ChIJhRGhtbFBzpQRFq0ovXWQ5zo)

## Destaques

- **UX premium e original** — identidade própria em verde-esmeralda + champanhe, tipografia Fraunces/Inter, header com efeito glass, orbes animados no hero e marquee de bairros atendidos.
- **Animações** — entrada em cascata no hero, reveal on scroll (IntersectionObserver), contadores animados, hover 3D nos cards, tudo respeitando `prefers-reduced-motion`.
- **Responsivo** — layout fluido do mobile ao desktop, com menu hambúrguer em tela cheia.
- **Intuitivo e focado em conversão** — busca com abas (Comprar/Alugar), filtros instantâneos por tipo, bairro, quartos e preço, e todos os CTAs levando direto ao WhatsApp com mensagem pré-preenchida.
- **Zero dependências** — um único `index.html` com HTML, CSS e JS puros. Basta hospedar (GitHub Pages, Netlify etc.).

## Como editar

Tudo fica no `index.html`:

- **WhatsApp / mensagens:** objeto `CONFIG` no início do `<script>`.
- **Imóveis:** array `IMOVEIS` — cada item gera um card automaticamente. Adicione uma foto real em `images/imovel-<id>.jpg` que ela substitui a ilustração SVG.
- **Cores / identidade:** variáveis CSS em `:root`.

## Publicar no GitHub Pages

Settings → Pages → Branch `main` → `/ (root)`. O site fica disponível em `https://<usuario>.github.io/brs-imoveis/`.
