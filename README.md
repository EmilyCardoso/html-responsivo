# html-responsivo

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/mb.css">
    <link rel="stylesheet" href="css/mqsreen.css" 
    media="screen and (max-width:480px)">
    <title>Media Queries</title>
</head>

<body>
    <section>
    <h1>Media Queries</h1>
    <p>Texto professor</p>
    <img src="img/arvore.webp" alt"Arvore">
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Commodi saepe iste distinctio aliquam molestiae, f
        ugiat nam eligendi possimus libero mollitia quas inventore eaque iure magni hic dolorem, sequi quam laborum.</p>

    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolore vero magnam consectetur tempora eaque
        dolorem quia provident hic aperiam est perferendis molestiae inventore, repudiandae sequi dolores quisquam
        distinctio cupiditate eveniet!
    </p>

    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Consectetur odio eligendi est ad eveniet hic excepturi
        nesciunt cum non,
        suscipit minima assumenda nam aliquid unde eum. Pariatur saepe inventore consequatur.</p>

    </section>

</body>

</html>


*{
    margin: 0;
    padding: 0;

}
body{
    background-color:white;
    box-sizing: border-box;
    margin-top: 2em;

}
section{
    width: 80vw;
    height: auto;
    margin: 0 auto;
    padding: 0.5em;
    border: 0.1em solid black;
    background-color: cadetblue;
}

h1{
    font-family: 'Courier New', Courier, monospace;
    font-size: 2em;
    padding: 0.5em;
}

p{
    font-size: 1.2em;
    padding: 0.5em;
    line-height: 2em;

}
img{
    width: 10vw;
    height: 10vh;
    float: left;
    margin: 1em 0.5em 0.5em ;
    
}


@media screen and (max-width:480px){
  body{
        background-color:orange;
        font-size:10px;
        
    }
    h1{
        font-size:2.2em;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;

    }
    p{
        font-size:1.5em;
        font-family:Georgia, 'Times New Roman', Times, serif;
        line-height:01.6em;
        justify-content: flex-end;
    }
    section{
        width:88vw;
        height:auto;
        margin:0 auto ;
        background-color: lightskyblue;

    }

    img{
        width: 15vw;
        height: 15vh;
        
    }

}
