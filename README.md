# GameZone

## Descrição

GameZone é um catálogo visual de jogos feito com HTML e CSS. A página apresenta três jogos em destaque, organizados por categoria, com imagens e descrições para ajudar visitantes a conhecer a seleção.

## Objetivo

O projeto demonstra a estruturação de uma página com áreas de navegação, apresentação, catálogo e rodapé, além da estilização e organização de conteúdo em cartões. Também apresenta um layout que se adapta a diferentes larguras de tela e inclui recursos de acessibilidade no HTML e no CSS.

## Tecnologias utilizadas

- **HTML5**: estrutura e conteúdo da página.
- **CSS3**: estilos, layout, adaptação a diferentes telas e efeitos visuais.

As imagens dos jogos são carregadas de URLs do Unsplash. O projeto não utiliza bibliotecas ou frameworks.

## Estrutura do projeto

```text
gamezone/
├── index.html   # Estrutura da página, navegação e conteúdo do catálogo
├── style.css    # Estilos, layout responsivo e efeitos visuais
└── README.md    # Documentação do projeto
```

## Como executar

Não é necessária instalação de dependências nem etapa de compilação. Abra o arquivo `index.html` em um navegador para visualizar a página. As imagens hospedadas no Unsplash dependem de conexão com a internet para serem carregadas.

## Acessibilidade e responsividade

- O documento declara o idioma como português do Brasil (`pt-BR`) e inclui uma descrição da página e a configuração de viewport.
- O HTML usa regiões e elementos semânticos, como `header`, `nav`, `main`, `section`, `article` e `footer`, além de títulos organizados por nível.
- A navegação tem um rótulo acessível; imagens dos jogos têm textos alternativos, e elementos decorativos são ocultados de tecnologias assistivas com `aria-hidden`.
- Links recebem um contorno visível ao navegar pelo teclado usando o foco.
- O CSS reorganiza a grade do catálogo em pontos de quebra para telas menores e ajusta o cabeçalho, o conteúdo e o rodapé em dispositivos estreitos.
- A preferência do sistema por movimento reduzido é considerada, diminuindo as transições e desativando a rolagem suave.
