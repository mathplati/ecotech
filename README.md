Este projeto é um site de e-commerce para uma loja fictícia chamada EcoTech, especializada em produtos sustentáveis e tecnológicos. O site foi desenvolvido utilizando HTML, CSS e Bootstrap para garantir um design responsivo e acessível. O objetivo é proporcionar aos usuários uma experiência de compra online agradável, com foco em sustentabilidade.

Estrutura do Projeto
O projeto contém as seguintes páginas e arquivos principais:

index.html: Página inicial do site, contendo a apresentação da marca e um carrossel de produtos em destaque.
categorias.html: Página que exibe diferentes categorias de produtos disponíveis na loja.
contato.html: Página de contato para os usuários entrarem em contato com a loja.
carrinho.html: Página de visualização do carrinho de compras.
detalhes-produto.html: Página com detalhes sobre produtos individuais.
styles.css: Arquivo CSS com o estilo geral do site.
Bootstrap: Framework utilizado para facilitar o desenvolvimento responsivo e a criação de componentes interativos.
Tecnologias Utilizadas
HTML5: Para a estruturação do conteúdo e a criação das páginas web.
CSS3: Para estilizar as páginas e melhorar a aparência do site.
Bootstrap 5: Framework para facilitar o design responsivo e componentes interativos.
Bootstrap Icons: Para utilizar ícones nos botões e navegação.
Funcionalidades
Página Inicial (index.html)
Exibe um carrossel de produtos em destaque, onde os usuários podem visualizar rapidamente produtos sustentáveis em promoção.
Links de navegação para as principais seções do site: Categorias, Contato, Carrinho e Home.
Seção de produtos em destaque com cards que possuem imagem, título e botão para "Ver mais".
Página de Categorias (categorias.html)
Exibe categorias de produtos sustentáveis, como Roupas Sustentáveis, Beleza Natural, Itens para Casa e Tecnologia Verde.
Cada categoria possui um card com imagem e link para ver os produtos dessa categoria.
Página de Detalhes do Produto (detalhes-produto.html)
Exibe detalhes de um produto específico, com uma descrição e o preço.
O usuário pode adicionar o produto ao carrinho com um botão "Adicionar ao Carrinho".
Página de Contato (contato.html)
Formulário simples de contato para os usuários enviarem mensagens, com campos para Nome, E-mail, Assunto e Mensagem.
Informações de contato, como e-mail e telefone, também estão disponíveis no rodapé.
Página do Carrinho (carrinho.html)
Exibe os produtos no carrinho de compras do usuário.
Funcionalidade para adicionar e remover produtos do carrinho.
Estrutura de Pastas
css
Copiar
EcoTech/
│
├── index.html
├── categorias.html
├── contato.html
├── carrinho.html
├── detalhes-produto.html
├── styles.css
└── assets/
    ├── img/
    │   ├── product1.jpg
    │   ├── product2.jpg
    │   └── ...
    └── ...
index.html: Página inicial.
categorias.html: Página com as categorias de produtos.
contato.html: Página de formulário de contato.
carrinho.html: Página do carrinho de compras.
detalhes-produto.html: Página de detalhes de produto.
styles.css: Arquivo de estilos do site.
assets/img/: Pasta para armazenar imagens do site (produtos, banners, etc.).
Como Rodar o Projeto
Pré-requisitos
Para rodar o projeto, basta ter um navegador moderno instalado, como o Google Chrome ou Firefox. Não há necessidade de servidores ou configurações adicionais.

Passos
Baixe ou clone o repositório:

bash
Copiar
git clone https://github.com/seu-usuario/ecoTech.git
Abra a pasta do projeto:

bash
Copiar
cd ecoTech
Abra o arquivo index.html em seu navegador.

Você pode simplesmente clicar duas vezes no arquivo index.html ou abrir com um editor de texto e rodar diretamente no navegador.

Personalização
Este projeto foi desenvolvido para ser facilmente personalizável. Se você deseja adicionar novos produtos, basta editar os arquivos HTML e CSS, alterando os links de imagem e as descrições conforme necessário.

Além disso, se quiser expandir a funcionalidade de carrinho de compras, você pode integrar com uma API backend (por exemplo, utilizando Node.js, Express e MongoDB).

Contribuições
Sinta-se à vontade para fazer um fork deste repositório e criar suas próprias versões ou melhorias no projeto! Se você encontrar algum erro ou tiver sugestões, abra uma issue no GitHub ou envie um pull request.
