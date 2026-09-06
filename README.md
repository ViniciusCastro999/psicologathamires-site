# psithamires-site

Landing page da psicóloga clínica **Thamires Castro**, CRP 04/71409.
Atendimento online, por chamada de vídeo.

## Sobre

Página única (`index.html`), sem dependências de build. Todo o CSS e os
ícones (SVG) estão embutidos no próprio arquivo; as únicas requisições
externas são as fontes do Google Fonts (Fraunces, Mulish e Caveat) e a
foto `thamires.jpg`.

- Paleta nude/coral calcada nos posts do Instagram [@psithamires.castro](https://www.instagram.com/psithamires.castro/)
- Fotos de Thamires (`thamires1.jpg` no topo, `thamires2.jpg` em "Como funciona")
- Ícone próprio (`favicon.svg`, `apple-touch-icon.png`)
- Identidade visual única, quente (nude/coral), sem tema escuro
- CTA principal para o WhatsApp **(35) 99884-5491**

## Como visualizar

Abra o `index.html` no navegador, ou sirva a pasta:

```bash
python3 -m http.server
```

## Publicar no GitHub Pages

Settings → Pages → Branch: `main` / `/root`. O site fica em
`https://viniciuscastro999.github.io/psithamires-site/`.

## Estrutura

```
index.html        página completa
thamires1.jpg     foto do topo
thamires2.jpg     foto da seção "Como funciona"
favicon.svg       ícone da aba
```
