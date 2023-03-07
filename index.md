<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header></header>
    <main class="apresentacao">

        <div id="lottie"></div>

        <script src="https://cdnjs.cloudflare.com/ajax/libs/lottie-web/5.10.2/lottie.min.js"></script>

        <script>

            var params = {
                container: document.getElementById('lottie'),
                renderer: 'svg',
                loop: true,
                autoplay: true,
                path: 'https://assets2.lottiefiles.com/packages/lf20_lS88YC8r3Y.json'
            };

            var anim;

            anim = lottie.loadAnimation(params);

        </script>

        <section class="apresentacao__texto1">
            <h1 class="apresentacao__texto1__titulo">Eleve seu negócio digital a outro nível 
                <strong class="titulo-destaque">com um Design de qualidade!
                </strong></h1>
                <p>Olá! Olá! Sou Lucas Neves, Design com especialidade em Photoshop, Illustrator e Afeter Effects. Ajudo pequenos negócios e designers a colocarem em prática boas ideias. Vamos conversar?</p>
                    <div class="button">
                        <h2>Acesse nossas Redes:</h2>
                    <a href="https://instagram.com/" target="_blank">Instagram</a>
                    <a href="https://octos.com.br" target="_blank">Site</a>
                    </div>
        </section>
           
        
    </main>
    <footer></footer>
</body>
</html>
