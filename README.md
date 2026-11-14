# Portfólio Pessoal

**Nome do aluno:** Laís ramos Messias

## Descrição do **portfólio**

Portfólio pessoal desenvolvido para apresentar meu perfil, tecnologias e ferramentas, projetos realizados durante a formação e formas de contato. O site contém menu de navegação, área de destaque (carousel), seção de perfil, apresentação de três projetos, área de contato e rodapé.

## Tecnologias utilizadas

- HTML5
- CSS3
- Bootstrap
- GitHub Pages

## Link do site publicado

https://laismess.github.io/portfolio_pessoal/

## Funcionamento do projeto

O arquivo `index.html` é a página principal. O menu fixo e responsivo permite navegar pelas seções Perfil, Projetos e Contato por meio de links internos. O carousel apresenta três slides com controles e indicadores. A seção Perfil reúne imagem, identificação, descrição, informações principais e tecnologias e ferramentas. A seção Projetos apresenta três cards com imagem, título, descrição e link. A seção Contato reúne botões para e-mail, GitHub e LinkedIn. O rodapé encerra a página.

O Bootstrap é carregado por CDN e fornece o sistema de grid, componentes, botões, cards e classes responsivas. Os arquivos visuais ficam na pasta `imagens`.

## Recurso novo adicionado

Foi adicionada uma animação de elevação nos cards da seção Projetos: quando o cursor passa sobre um card, ele se desloca suavemente para cima e recebe uma sombra mais destacada.

## Como o recurso foi implementado

O recurso foi implementado com CSS próprio no arquivo `index.html`. A classe `.project-card` utiliza `transition` nas propriedades `transform` e `box-shadow`, definindo a suavidade da animação. A regra `.project-card:hover` aplica `transform: translateY(-10px)` e uma sombra mais intensa. Assim, o efeito fica visível ao passar o mouse sobre cada card, sem adicionar outra seção ou alterar a estrutura solicitada.

