# Clínica Dra. Erica Mota — Estética Avançada

Landing page premium (HTML, CSS e JavaScript puro) focada em conversão pelo WhatsApp,
com foco de SEO local na **Freguesia do Ó** (Vila Albertina), São Paulo.

## Arquivos

```
index.html        Página única com todas as seções
styles.css        Estilos (branco · rosa pastel · dourado · glassmorphism)
script.js         Header dinâmico, menu mobile, scroll reveal
assets/
  favicon.svg        Ícone do site
  dra-erica.svg      Placeholder da foto da Dra. (Hero + Sobre)
  antes-depois.svg   Placeholder da imagem única de antes e depois
robots.txt
sitemap.xml
```

## Como adicionar as fotos (só soltar no repositório)

Salve as imagens dentro da pasta **`assets/`** com EXATAMENTE estes nomes. A página
detecta cada arquivo automaticamente e troca o placeholder pela foto real — sem mexer no código:

| Arquivo                   | Onde aparece           | Sugestão                                   |
| ------------------------- | ---------------------- | ------------------------------------------ |
| `assets/dra-erica.jpg`    | Hero **e** seção Sobre | Vertical, ~640×800px ou maior              |
| `assets/antes-depois.jpg` | Seção Antes & Depois   | Imagem única com antes e depois lado a lado |

> A imagem de antes/depois é **um único arquivo** (já com os dois lados na mesma foto).
> Os selos "Antes" e "Depois" são adicionados automaticamente sobre a imagem.
> Enquanto os `.jpg` não existirem, placeholders sofisticados são exibidos no lugar.

## Personalizações rápidas

- **WhatsApp:** os links usam `https://wa.me/5511965849446`. Para trocar o número,
  faça um localizar/substituir por `5511965849446`.
- **Domínio:** ajuste as URLs `https://www.dra-ericamota.com.br/` nas meta tags,
  Open Graph, canonical, `sitemap.xml` e no Schema (`index.html`).
- **Cores:** todas as cores estão em variáveis CSS no topo de `styles.css` (`:root`).

## Publicação

É um site estático — basta hospedar a pasta em qualquer serviço (Netlify, Vercel,
GitHub Pages, hospedagem comum). Sem build, sem dependências.
