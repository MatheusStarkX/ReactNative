# Aplicativo mobile para entrega de comida

[![licence mit](https://img.shields.io/badge/licence-MIT-blue.svg)](./LICENSE)

Esse é meu primeiro projeto na área mobile, onde criei 3 telas interativas para entrega de comida por aplicativo. Nele pode-se escolher um ou mais produtos, adicioná-los ou removê-los do carrinho e enviar o pedido via whatsapp com informações de endereço para entrega.

Esse projeto foi baseado na trilha React Native da NLW 14 expert da Rocketseat (https://github.com/rocketseat-education/nlw-expert-react-native).

## Bibliotecas e ferramentas do projeto

- **Expo** para instalação do React Native, pois ele permite o fácil acesso às API’s nativas do dispositivo sem precisar instalar qualquer dependência ou alterar código nativo.
- **Tailwind CSS** para facilitar a estilização de páginas e componentes.
- **Zustand** para gerenciamento de estados globais na aplicação, nesse caso para persistir os dados do carrinho de compras.
- **CLSX** para aplicação de classes de forma condicional

## Estrutura de Pastas

Dentro do repositório temos os arquivos de configuração e 2 pastas principais: `\assets` que contém as imagens e ícones globais do app e `\src` que contém o todo o código fonte.
Na pasta `\src` a seguinte divisão de pastas foi feita:

- `app/` possui os arquivos e páginas principais da aplicação, como o `index.jsx` e o `_layout.tsx`, além da `[id].tsx`, uma pasta criada dinamicamente para configuração de cada produto.
- `assets/` contém arquivos estáticos como fontes, imagens, ícones, etc.
- `components/` contém os componentes reutilizáveis em todo o aplicativo.
- `stores/` possui as funções que manipulam os dados, como persistências e operações no carrinho de compras.
- `types/` que tem a referências para os estilos usados.
- `utils/` tem as funções utilitárias do app e os dados utilizados.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).
