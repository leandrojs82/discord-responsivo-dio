# Discord — Desafio de Responsividade DIO

Reprodução dos modelos desktop e mobile do Figma usando apenas HTML5 e CSS3, sem JavaScript, bibliotecas, frameworks ou instalação.

## Como abrir

Extraia o ZIP e abra `index.html` no navegador. Mantenha o arquivo `styles.css` e a pasta `assets` ao lado dele. Todas as imagens e fontes estão incluídas, permitindo visualizar o projeto sem internet.

## Arquivos

- `index.html`: abertura, quatro seções de conteúdo e rodapé.
- `styles.css`: tipografia, fundos, composição desktop e media queries para tablet e celular.
- `assets/`: ilustrações nas versões desktop e mobile, fundo da abertura, marca e fontes locais.

## Comportamento responsivo

- Desktop: título centralizado, botões lado a lado e seções com imagem e texto em colunas alternadas.
- Tablet, de 768 a 1023 px: colunas proporcionais e títulos menores.
- Celular, até 767 px: fundo mobile da referência, título alinhado à esquerda, botões em coluna e imagens antes do texto.
- Celulares menores que 360 px: ajustes de margens e texto dos botões.

As imagens são selecionadas com `picture` e `source`. O layout evita larguras fixas que ultrapassem a tela. Há texto alternativo nas imagens, um link para pular ao conteúdo e foco visível para navegação por teclado.

## Links

Os botões abrem a página oficial de download e o Discord no navegador. O link do rodapé abre o site oficial do Discord. Esses acessos exigem internet; o projeto local reproduz a página de apresentação, não a aplicação de mensagens.

## Referência e créditos

Design: https://www.figma.com/design/NRBYrG5d4DSzObv7dpTqoM/Desafio-Responsividade---DIO?node-id=0-1

Ilustrações do desafio: https://github.com/MarcosWinther/project-html-css-clone-site-discord/tree/main/assets/imgs

Marca no rodapé: https://github.com/AndersonBHBR/clone-discord-responsivo/tree/main/assets/images

Fontes: Open Sans e Luckiest Guy, obtidas no Google Fonts. Licenças incluídas em `assets/fonts`.

Marcas e ilustrações pertencem ao Discord e respectivos titulares. Projeto de estudo baseado no desafio da DIO, sem vínculo oficial com o Discord.
