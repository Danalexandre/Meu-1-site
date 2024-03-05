# Meu-1-site
Verificar algum erro em meu site
(html)
<!DOCTYPE html>
      <html lang="en">
      <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA Compatible" content="IE-edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>milgrau</title>
            <link rel="stylesheet" href="./style.css">
      </head>
      <body>
            <header>
                  <img id="logo" src="rimuro.png" />
                  </a>
            <nav> 
                        <ul>
                              <a href="index.html">
                                    <li>Home</li>
                              </a>
                              <a href="contatos.html">
                                    <li>contatos</li>
                        
                              <a href="fotos.html">
                                    <li>fotos</li>
                              </a>
                              <a href="comentarios.html">
                                    <li>comentarios</li>
                              </a>
                  </ul>
                  </nav>
            </header>
            <div id="banner"></div>
            <div id="trailer-conteiner">
            <div class="content">
            <video controls class="trailer">
                  <source src="./slime.mp4" type="video/mp4">
      </video>
      <div id="sinopse">
            <p class="description">
                  Em última análise, Rimuru sendo reconhecido como igual a Veldora basicamente significava 
                  que ele era reconhecido como um ser no mesmo status que um Dragão Verdadeiro, e por causa 
      disso, era necessário que Rimuru realmente se tornasse tão forte quanto um Dragão Verdadeiro para viver
      de acordo com isso
            </p>
            <button class="button">Assistir Anime</button>

      </div>

      </div>
      </div>
      <div class="actor-cards-container">
            <div class="cards-content">
            <div class="card banner-1">Rimuro-slime</div>
            <div class="card banner-2">Floresta de Jura-Batalha</div>
            <div class="card banner-3">Hinata-Vilã</div>
            </div>
            
            <footer>
                  <img style="object-fit: contain;" id="logo" src="rimuro.png"/>
                  <span>Todos os Direitos Reservados ©</span>
                  <span>Desenvolvido por: Daniel Alexandre</span>
                  
            <nav class="footer-navigation">
                  <ul class="footer-list">

                              <a href="index.html">
                                    <li>Home</li>
                              </a>

                              <a href="contatos.html">
                                    <li>contatos</li>
                              </a>

                              <a href="fotos.html">
                                    <li>fotos</li>
                              </a>
                              
                              <a href="comentarios.html">
                                    <li>comentarios</li>
                              </a>
                          </ul>
                            </nav>
            </footer>
      </body>
</html>

(Css)
@import url('https://fonts.googleapis.com/css2?family=Kdam+Thmor+Pro&display=swap');
*{
    margin: 0;
    padding: 0;
    background-color: black;
    list-style: none;
    text-decoration: none;
}

header{
    height: 90px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
nav{
    width: 60%;
}
ul{
    display: flex;
    width: 100%;
    justify-content: space-between;
}

li:hover{
    color: skyblue;
}

li{
   list-style: none; 
   color: aliceblue;
   cursor: pointer;
   font-size: 10px;
   transition: 3s;
   font-family: 'kdam thmor pro', sans-serif;
}
#logo{
    width: 150px;
    height: auto;
}

#banner {
    background-position: 50% 50%;
    background-size: cover;
    width: 100%;
    height: 600px;
    background-image: url(https://c4.wallpaperflare.com/wallpaper/867/201/234/rimuru-tensei-shitara-slime-datta-ken-hd-wallpaper-preview.jpg);
}

#trailer-conteiner{
    width: 100¢;
    height: 400px;
    display: flex;
    justify-content: center;
}

.content{
    width: 60%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.trailer{
    width: 50%;
}
#sinopse{
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-left: 30px;
}
.description{
    color: #fff;
    font-size: 10px;
    font-family:'kdam thmor pro', sans-serif;
    width: 70%;
}
.button{
    width: 200px;
    height: 60px;
    background-color: red;
    color: #fff;
    padding: 8px 10px;
    border-radius: 5px;
    cursor: pointer;
    transition: 1.5s;
    font-size: 18px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    border: none;
    outline: none;
    margin-top: 25px;
}
.button:hover{
    background-color: #fff;
    color: #000;
}
.actor-cards-container {
    width: 100%;
    display: flex;
    justify-content: center;
    margin-top: 50px;
}
.cards-content {
    width: 90%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    row-gap: 20px;
    column-gap: 40px;
}
.card{
    width: 100%;
    height: 600px;
    background-size: cover;
    background-position: 50% 50%;
    border-radius: 5px;
    cursor: pointer;
    transition: 1s;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding: 0 0 20px 10px;
    color: red;
    font-size: 17px;
    font-family: 'kdam thmor pro', sans-serif; 
}
.card:hover {
    transform: scale(1.02);
}

.banner-1 {
    background-image: url('https://gartic.com.br/imgs/mural/ze/zerek/rimuru-tempest.png');
}

.banner-2 {
     background-image: url('https://static.wikia.nocookie.net/tensura/images/4/46/Tempest.jpg/revision/latest?cb=20181209130800&path-prefix=pt-br'); 
}

.banner-3 { 
      background-image: url('https://static.wikia.nocookie.net/tensura/images/2/24/Hinata_Sakaguchi.jpg/revision/latest?cb=20190311203500&path-prefix=pt-br');
}
footer{
    height: 200px;
    margin-top: 50px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
}
span{
    color: #fff;
    font-family:'kdam thmor pro', sans-serif;
}
.footer-navigation{
    display: none;
}
.footer-list{
    display: flex;
    flex-direction: column;
    align-items: center;
}
@Media(max-width: 760px){
    .footer-navigation{
        display: block;
    }
    nav{
        display: none;
    }
    #banner {
        background-position: 40%;
    }
    #trailler-container {
        width: 100%;
        height: 400px;
        display: flex;
        flex-direction: column;
    }
    .content{
        width: 95%;
        display: flex;
        flex-direction: column;
    }
    .trailer{
    width: 100%;
    }
    #sinopse{
        width: 95%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    .description{
        width: 100%;
    }
    .button{
        width: 100%;
        margin-top: 30px;
    }
    .cards-content{
        grid-template-columns: 1fr;
        margin-top: 50px;
    }
}

