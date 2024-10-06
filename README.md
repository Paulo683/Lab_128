# Lab_128 - Formulário de Contato

 Esse projeto é o resultado do Lab_128 da disciplina de Desenvolvimento de Sistemas Web. A ideia aqui era criar um formulário de contato bem simples, mas funcional, usando HTML, CSS e um pouco de Node.js. Além disso, conectamos o formulário a uma ferramenta chamada Formspree pra poder receber as mensagens de quem preencher.

## O que tem aqui

- **public/**: Aqui ficam os arquivos estáticos (HTML, CSS e imagens).
  - `index.html`: É a página do formulário.
  - `style.css`: Estilos pra deixar a página bonita.
  - `img/`: Contém as imagens do projeto (logo e etc).

- **server.js**: Esse é o arquivo do Node.js que roda o servidor e serve os arquivos da pasta `public`.

- **package.json** e **package-lock.json**: Esses são os arquivos que configuram as dependências e os scripts do Node.js.

## Ferramentas e Tecnologias

- **HTML5**: O básico pra estruturar a página.
- **CSS3**: Para estilizar e deixar tudo responsivo.
- **JavaScript (Node.js)**: Serve os arquivos e faz o backend básico.
- **Formspree**: A ferramenta que recebe os dados do formulário.

## Como rodar isso?

1. **Instala as dependências**:
   No terminal, dá um:
   ```bash
   npm install
Sobe o servidor: Depois, roda o servidor com:

node server.js

Acessa no navegador: Vai no http://localhost:3000 e vê o formulário rodando bonitinho.


O que o formulário faz?
Pega o nome, email e mensagem do usuário.
Quando você clica em enviar, os dados vão pro Formspree.
Tudo isso com um layout que se adapta bem em celular e desktop (responsivo é a palavra chique pra isso).
