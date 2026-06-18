# Clínica Dra. Erica Mota — Estética Avançada

Landing page premium (HTML, CSS e JavaScript puro) focada em conversão pelo WhatsApp,
com foco de SEO local na **Freguesia do Ó** (Vila Albertina), São Paulo.

## Arquivos

```
index.html        Página única com todas as seções
styles.css        Estilos (branco · rosa pastel · dourado · glassmorphism)
script.js         Header dinâmico, menu mobile, scroll reveal
assets/
  favicon.svg     Ícone do site
  dra-erica.svg   Placeholder elegante da foto (substituir pela foto real)
robots.txt
sitemap.xml
```

## Como adicionar a foto da Dra. Erica

1. Salve a foto como **`assets/dra-erica.jpg`** (recomendado: vertical, ~640×800px ou maior, boa iluminação).
2. Pronto — a página detecta o arquivo automaticamente e troca o placeholder pela foto real,
   tanto na Hero quanto na seção "Sobre".

> Enquanto o `.jpg` não existir, um placeholder sofisticado é exibido no lugar.

## Personalizações rápidas

- **WhatsApp:** os links usam `https://wa.me/5511965849446`. Para trocar o número,
  faça um localizar/substituir por `5511965849446`.
- **Domínio:** ajuste as URLs `https://www.dra-ericamota.com.br/` nas meta tags,
  Open Graph, canonical, `sitemap.xml` e no Schema (`index.html`).
- **Cores:** todas as cores estão em variáveis CSS no topo de `styles.css` (`:root`).

## Publicação

É um site estático — basta hospedar a pasta em qualquer serviço (Netlify, Vercel,
GitHub Pages, hospedagem comum). Sem build, sem dependências.
