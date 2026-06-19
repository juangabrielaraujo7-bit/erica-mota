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

| Arquivo                 | Onde aparece         | Enquadramento ideal                              |
| ----------------------- | -------------------- | ------------------------------------------------ |
| `assets/dra-erica`      | Hero (topo)          | **Vertical** (retrato), rosto na metade de cima  |
| `assets/sobre`          | Seção Sobre          | **Vertical** (retrato), rosto na metade de cima  |
| `assets/antes-depois-1` | Seção Antes & Depois | **Quadrada** (antes e depois lado a lado)        |
| `assets/antes-depois-2` | Seção Antes & Depois | **Quadrada** (antes e depois lado a lado)        |

### Formatos aceitos automaticamente

Você pode salvar em **`.jpg`, `.jpeg`, `.png` ou `.webp`** — a página testa os formatos
nessa ordem e usa o primeiro que encontrar. Ex.: pode ser `dra-erica.jpg` **ou**
`dra-erica.png`. Enquanto nenhum existir, um placeholder sofisticado é exibido.

### Dicas de enquadramento ("ficar top")

- **Hero e Sobre:** fotos **verticais** (em pé). O recorte foca a metade de cima da
  imagem, então deixe o rosto na parte superior/central. Ideal a partir de ~640×800px.
- **Antes & Depois:** use imagens **quadradas** (1:1, como as do Instagram), cada uma já
  com o antes e o depois na mesma foto. As duas são exibidas lado a lado, do mesmo tamanho.
  Os selos "Antes" e "Depois" entram por cima automaticamente — não precisa editar a foto.

## Personalizações rápidas

- **WhatsApp:** os links usam `https://wa.me/5511965849446`. Para trocar o número,
  faça um localizar/substituir por `5511965849446`.
- **Domínio:** ajuste as URLs `https://www.dra-ericamota.com.br/` nas meta tags,
  Open Graph, canonical, `sitemap.xml` e no Schema (`index.html`).
- **Cores:** todas as cores estão em variáveis CSS no topo de `styles.css` (`:root`).

## Publicação

É um site estático — basta hospedar a pasta em qualquer serviço (Netlify, Vercel,
GitHub Pages, hospedagem comum). Sem build, sem dependências.
