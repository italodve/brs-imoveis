# BRS Imóveis — Site institucional

Landing page de conversão para a **BRS Imóveis**, imobiliária em São Bernardo do Campo/SP (Grande ABC).

**Instagram:** [@brs.imoveis.sbc](https://www.instagram.com/brs.imoveis.sbc/)
**Site oficial:** [brsimoveis.com.br](https://www.brsimoveis.com.br/)
**Google Maps:** [ver ficha da empresa](https://www.google.com/maps/search/?api=1&query=BRS%20Im%C3%B3veis&query_place_id=ChIJhRGhtbFBzpQRFq0ovXWQ5zo)

## Destaques

- **UX premium e original** — identidade em verde-esmeralda + champanhe, tipografia Fraunces/Inter, header com efeito glass, orbes animados no hero e marquee com os bairros de SBC atendidos.
- **Animações** — entrada em cascata no hero, reveal on scroll (IntersectionObserver), contadores animados, hover com zoom nos cards, tudo respeitando `prefers-reduced-motion`.
- **Responsivo** — layout fluido do mobile ao desktop, com menu hambúrguer em tela cheia.
- **Intuitivo e focado em conversão** — busca com abas (Comprar/Alugar), filtros instantâneos por tipo, bairro, quartos e preço, e todos os CTAs levando direto ao WhatsApp com mensagem pré-preenchida.
- **Zero dependências** — um único `index.html` com HTML, CSS e JS puros. Basta hospedar (GitHub Pages, Netlify etc.).

## Como editar

Tudo fica no `index.html`:

- **WhatsApp / mensagens:** objeto `CONFIG` no início do `<script>` — **troque o número placeholder pelo WhatsApp real da BRS**.
- **Imóveis:** array `IMOVEIS` — cada item gera um card automaticamente. Para espelhar os anúncios do Instagram, copie título, bairro, preço, quartos e área de cada post para um item do array. Adicione a foto real do post em `images/imovel-<id>.jpg` que ela substitui a ilustração SVG.
- **Cores / identidade:** variáveis CSS em `:root`.

## Publicar no GitHub Pages

Settings → Pages → Branch `main` → `/ (root)`. O site fica disponível em `https://<usuario>.github.io/brs-imoveis/`.
