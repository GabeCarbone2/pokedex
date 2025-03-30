📖 Pokédex - React App

Este é um projeto de Pokédex desenvolvido com React, consumindo a API da PokéAPI para exibir informações sobre os Pokémon.

✨ Funcionalidades

✅ Busca de Pokémon pelo nome
✅ Exibição de imagem, nome, número, peso e altura
✅ Interface responsiva e intuitiva

🚀 Tecnologias Utilizadas

React ⚛️ - Biblioteca para construção da interface

Fetch API 🌐 - Para requisições HTTP

CSS 🎨 - Estilização do layout

📌 Como executar o projeto

🔹 Pré-requisitos

Antes de iniciar, você precisa ter o Node.js instalado.

🔹 Passos para rodar o projeto

# Clone o repositório
git clone https://github.com/seu-usuario/pokedex-react.git

# Acesse a pasta do projeto
cd pokedex-react

# Instale as dependências
npm install

# Inicie o servidor
npm start

Agora, abra no navegador:

http://localhost:3000

🎨 Demonstração

A interface contém um campo de busca onde você pode digitar o nome de um Pokémon e visualizar seus detalhes.

<form onSubmit={handleSubmit}>
  <input
    type="text"
    placeholder="Digite o nome do Pokémon"
    value={nomePokemon}
    onChange={(e) => setNomePokemon(e.target.value)}
  />
  <button type="submit">Buscar</button>
</form>

📜 Licença

Este projeto está sob a licença MIT. Sinta-se livre para utilizá-lo e melhorá-lo! 🚀

