# Atividade Guiada: Construindo uma Aplicação React com React Router

Aplicação React com múltiplas páginas, navegação com **React Router** e rotas
dinâmicas para exibição de detalhes de produtos.

## Autor
Paulo Henrique da Silva Lage

## Funcionalidades

- Navegação entre páginas sem recarregar (SPA) usando `react-router-dom`
- Páginas: Home, Sobre, Contato e Produtos
- Rota dinâmica `/produtos/:id` com `useParams()` para exibir detalhes de cada produto
- Estilização completa com CSS (`App.css`)
- Desafio final resolvido: a página de detalhes busca o produto no array pelo `id`
  da URL (convertido com `parseInt`) e exibe nome e preço, com tratamento para
  produto não encontrado

## Como rodar o projeto localmente

```bash
# 1. Clone o repositório
git clone <URL-DO-SEU-REPOSITORIO>
cd meu-app-com-rotas

# 2. Instale as dependências
npm install

# 3. Rode o servidor de desenvolvimento
npm run dev
```

Abra o endereço mostrado no terminal (geralmente `http://localhost:5173`).

## Estrutura de pastas

```
meu-app-com-rotas/
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── App.css
    ├── index.css
    ├── components/
    │   └── Menu.jsx
    └── pages/
        ├── Home.jsx
        ├── Sobre.jsx
        ├── Contato.jsx
        ├── Produtos.jsx
        └── ProdutoDetalhe.jsx
```
