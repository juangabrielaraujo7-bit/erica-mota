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
  dra-erica.svg   Placeholder da foto da Dra. (Hero + Sobre)
  antes.svg       Placeholder da imagem "antes"
  depois.svg      Placeholder da imagem "depois"
robots.txt
sitemap.xml
```

## Como adicionar as fotos (só soltar no repositório)

Salve as imagens dentro da pasta **`assets/`** com EXATAMENTE estes nomes. A página
detecta cada arquivo automaticamente e troca o placeholder pela foto real — sem mexer no código:

| Arquivo                 | Onde aparece            | Sugestão                          |
| ----------------------- | ----------------------- | --------------------------------- |
| `assets/dra-erica.jpg`  | Hero **e** seção Sobre  | Vertical, ~640×800px ou maior     |
| `assets/antes.jpg`      | Slider Antes & Depois   | Horizontal, ~700×520px (mesma proporção da "depois") |
| `assets/depois.jpg`     | Slider Antes & Depois   | Horizontal, ~700×520px (mesma proporção da "antes")  |

> Dica: use o **mesmo enquadramento e proporção** nas fotos de antes/depois para o
> slider de comparação ficar perfeito. Enquanto os `.jpg` não existirem, placeholders
> sofisticados são exibidos no lugar.

## Personalizações rápidas

- **WhatsApp:** os links usam `https://wa.me/5511965849446`. Para trocar o número,
  faça um localizar/substituir por `5511965849446`.
- **Domínio:** ajuste as URLs `https://www.dra-ericamota.com.br/` nas meta tags,
  Open Graph, canonical, `sitemap.xml` e no Schema (`index.html`).
- **Cores:** todas as cores estão em variáveis CSS no topo de `styles.css` (`:root`).

## Publicação

É um site estático — basta hospedar a pasta em qualquer serviço (Netlify, Vercel,
GitHub Pages, hospedagem comum). Sem build, sem dependências.
