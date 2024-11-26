<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cine&Séries - Página Inicial</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Cabeçalho do Site -->
    <header>
        <h1>Cine&Séries</h1>
        <p>Bem-vindo ao seu site favorito sobre filmes e séries!</p>
        <!-- Barra de Pesquisa -->
        <input type="text" id="searchInput" placeholder="Buscar filmes e séries..." onkeyup="searchMovies()">
    </header>

    <!-- Barra de Navegação -->
    <nav>
        <a href="index.html">Início</a>
        <a href="categorias.html">Categorias</a>
        <a href="contato.html">Contato</a>
    </nav>

    <!-- Conteúdo Principal -->
    <div class="container">
        <h2>Últimos Lançamentos</h2>
        <div class="movie-list" id="movieList">
            <!-- Card do Filme 1 -->
            <div class="movie-item">
                <img src="https://via.placeholder.com/200x300" alt="Poster do Filme 1">
                <h3>Filme 1</h3>
                <p>Aventura, Ação</p>
                <p>2023</p>
            </div>
            <!-- Card do Filme 2 -->
            <div class="movie-item">
                <img src="https://via.placeholder.com/200x300" alt="Poster do Filme 2">
                <h3>Filme 2</h3>
                <p>Drama, Suspense</p>
                <p>2022</p>
            </div>
            <!-- Card do Filme 3 -->
            <div class="movie-item">
                <img src="https://via.placeholder.com/200x300" alt="Poster do Série 1">
                <h3>Série 1</h3>
                <p>Comédia</p>
                <p>1ª Temporada</p>
            </div>
        </div>
    </div>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2023 Cine&Séries. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
