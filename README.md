# Angular Blog Example

Este é um projeto de aplicação de blog desenvolvido com Angular. A aplicação tem uma estrutura simples, com componentes reutilizáveis como cabeçalho, menu, cards de conteúdo e rodapé.

## Funcionalidades

- **Cabeçalho**: Contém o título do blog.
- **Menu**: Um menu de navegação simples.
- **Cards de conteúdo**: Exibe cards grandes e pequenos com conteúdo fictício.
- **Rodapé**: Exibe o rodapé com informações sobre o blog.

## Tecnologias Usadas

- **Angular**: Framework JavaScript para construção de Single Page Applications (SPA).
- **TypeScript**: Linguagem de programação usada no desenvolvimento.
- **CSS**: Para estilização da interface.

## Estrutura do Projeto

A aplicação é dividida em vários componentes principais, como cabeçalho, rodapé, menu, e cards. Abaixo está a estrutura de diretórios do projeto:

```plaintext
blogApp/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── header/
│   │   │   ├── footer/
│   │   │   ├── menu/
│   │   │   ├── big-card/
│   │   │   └── small-card/
│   │   ├── app.component.ts
│   │   ├── app.component.html
│   │   ├── app.component.css
│   │   └── app.module.ts
│   ├── index.html
│   ├── main.ts
│   ├── styles.css
├── angular.json
├── package.json
└── tsconfig.json
```

## Pré Requisitos

Para rodar o projeto localmente, você precisará ter o Node.js e o Angular CLI instalados.

- Instale o Node.js (inclui o npm).
- Instale o Angular CLI globalmente.

```bash
npm install -g @angular/cli
```

## Como Rodar Local

1. ```bash
    git clone https://github.com/SEU_USUARIO/blogApp.git
    ```
2. ```bash
    cd blogApp
    ```
3. ```bash
    npm install
    ```
4. ```bash
    npm start
    ```
O servidor estará disponível em http://localhost:4200.

## Estrutura dos Componentes

- AppComponent: O componente raiz da aplicação. Ele contém a estrutura básica da página, incluindo o cabeçalho, menu, e o conteúdo principal.
- HeaderComponent: Exibe o título do blog.
- FooterComponent: Exibe informações sobre o blog.
- MenuComponent: Contém links de navegação (ainda não configurados).
- BigCardComponent: Exibe um card grande com informações fictícias.
- SmallCardComponent: Exibe um card pequeno com informações fictícias.

## Contribuindo
Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novos recursos. Para isso, basta seguir estas etapas:

1. Faça um fork do repositório.
2. Crie uma branch com a sua feature (git checkout -b feature/MinhaFeature).
3. Commit suas alterações (git commit -m 'Adiciona nova feature').
4. Envie para o repositório remoto (git push origin feature/MinhaFeature).
5. Abra um pull request.