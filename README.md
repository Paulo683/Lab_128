# Lab_128 - Formulário de Contato

Este projeto faz parte do laboratório 128 da disciplina de Desenvolvimento de Sistemas Web. O objetivo é criar um formulário de contato funcional utilizando HTML, CSS e JavaScript, com a possibilidade de integração com uma ferramenta de envio de dados. Além disso, o projeto inclui a configuração de um servidor Node.js para servir o conteúdo do formulário.

## Estrutura do Projeto

- **public/**: Pasta que contém os arquivos estáticos, como HTML, CSS, e imagens.
  - `index.html`: Página principal que contém o formulário de contato.
  - `style.css`: Arquivo de estilo que define a aparência da página.
  - `img/`: Pasta contendo as imagens utilizadas no projeto (logo e outras).

- **server.js**: Arquivo principal do servidor Node.js, configurado para servir os arquivos estáticos da pasta `public`.

- **package.json** e **package-lock.json**: Arquivos de configuração do Node.js, contendo as dependências e scripts necessários para rodar o projeto.

## Tecnologias Utilizadas

- **HTML5**: Estrutura básica da página.
- **CSS3**: Estilização e responsividade.
- **JavaScript (Node.js)**: Backend simples para servir os arquivos.
- **Formspree**: Integração para o envio de dados do formulário.

## Como Rodar o Projeto

1. **Instalar as dependências**:
   Execute o seguinte comando para instalar as dependências necessárias:
   ```bash
   npm install
Iniciar o servidor: Após a instalação das dependências, inicie o servidor com:
-node server.js

Acessar o formulário: Com o servidor rodando, acesse http://localhost:3000 no navegador para visualizar o formulário de contato.



