# MoviesLib

Um site de portfólio simples utilizando API para visualização de informações sobre filmes

# Demonstração   
[Acesse o site](https://movies-lib-xi.vercel.app)

# Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript  
- React
- API TMDB

#Como rodar o projeto?
1. Clone este repositório:
   ```bash
   git clone https://github.com/GabrielM6/MoviesLib.git
   cd MoviesLib
   npm install

2. Obtenha a chave da API TMDB
   Acesse TMDB Developer, crie uma conta e solicite uma chave de API.
   crie uma conta e solicite uma chave de api

3. Configure as variáveis de ambiente:
   Crie um arquivo chamado .env na raiz do projeto e adicione:
   ```.env
   VITE_API_KEY=api_key=SUA_CHAVE_API
   VITE_API=https://api.themoviedb.org/3/movie/
   VITE_SEARCH=https://api.themoviedb.org/3/search/movie
   VITE_IMG=https://image.tmdb.org/t/p/w500/

4.Rode o projeto:
  no terminal execute:
  ```bash
  npm run dev
