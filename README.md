/* Estilos generales */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline;
    margin-right: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

header nav ul li a:hover {
    text-decoration: underline;
}

/* Sección principal */
#home {
    text-align: center;
    padding: 50px 20px;
    background-color: #1e2a38;
    color: white;
}

#home h1 {
    font-size: 40px;
    margin-bottom: 20px;
}

#home p {
    font-size: 20px;
    margin-bottom: 30px;
}

#home img {
    width: 100%;
    max-height: 400px;
    object-fit: cover;
}

/* Sección de juegos */
#juegos {
    padding: 50px 20px;
    background-color: #fff;
    text-align: center;
}

#juegos h2 {
    font-size: 30px;
    margin-bottom: 20px;
}

.juego {
    display: inline-block;
    width: 30%;
    margin: 10px;
    background-color: #f0f0f0;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.juego img {
    width: 100%;
    border-radius: 8px;
}

.juego h3 {
    font-size: 22px;
    margin-top: 10px;
}

.juego p {
    font-size: 16px;
}

/* Sección de noticias */
#noticias {
    padding: 50px 20px;
    background-color: #ececec;
    text-align: center;
}

#noticias h2 {
    font-size: 30px;
    margin-bottom: 20px;
}

.noticia {
    margin-bottom: 20px;
}

.noticia h3 {
    font-size: 24px;
    margin-bottom: 10px;
}

.noticia p {
    font-size: 16px;
}

/* Sección de contacto */
#contacto {
    padding: 50px 20px;
    background-color: #fff;
    text-align: center;
}

#contacto h2 {
    font-size: 30px;
    margin-bottom: 20px;
}

#contacto p {
    font-size: 16px;
}

/* Pie de página */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 50px;
}

