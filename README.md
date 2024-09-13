<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="index.css">

        <title>Bem vindo</title>

</head>

<div class="container">
    <nav>
        <ul>
          <li>
            <a href="sobre.html">Sobre mim</a>
        </li>
    
        <li>
            <a href="projeto.html">Projetos</a>
        </li>
    
        <li>
            <a href="contato.html">Contato</a>
        </li>
        </ul> 
    </nav>
<header>
    <div class="center">
        <img src="./img/me.png" alt="me"> </img>
    </div>

    <h1>Erick Moreno</h1>
    <h2>Iniciando Carreira como Front-end</h2>
</header>    
    <main>
        <section>
            <h3>Sobre mim</h3>
            <P> Olá! Sou Erick, um desenvolvedor front-end em início de carreira. Tenho 26 anos, moro no Rio de Janeiro e tenho estudado programação por
                 conta própria. Atualmente, estou buscando oportunidades para ganhar experiência, prática e me desenvolver no mercado
                  de desenvolvimento web.

 
            </P>
        </section>

        <section>
            <h3>Formação</h3>
            <P>Completei o ensino médio e fiz um curso no Senac, onde me especializei como auxiliar administrativo e vendedor. Atualmente, estou estudando
                 programação por conta própria e aprendendo os conceitos de HTML, CSS e JavaScript.
                
            </P>
        </section>

        <section>
            <h3>Cursos</h3>
            <P>Senac - Portal do Futuro (auxiliar administrativo e vendas).<br>Curso em video - Gustavo Guanabara (HTML5, CSS e Js)<br>
                Curso básico de JavaScript na Udemy.
            </P>
           
        </section>
    </main>


    <footer>

        <a href="https://github.com/Guilzerk" target="_blank" rel="noopener noreferrer">
    
            <img src="./img/GitHub_Invertocat_Logo.svg.png" alt=""></img>

            <p>Github</p>
        </a>
        <a href="https://www.linkedin.com/in/erick-moreno-41b2311a7/" target="_blank" rel="noopener noreferrer">
    
            <img src="./img/i490027.jpeg" alt=""></img>

            <p>Linkedin</p>
        </a>
   

    </footer>
   
</div>

</body>

</html>


body{
color: white;
background-color: black;
font-family: Arial, Helvetica, sans-serif;
}

ul{
display: flex;
justify-content: space-between;
align-items: center;
padding: 16px;
list-style-type: none;
}

a {
    color: white;
    text-decoration: none;
}

header img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 5px solid rgb(60, 151, 236);;
}

.center {
    text-align: center;
}

h1{
    color: rgb(60, 151, 236);
}

footer img {
    width: 45px;
    height: 45px;
    border-radius: 50%;
}


footer {
   display: flex;
   justify-content: center;

  
}

footer a {
    margin: 20px;
    text-align: center;
}
footer p {
    text-align: center;
   margin-top: 2px;
}

.container {
    padding: 0px 50px;
}

nav a:hover {
  
    color: rgb(60, 151, 236);
}

