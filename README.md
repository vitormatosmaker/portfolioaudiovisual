[404.html](https://github.com/user-attachments/files/24718684/404.html)
<!DOCTYPE html>

<html lang="pt-BR">
<head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Portfólio Audiovisual</title>
<link href="https://fonts.googleapis.com/css2?family=Anton&amp;family=Montserrat:wght@400&amp;display=swap" rel="stylesheet"/>
<style>
    body {
      margin: 0;
      background-color: #0e0e0e;
      font-family: 'Arial', sans-serif;
      color: white;
      text-align: center;
    }

    .whatsapp-button {
      margin-top: 40px;
      margin-bottom: 10px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      background-color: #25D366;
      color: white;
      padding: 8px 60px;
      border-radius: 40px;
      text-decoration: none;
      font-size: 22px;
      font-weight: bold;
      width: 271px;
    }

    .whatsapp-icon {
      filter: drop-shadow(1px 1px 2px black);
      margin-right: 6px; /* pequeno espaço entre ícone e texto */
      width: 17%;
    }

    .whatsapp-text {
      display: inline-block;
      filter: drop-shadow(1px 1px 1px black);
      font-family: 'Poppins', sans-serif;
      font-size: 17px;
    }

    .whatsapp-subtext {
      margin-top: 0;
      margin-bottom: 50px;
      color: #A4F6BE;
      font-size: 10px;
      letter-spacing: 1px;
      font-family: 'Poppins', sans-serif;
       font-weight: 400;
    }

    .banner-container {
      position: relative;
      max-width: 800px;
      margin: 0 auto;
    }

    .banner-container img {
      width: 100%;
      height: auto;
      border-radius: 0;
    }

    .title {
      font-family: 'Anton', sans-serif;
      font-size: 137px;
      font-weight: 400;
      margin: 164px;
      color: white;
      text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.8);
      letter-spacing: 2px;
      position: relative;
      top: 19px;
      z-index: 2;
    }

    .subtitle {
      font-family: 'Montserrat', sans-serif;
      font-size: 22px;
      color: #c8c9ed;
      margin-top: -160px;
      letter-spacing: 3px;
    }

    .scroll-indicator {
      font-size: 32px;
      color: white;
      margin-top: 15px;
      animation: bounce 2s infinite;
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(10px); }
    }
  
@media (max-width: 768px) {
  .title {
    font-size: 48px;
    top: -60px;
  }
  .subtitle {
    font-size: 16px;
    margin-top: -80px;
  }
  .whatsapp-button {
    width: 90%;
    padding: 10px 20px;
    font-size: 18px;
  }
  .whatsapp-icon {
    width: 24px;
  }
  .portfolio {
    flex-direction: column;
  }
  .video-card {
    width: 100%;
  }
  .team-member {
    width: 90%;
  }
  .team-member img {
    width: 100%;
    height: auto;
  }
  header h1 {
    font-size: 32px;
  }
  header p {
    font-size: 16px;
  }
  .hero-content h1 {
    font-size: 1.8rem;
  }
  .hero-content p {
    font-size: 1rem;
  }
}

@media (max-width: 768px) {
  .video-wrapper {
    padding-top: 56.25%; /* 16:9 aspect ratio */
  }
  .modal-content {
    width: 95%;
    height: 60%;
  }


}
</style>
</head>
<body>



<div class="title">PORTFÓLIO</div>
<div class="subtitle">PRODUÇÃO AUDIOVISUAL</div>
<div class="scroll-indicator">↓</div>
</body>
</html>
<!DOCTYPE html>

<html lang="pt-BR">
<head>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400&amp;display=swap" rel="stylesheet"/>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Portfólio Filmmaker</title>
<style>
    * { margin:0; padding:0; box-sizing:border-box; }
    body { font-family: 'DIN2014';
  background: radial-gradient(circle at 90% 10%, #00023d  0%, #02040a 80%); background-size: cover;
  background-repeat: no-repeat;background-attachment: fixed; color:#eee; }
  .hero { position:relative; width:100%; height:60vh; overflow:hidden; }
    .hero video { position:absolute; top:50%; left:50%; width:85%; height:85%; object-fit:cover; transform:translate(-50%, -50%); filter:brightness(0.6); }
    .hero-content { position:absolute; top:50%; left:50%; transform:translate(-50%, -50%); text-align:center; color:#fff; z-index:2; }
    .hero-content h1 { font-size:2.5rem; margin-bottom:0.5rem;}
    .hero-content p { font-size:1.2rem; margin-bottom:1rem; }
    .btn-contact { display:inline-block; background:#e91e63; color:#fff; padding:0.8rem 1.5rem; border-radius:30px; text-decoration:none; font-weight:600; transition:background 0.3s ease; }
    .btn-contact:hover { background:#b31547; }
    .portfolio { max-width: 1020px; margin: 2rem auto 4rem; padding: 0 1rem; display: flex; flex-wrap: wrap; justify-content: center; gap: 0.75rem; margin-bottom: -10px;}
    .video-card { background: #222; border-radius: 8px; overflow: hidden; box-shadow: 0 0 10px #0006; position: relative; display: flex; flex-direction: column; transition: transform 0.4s ease; width: calc(33% - 0.75rem); }
    .video-wrapper { position: relative; width: 100%; padding-top: 177.77%; overflow: hidden; }
    .video-card iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none; z-index: 1; }
    .video-card:hover { transform: scale(1.05); transition: transform 0.3s ease; }
    footer { text-align:center; padding:1.5rem 0; background:#222; color:#999; }
    section { padding: 2rem 0; text-align: center; }
    h2 { font-size: 2rem; color: #ffffff; margin-bottom: 0rem;  font-family: 'Poppins', sans-serif;
  font-weight: 600; /* Regular */}

    .description { font-size: 1rem; color: #c5c7f8; margin-bottom: 2rem; font-family: 'Poppins', sans-serif;
  font-weight: 600;}
    
    /* Modal (video em alta qualidade) */
    .modal { display: none; position: fixed; top: 0; left: 0; width: 100vw; height: 100vh; background: rgba(0, 0, 0, 0.8); z-index: 10; justify-content: center; align-items: center; }
    .modal-content { position: relative; width: 80%; height: 80%; }
    .modal iframe { width: 100%; height: 100%; border: none; }
    .close { position: absolute; top: 10px; right: 20px; font-size: 30px; color: #fff; cursor: pointer; }

    @media (max-width: 768px) {
  .coringa h2 {
    font-size: 20px; /* tamanho apenas para mobile */
    font-family: 'Poppins', sans-serif;
}

.description  {
    font-size: 10px; /* tamanho apenas para mobile */
    font-family: 'Poppins', sans-serif;
    color: #c5c7f8;
}

 .mk_of h2 {
     font-size: 20px; /* tamanho apenas para mobile */
    font-family: 'Poppins', sans-serif;
  }

}
  </style>
</head>
<body>
<section>

<span class="coringa">   <h2>TRABALHOS EM DESTAQUE</h2></span> 
<p class="description">Confira alguns dos trabalhos que entregamos aos nossos clientes</p>
<div class="portfolio">
<div class="video-card center" onclick="openModal('https://player.vimeo.com/video/1099462212?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099462212?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099468333?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099468333?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099468840?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099468840?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<!-- New videos (Row 2) with hidden title, profile, and channel -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099458457?p=0s')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099458457?p=0s&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099459713?p=0s')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099459713?p=0s&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099461212?p=0s')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099461212?p=0s&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<!-- New row with 3 new videos -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099464291?p=0s')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099464291?p=0s&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099542612?p=0s')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099542612?p=0s&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099469570?p=0s')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099469570?p=0s&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
</div>
</section>
<!-- Seção "Making Of" -->
<section>
<div class="mk_of"> <h2>MAKING OF</h2> </div>
<p class="description">Confira como foram os bastidores de algumas filmagens  </p>
<div class="portfolio">
<!-- Primeiro vídeo de making of -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099554358?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099554358?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0&amp;portrait=0"></iframe>
</div>
</div>
<!-- Segundo vídeo de making of -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099553815?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099553815?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<!-- Terceiro vídeo de making of -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099555900?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1102961573?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<!-- Quarto vídeo de making of -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099555025?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099555025?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<!-- Quinto vídeo de making of -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099555467?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099555467?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<!-- Sexto vídeo de making of -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099756489?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099756489?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<!-- Sétimo vídeo de making of -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099795275?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099795275?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<!-- Oitavo vídeo de making of -->
<!-- Novo vídeo de making of -->
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099778246?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099778246?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
<div class="video-card" onclick="openModal('https://player.vimeo.com/video/1099778841?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0')">
<div class="video-wrapper">
<iframe allow="autoplay; fullscreen" allowfullscreen="" src="https://player.vimeo.com/video/1099778841?h=76e43c87b1&amp;title=0&amp;byline=0&amp;portrait=0"></iframe>
</div>
</div>
</div>
</section>
<!-- Modal -->
<div class="modal" id="videoModal">
<span class="close" onclick="closeModal()">×</span>
<div class="modal-content">
<iframe allow="autoplay; fullscreen" allowfullscreen="" id="modalVideo" src=""></iframe>
</div>
</div>
<script>
  // Função para abrir o vídeo em alta qualidade
  function openModal(videoUrl) {
    document.getElementById("modalVideo").src = videoUrl;
    document.getElementById("videoModal").style.display = "flex";
  }

  // Função para fechar o modal
  function closeModal() {
    document.getElementById("videoModal").style.display = "none";
    document.getElementById("modalVideo").src = ""; // Parar o vídeo ao fechar
  }

  // Fechar o modal se o usuário clicar fora do vídeo
  window.onclick = function(event) {
    if (event.target == document.getElementById("videoModal")) {
      closeModal();
    }
  }
</script>
</body>
</html>
<!-- Adicionando a frase e o botão ao final com mais estilo -->
<section>
<style>
      /* Importing the Poppins font from Google Fonts */
      @import url('https://fonts.google.com/selection');
   
     
      .highlight-text {
        font-family: 'Poppins', sans-serif;
        font-size: 2rem;
        font-weight: 600;
        color: #e91e63;
        text-align: center;
        margin-top: 2rem;
        letter-spacing: 1px;
     /*    text-transform: uppercase;      deixa o texto grande */
       
      }

      .btn-contact {
        display: inline-block;
        background: #e91e63;
        color: #fff;
        padding: 0.8rem 2rem;
        border-radius: 30px;
        text-decoration: none;
        font-weight: 600;
        transition: background 0.3s ease;
        margin-top: 1rem;
      }

      .btn-contact:hover {
        background: #b31547;
      }
    </style>
<div class="top-bar">
    “<span class="highlight">AUMENTE A PERCEPÇÃO DE VALOR DO SEU NEGÓCIO ATRAVÉS DO AUDIOVISUAL</span>”
  </div>
<style>
    body 

    .top-bar {
      background-color: #fff;
      padding: 20px;
      text-align: center;
      font-weight: bold;
      font-size: 14px;
      letter-spacing: 0.5px;
      color: black;
      font-family: 'Poppins', sans-serif;
      font-weight: 600;
      margin-top: 65px;
      padding-left: 29px; 

    }
    
  .highlight {

  text-align: center;
 
  }



  </style>
<a class="wb" href="https://wa.me/5511948838756" target="_blank">
<img alt="WhatsApp" class="w-i" src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg"/>
<span class="w-t">WhatsApp</span>
</a>
<div class="w-st">CAPTAÇÃO | EDIÇÃO | PÓS PRODUÇÃO</div>
<style>
    body {}

 .wb {
    margin-top: 40px;
    margin-bottom: 10px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    background-color: #25D366;
    color: white;
    padding: 6px 31px;
    border-radius: 40px;
    text-decoration: none;
    font-size: 22px;
    font-weight: bold;
    width: 233px;
}

 .w-t {
    display: inline-block;
    filter: drop-shadow(1px 1px 1px black);
    font-family: 'Poppins', sans-serif;
    font-size: 17px;
}

.w-i {
    filter: drop-shadow(1px 1px 2px black);
    margin-right: 6px;
    width: 17%;
}

.w-st {
    margin-top: 0;
    margin-bottom: 27px;
    color: #A4F6BE;
    font-size: 10px;
    letter-spacing: 1px;
    font-family: 'Poppins', sans-serif;
    font-weight: 400;
    }

  </style>
<title>Quem somos?</title>
</section>
<head>
<style>



body {
           /* font-family: Arial, sans-serif;
            background-color: #111111;
            color: #FFFFFF;
            margin: 0;
            padding: 0;
            display: flex;*/
            flex-direction: column;
            align-items: center;
            padding-left: 1px; /* Aumentando a margem lateral esquerda */
            padding-right: 1px; /* Aumentando a margem lateral direita */
        }

      
          header {
              text-align: left;
              padding: 50px 20px;
              max-width: 900px; /* Deixando o texto mais estreito */
              width: 100%;
              margin: 0 auto;
          }
          header h1 {
              font-size: 35px;
              margin: -10px;
              font-family: 'Poppins', sans-serif;
              font-weight: 600;
  
          }
          header p {
              font-size: 17px;
              margin-top: 20px;
             font-family: 'Poppins', sans-serif;
             font-weight: 400;
          }
          .team-container {
            display: flex;
              justify-content: center;
              margin: 50px 0;
              gap: 30px;
              text-align: center;
              flex-wrap: wrap;
             /*  max-width: 1200px;*/
             margin: 0 20px;
              align-items: center;
              float: CENTER;
             
        
          }
          .team-member {
              width: 300px;
              text-align: center;
              margin-bottom: 20px;
          }
          .team-member img {
              width: 300px;
              height: 300px;
              object-fit: cover;
              border-radius: 0%;
          }
          .team-member h3 {
              margin-bottom: 5px;
              font-size: 20px;
             font-family: 'Poppins';
              font-weight: 400;
          }
          .team-member p {
              margin-top: 5px;
              font-size: 14px;
              color: #AAAAAA;
              white-space: nowrap;
              font-family: sans-serif;
             font-weight: 600;
             font-size: 12px;
          }
          .roles {
              font-size: 14px;
              color: #AAAAAA;
              margin-top: 5px;
              white-space: nowrap;
          }
      </style>
</head>
<body>
<header>
<center> <h1>QUEM SOMOS?</h1>
<p>Vitor Matos e Stefany Lima, somos noivos e apaixonados pelo audiovisual.</p>
<p>Lideramos uma produtora de mídia com foco em posicionamento de marca e temos uma visão clara: Buscamos aumentar a percepção de valor dos nossos clientes para que eles possam vender mais caro e atrair os clientes certos. Mais do que produzir vídeos e filmes, temos um desejo genuíno em fazer a diferença no negócio de vocês, com respeito, compromisso, visão empresarial e criativa.</p>
<p>Acreditamos na produção cinematográfica, sempre vamos nos esforçar para criar um trabalho original, e personalizado. É isso que nos move, é isso que nos mantém acordados de dia, e muitas vezes, à noite.</p></center>
</header>
<section class="team-container">
<div class="team-member">
<h3>Vitor Matos</h3>
<img alt="Vitor Matos" src="https://imgur.com/C8JqNx6.jpg"/>
<p class="roles">Diretor Criativo | Editor Sênior | Filmmaker</p>
</div>
<div class="team-member">
<h3>Stefany Lima</h3>
<img alt="Stefany Lima" src="https://imgur.com/BXH8RJJ.jpg"/>
<p class="roles">Diretora Criativa | Roteirista | Comunicadora</p>
</div>
</section>
<body>
<div class="container2">
<h1>PERGUNTAS FREQUENTES</h1>
<details>
<summary>1. Como eu faço para contratar vocês?</summary>
<p>Entre em contato pelo WhatsApp 11948838756 e fale conosco agora mesmo.</p>
</details>
<details>
<summary>2. Caso o projeto exija, vocês têm equipe?</summary>
<p>Sim, contamos com muitos profissionais parceiros para cada etapa das produções caso precise. O seu projeto seria totalmente personalizado.</p>
</details>
<details>
<summary>3. Fazem parcerias com outra empresa?</summary>
<p>Sim, se você tem um bom plano que favorece os dois CNPJs, estamos à disposição.</p>
</details>
<details>
<summary>4. Quero trabalhar com vocês, como faço?</summary>
<p>Envie seu currículo e portfólio de trabalho para o e-mail: contato.stefany.batista.lima @gmail.com</p>
</details>
</div>
</body>
<style>

  body {
      font-family: Poppins, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #000;
      color: white;
      font-weight: 400;
    }

    .container2 {
      max-width: 700px;
      margin: 0 auto;
      padding: 40px 20px;
      text-align: left;
    }

    .container2 h1 {
      text-align: center;
      margin-bottom: 20px;

    }

    details {
      background-color: #6495ED;
      border-radius: 8px;
      margin-bottom: 10px;
      padding: 10px 15px;
      cursor: pointer;
      overflow: hidden;
    }

    summary {
      font-size: 17px;
      outline: none;
    }

    summary::-webkit-details-marker {
      margin-right: 10px;
    }

    details[open] summary {
      color: #fff;
    }

    details p {
      margin-top: 10px;
      color: #f0f0f0;
      animation: fadeExpand 0.4s ease-in-out;
    }

    @keyframes fadeExpand {
      0% {
        opacity: 0;
        transform: scaleY(0.95);
      }
      100% {
        opacity: 1;
        transform: scaleY(1);
      }
    }
  </style>
<div class="pc">
<p> Copyright © 2025 Todos os direitos reservados.</p>
</div>
<style>
  body

 .pc {
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    unicode-bidi: isolate;
    font-family: poppins, sans-serif;
    height: 5vh;
    font-size: 13px;
} 

@media (max-width: 768px) {
  .portfolio {
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
  }

  .video-card {
    width: calc(50% - 0.75rem);
  }

  .video-wrapper {
    padding-top: 177.77%;
  }

  .title {
    font-size: 61px;
    top: 22px;
    margin: 90px;
    margin-top: 125px;
  }

  .subtitle {
    font-size: 10px;
    margin-top: -80px;
  }

  .whatsapp-button {
    width: 52%;
    padding: 7px 31px;
    font-size: 18px;
  }

  .whatsapp-icon {
    width: 24px;
  }

  .team-member {
    width: 90%;
  }

  .team-member img {
    width: 100%;
    height: auto;
  }

  header h1 {
    font-size: 25px;
  }

  header p {
    font-size: 14px;
  }

  .hero-content h1 {
    font-size: 1.8rem;
  }

  .hero-content p {
    font-size: 1rem;
  }

  .modal-content {
    width: 95%;
    height: 60%;
  }

.container2 h1 {
  font-size: 20px;

} 


.container2 {
    max-width: 700px;
    margin: 0 auto;
    padding: 41px 51px;
    text-align: left;
}

.container2 summary {
 font-size: 12px;
  outline: none;

} 
.container2 p  {
 font-size: 12px;
  outline: none;

} 
.pc p  {
 font-size: 10px;
  outline: none;

}
.whatsapp-text {
 font-size: 14px;
}
.w-t {
 font-size: 14px;
}

.highlight {
 font-size: 14px;
}
}

</style>
</body>
