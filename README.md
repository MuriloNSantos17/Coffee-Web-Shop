<div align="center">
  <img src="./images/logo.png" alt="Coffee Web Shop" width="100">

  # Coffee Web Shop

  Landing page responsiva para uma cafeteria, desenvolvida com HTML, CSS e JavaScript.
</div>

## Sobre o projeto

O **Coffee Web Shop** apresenta uma cafeteria e seus produtos em uma página única. O layout reúne uma seção inicial, a história da marca, um catálogo de cafés, avaliações de clientes e informações de contato.

O projeto foi criado com tecnologias web nativas e não exige instalação de dependências ou processo de build.

## Funcionalidades

- Layout responsivo para desktop, tablet e celular
- Navegação suave entre as seções da página
- Menu adaptado para dispositivos móveis
- Campo de busca expansível
- Cabeçalho com destaque ao rolar a página
- Catálogo visual de produtos
- Seção de avaliações de clientes
- Rodapé com redes sociais, links de suporte e contato

> [!NOTE]
> Este projeto é uma interface demonstrativa. A busca, o carrinho, os botões de compra e os links sociais ainda não possuem integração com um back-end.

## Tecnologias

- [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Boxicons](https://boxicons.com/) para os ícones
- [Google Fonts](https://fonts.google.com/) para a fonte Poppins

## Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/MuriloNSantos17/Coffee-Web-Shop.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd Coffee-Web-Shop
   ```

3. Abra o arquivo `index.html` no navegador.

Se preferir utilizar um servidor local, execute:

```bash
python -m http.server 8000
```

Depois, acesse [http://localhost:8000](http://localhost:8000).

> A conexão com a internet é necessária para carregar a fonte Poppins e os ícones do Boxicons.

## Estrutura do projeto

```text
Coffee-Web-Shop/
├── images/        # Imagens, logotipos e fotos dos produtos
├── index.html     # Estrutura e conteúdo da página
├── style.css      # Estilos e regras de responsividade
├── main.js        # Interações do menu, busca e cabeçalho
├── LICENSE        # Licença do projeto
└── README.md      # Documentação
```

## Personalização

As principais cores da interface estão definidas como variáveis no início do arquivo `style.css`:

```css
:root {
  --main-color: #bc9667;
  --second-color: #edeae3;
  --text-color: #1b1b1b;
  --bg-color: #fff;
}
```

Os textos, produtos, preços, avaliações e dados de contato podem ser alterados diretamente no arquivo `index.html`. As imagens correspondentes ficam na pasta `images`.

## Autor

Desenvolvido por [Murilo Nunes dos Santos](https://github.com/MuriloNSantos17).

## Licença

Este projeto está disponível sob a [licença MIT](./LICENSE).
