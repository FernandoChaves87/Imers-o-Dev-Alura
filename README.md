# Dicas para ciclistas para Ciclistas

Este projeto é uma página web interativa criada para ser um guia rápido e uma base de conhecimento para ciclistas. Ele exibe uma coleção de dicas importantes sobre segurança, manutenção, alimentação e equipamentos, com a funcionalidade de busca para encontrar informações rapidamente.

## ✨ Funcionalidades

*   **Busca Dinâmica:** Filtre as dicas em tempo real digitando palavras-chave no campo de busca e pressionando "Enter" ou clicando no botão "Buscar".
*   **Conteúdo Centralizado:** Todas as dicas são carregadas a partir de um arquivo `data.json`, facilitando a adição, remoção ou edição de conteúdo sem precisar alterar o código da página.
*   **Design Responsivo:** A interface se adapta a diferentes tamanhos de tela, de desktops a celulares, com um tema escuro moderno.
*   **Links Úteis:** Acesso rápido aos seus perfis em plataformas de ciclismo como Strava, Garmin e Wikiloc.

## 🚀 Como Executar

1.  Clone ou baixe este repositório para o seu computador.
2.  Abra o arquivo `index.html` em um navegador web (Google Chrome, Firefox, etc.).

> **⚠️ Atenção:** Se as dicas não carregarem, pode ser devido a uma restrição de segurança do navegador (CORS) ao tentar carregar o arquivo `data.json` localmente. Para resolver isso, você pode usar um servidor local. Se você utiliza o Visual Studio Code, a extensão **Live Server** é uma ótima opção para abrir o projeto.

## 📂 Estrutura dos Arquivos

O projeto é composto pelos seguintes arquivos:

### `index.html`

É o arquivo principal que estrutura a página web. Ele contém o cabeçalho com o título e a barra de busca, a seção principal onde as dicas são exibidas e o rodapé com seus links de perfil.

### `style.css`

Este arquivo é responsável por toda a aparência visual da página. Ele define o tema escuro, as cores, a fonte "Quicksand", o layout dos cards e garante que a página seja responsiva para diferentes dispositivos.

### `script.js`

Aqui reside a lógica da aplicação. O script carrega os dados do arquivo `data.json` assim que a página é aberta, cria os cards de dicas e os exibe. Ele também gerencia a funcionalidade de busca, filtrando e exibindo os resultados conforme o que o usuário digita.

### `data.json`

Funciona como um pequeno "banco de dados" para o projeto. Ele armazena todas as dicas em um formato estruturado (JSON), permitindo que o `script.js` leia e manipule essas informações de forma fácil. Para atualizar o conteúdo da página, basta editar este arquivo.


