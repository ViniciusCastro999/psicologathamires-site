# psithamires-site

Landing page da psicóloga clínica **Thamires Castro**, CRP 04/71409.
Atendimento online, por chamada de vídeo.

🔗 https://viniciuscastro999.github.io/psithamires-site/
(domínio próprio `psicologathamires.com.br` em configuração)

## Estrutura

```
index.html              página completa (HTML + CSS embutidos, sem build)
assets/
  thamires-1.jpg        foto do topo
  thamires-2.jpg        foto da seção "Como funciona"
  favicon.png           ícone da aba (balão + coração)
  apple-touch-icon.png  ícone iOS
  icon-512.png          ícone grande (PWA / compartilhamento)
CNAME                   domínio personalizado (adicionado quando o DNS propagar)
_source/                originais das fotos, fora do versionamento
```

## Sobre a página

- Página única, sem dependências de build. Todo o CSS e os ícones de
  interface (SVG) estão no próprio `index.html`.
- Requisições externas: apenas Google Fonts (Fraunces, Mulish, Caveat)
  e as imagens em `assets/`.
- Identidade visual quente (nude/coral) calcada nos posts do Instagram
  [@psithamires.castro](https://www.instagram.com/psithamires.castro/).
  Tema único, sem modo escuro.
- CTA principal: WhatsApp **(35) 99884-5491**.

## Rodar localmente

```bash
python3 -m http.server
# abra http://localhost:8000
```

## Publicação

GitHub Pages a partir da branch `main` (pipeline nativo "pages build
and deployment"). Todo push para `main` republica o site em ~1 min.

### Domínio próprio

1. No registro.br (modo avançado), apontar o domínio para o GitHub Pages:
   - 4 registros `A` (nome vazio) → `185.199.108.153`, `185.199.109.153`,
     `185.199.110.153`, `185.199.111.153`
   - `CNAME` `www` → `viniciuscastro999.github.io`
2. Criar o arquivo `CNAME` na raiz com `psicologathamires.com.br`.
3. GitHub → Settings → Pages → Custom domain + Enforce HTTPS.

## Editar as fotos

Substitua os arquivos em `assets/` mantendo os nomes (ou ajuste os
`src` no `index.html`). Recomendado ~1000 px no lado maior e JPG.
