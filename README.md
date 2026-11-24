# De Pátria para Pátria

Projeto 5 e 6 do curso de Desenvolvimento Web Full-Stack da TripleTen.

## Descrição

Página da Galeria de Arte TripleTen que apresenta as cidades natais de
profissionais da TripleTen. A página tem um cabeçalho com o logotipo, uma
seção de abertura com título, subtítulo e foto, uma seção de introdução com
uma citação e um texto sobre a galeria, uma grade de fotos, uma seção com as
histórias de cada cidade (com fotos, artistas e um botão para comprar a obra
como NFT) e um rodapé.

O layout é responsivo e segue o design do Figma em três larguras de tela:
1280px (desktop), 768px (tablet) e 320px (celular).

## Tecnologias e técnicas utilizadas

- HTML5 semântico
- CSS3 com Flexbox e Grid Layout (`grid-template-areas` nas seções
  `photo-grid` e `places`)
- Design responsivo com media queries nos pontos de interrupção 1024px e 544px
- Valores relativos (`%`, `fr`, `aspect-ratio`) e `object-fit` para as imagens
  se adaptarem a qualquer largura
- Sombras (`box-shadow`), gradiente (`linear-gradient`) e estados `:hover`
- `line-height` em valores decimais
- Fonte Inter conectada localmente com `@font-face` (`vendor/fonts.css`)
- Metodologia BEM com estrutura de arquivos BEM Flat
- Normalize.css para padronizar os estilos entre navegadores
- Imagens comprimidas em JPEG

## GitHub Pages

https://8felps8.github.io/web_project_homeland/
