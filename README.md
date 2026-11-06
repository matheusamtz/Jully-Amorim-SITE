# Jully Amorim · Psicologia

Site da psicóloga Jullyannie (Jully) Amorim, CRP 01/18359, Brasília.

Uma página única em formato de storytelling: o visitante atravessa sete cenas (abertura, "o peso", o encontro, a abordagem, arteterapia, atendimentos e como começa) até o formulário de agendamento, que abre o WhatsApp com a mensagem pronta.

## Arquivos

- `index.html` — o site completo em um único arquivo (estilos, scripts, foto, ilustrações e logo embutidos).
- `logo/` — a assinatura "Jully Amorim" em SVG vetorial, nas cores lavanda, ameixa e branco.

## Publicar no GitHub Pages

1. Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`.
2. O site fica disponível em `https://matheusamtz.github.io/Jully-Amorim-SITE/`.
3. Para usar o domínio `jullypsicologia.com.br`, adicione-o em **Custom domain** e aponte o DNS para o GitHub Pages.

## Guardar os contatos em uma planilha

Hoje o formulário envia tudo pelo WhatsApp. Para também salvar cada contato, crie um endpoint (Formspree ou Google Apps Script ligado a uma planilha) e preencha a variável no `index.html`:

```js
var LEAD_ENDPOINT = 'https://...';
```

## Dependências externas

Carregadas por CDN: GSAP 3.12.5 + ScrollTrigger (cdnjs), Lenis 1.1.13 (jsDelivr) e as fontes Cormorant Garamond, Jost e Allison (Google Fonts). Sem elas o conteúdo aparece completo, porém sem animações.
