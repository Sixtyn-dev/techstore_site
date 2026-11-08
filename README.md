# Nexa Tech — Loja de Tecnologia

Protótipo acadêmico de uma loja virtual de celulares, notebooks e acessórios, desenvolvido com **HTML5 e CSS3**. O site é estático e pode ser publicado gratuitamente com GitHub Pages.

## Acessar o site
Após ativar o GitHub Pages, adicione aqui o endereço publicado:
`https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## Telas e navegação
O projeto possui seis telas conectadas:
1. `index.html` — página inicial e acesso às categorias.
2. `celulares.html` — catálogo de celulares.
3. `notebooks.html` — catálogo de notebooks.
4. `acessorios.html` — catálogo de acessórios.
5. `produto.html` — detalhes de um produto.
6. `contato.html` — formulário visual e informações de atendimento.

## Conceitos aplicados

### Usabilidade
- Menu principal consistente em todas as páginas.
- Categorias organizadas e chamadas para ação claras.
- Caminho de navegação e botão para voltar ao catálogo na página de produto.
- Conteúdo dividido em blocos e cartões para facilitar a leitura.

### Experiência do Usuário (UX)
- Identidade visual consistente, com paleta azul-marinho e azul.
- Hierarquia visual entre títulos, descrições, preços e botões.
- Fluxo simples: início → categoria → produto → contato.
- Textos objetivos e informações importantes em destaque.

### Acessibilidade
- Documento em português (`lang="pt-BR"`).
- Estrutura semântica com `header`, `nav`, `main`, `section`, `article` e `footer`.
- Rótulos associados aos campos do formulário.
- Texto alternativo/descrições acessíveis para ilustrações relevantes.
- Link “Pular para o conteúdo” e foco de teclado visível.
- Contraste pensado para facilitar a leitura.

### Responsividade
- Layout com CSS Grid e Flexbox.
- Media queries para telas menores.
- Navegação com quebra de linha e cartões que mudam de colunas conforme a largura.
- Imagens/ilustrações dimensionadas dentro dos seus contêineres.

## Divisão de tarefas sugerida
Cada integrante fica responsável por duas telas, conforme a exigência de no mínimo duas telas por pessoa:

| Integrante | Telas / responsabilidades |
|---|---|
| Mohammed Samer | `index.html` (início) e `celulares.html` (catálogo de celulares) |
| Joao Franscisco Anciutti | `notebooks.html` (catálogo de notebooks) e `acessorios.html` (catálogo de acessórios) |
| Israel Lima | `produto.html` (detalhes do produto) e `contato.html` (contato) |

**Trabalho conjunto:** revisão de navegação, testes em diferentes tamanhos de tela, acessibilidade, organização do CSS e publicação no GitHub Pages. Todos os integrantes devem realizar commits com sua própria conta.

## Como executar localmente
Baixe/clique em `index.html` para abrir no navegador. Não é necessário instalar dependências nem executar servidor.

## Como publicar no GitHub Pages
1. Crie um repositório no GitHub (por exemplo, `nexa-tech`).
2. Envie todos os arquivos e pastas mantendo a estrutura.
3. Cada integrante deve contribuir com commits identificados pela própria conta GitHub.
4. No repositório, acesse **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Escolha a branch `main` e a pasta `/ (root)`, depois salve.
7. Aguarde a publicação e copie o endereço exibido na seção Pages.
8. Substitua o endereço de exemplo no início deste README pelo link real.

## Observação
Produtos, preços, e-mails e dados de atendimento são fictícios e servem somente para demonstrar o design. O formulário é visual e não envia mensagens.
