<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Para Mel 💜</title>

<style>

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial, Helvetica, sans-serif;
}

body{
  background:linear-gradient(to bottom,#240046,#3c096c,#10002b,#000);
  color:white;
  overflow-x:hidden;
}

/* FUNDO DE CORAÇÕES */

.hearts{
  position:fixed;
  width:100%;
  height:100%;
  top:0;
  left:0;
  overflow:hidden;
  z-index:-1;
}

.heart{
  position:absolute;
  bottom:-50px;
  color:rgba(255,255,255,0.2);
  animation:float 10s linear infinite;
  font-size:20px;
}

@keyframes float{
  0%{
    transform:translateY(0) rotate(0deg);
    opacity:0;
  }

  10%{
    opacity:1;
  }

  100%{
    transform:translateY(-110vh) rotate(360deg);
    opacity:0;
  }
}

/* CONTAINER */

.container{
  width:90%;
  max-width:1200px;
  margin:auto;
}

/* HERO */

.hero{
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:80px 0;
}

.hero-content{
  max-width:900px;
}

.badge{
  display:inline-block;
  background:rgba(255,255,255,0.08);
  border:1px solid rgba(255,255,255,0.15);
  color:#ffb3ff;
  padding:12px 22px;
  border-radius:50px;
  margin-bottom:30px;
  backdrop-filter:blur(10px);
}

h1{
  font-size:85px;
  line-height:1;
  margin-bottom:30px;
  background:linear-gradient(to right,#ffffff,#ff9de2,#d9b3ff);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
}

.hero p{
  font-size:24px;
  line-height:1.8;
  color:#f0dfff;
  margin-bottom:40px;
}

.btn{
  display:inline-block;
  padding:18px 35px;
  background:linear-gradient(to right,#ff4fc3,#c918ff);
  border-radius:20px;
  text-decoration:none;
  color:white;
  font-size:20px;
  font-weight:bold;
  transition:0.3s;
  box-shadow:0 0 30px rgba(255,0,180,0.3);
}

.btn:hover{
  transform:scale(1.05);
}

/* SEÇÕES */

.section{
  padding:120px 0;
}

.section-title{
  text-align:center;
  margin-bottom:70px;
}

.section-title h2{
  font-size:56px;
  margin-bottom:20px;
  color:#ffd6ff;
}

.section-title p{
  color:#d9b3ff;
  font-size:20px;
}

.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:30px;
}

.card{
  background:rgba(255,255,255,0.05);
  border:1px solid rgba(255,255,255,0.08);
  border-radius:30px;
  padding:40px;
  backdrop-filter:blur(10px);
  transition:0.4s;
}

.card:hover{
  transform:translateY(-10px);
  background:rgba(255,255,255,0.08);
}

.icon{
  font-size:45px;
  margin-bottom:25px;
}

.card h3{
  font-size:30px;
  margin-bottom:18px;
  color:#ffd6ff;
}

.card p{
  color:#f1dfff;
  line-height:1.8;
  font-size:18px;
}

/* DECLARAÇÃO */

.love-box{
  background:rgba(255,255,255,0.06);
  border:1px solid rgba(255,255,255,0.1);
  border-radius:40px;
  padding:70px;
  text-align:center;
  backdrop-filter:blur(10px);
}

.love-box h2{
  font-size:60px;
  margin-bottom:30px;
  color:#fff;
}

.love-box p{
  font-size:24px;
  line-height:2;
  color:#f7e7ff;
}

/* FOOTER */

footer{
  text-align:center;
  padding:50px 20px;
  color:#c8a2ff;
}

/* RESPONSIVO */

@media(max-width:768px){

  h1{
    font-size:55px;
  }

  .hero p{
    font-size:20px;
  }

  .section-title h2{
    font-size:40px;
  }

  .love-box{
    padding:40px 25px;
  }

  .love-box h2{
    font-size:40px;
  }

  .love-box p{
    font-size:20px;
  }

}

</style>
</head>

<body>

<!-- CORAÇÕES -->

<div class="hearts">

  <div class="heart" style="left:5%; animation-delay:0s;">💜</div>
  <div class="heart" style="left:15%; animation-delay:2s;">💖</div>
  <div class="heart" style="left:25%; animation-delay:4s;">💜</div>
  <div class="heart" style="left:35%; animation-delay:1s;">💖</div>
  <div class="heart" style="left:50%; animation-delay:6s;">💜</div>
  <div class="heart" style="left:65%; animation-delay:3s;">💖</div>
  <div class="heart" style="left:75%; animation-delay:5s;">💜</div>
  <div class="heart" style="left:90%; animation-delay:7s;">💖</div>

</div>

<!-- HERO -->

<section class="hero container">

  <div class="hero-content">

    <div class="badge">
      Para a mulher mais linda, inteligente e perfeita do multiverso 💜
    </div>

    <h1>
      TE AMO, MEL 💜
    </h1>

    <p>
      Entre todas as coincidências da vida, você foi a mais bonita.
      Seu sorriso acalma meu caos, seus olhos castanhos claros brilham
      como estrelas douradas no meio da noite, e cada momento ao seu lado
      transforma o mundo em um lugar melhor. 
      Eu te amo mais que tudo, bom dia flor do meio dia.
    </p>

    <a 
    href="https://wa.me/559199138069?text=Obrigada%20meu%20amor%20eu%20amei!!!"
    target="_blank"
    class="btn">
      💌 Falar com meu amor
    </a>

  </div>

</section>

<!-- SEÇÃO -->

<section class="section container">

  <div class="section-title">
    <h2>O que eu amo em você</h2>

    <p>
      Existem milhares de motivos, mas alguns merecem ser eternizados.
    </p>
  </div>

  <div class="cards">

    <div class="card">

      <div class="icon">✨</div>

      <h3>Seu olhar</h3>

      <p>
        Seus olhos castanhos claros têm uma luz que me desmonta completamente.
        Quando você me olha, parece que o universo inteiro fica em silêncio
        só pra eu admirar você.
      </p>

    </div>

    <div class="card">

      <div class="icon">🌙</div>

      <h3>Sua energia</h3>

      <p>
        Você carrega uma força linda, intensa e acolhedora.
        Tem algo em você que transmite paz e profundidade,
        como as águas calmas e misteriosas de Nanã.
      </p>

    </div>

    <div class="card">

      <div class="icon">💜</div>

      <h3>Seu coração</h3>

      <p>
        Você ama de um jeito raro.
        E eu prometo continuar cuidando desse coração
        todos os dias da minha vida, 
        assim como você tem feito comigo, ja disse que a minha missão é retribuir todo o amor q você me faz sentir
      </p>

    </div>

  </div>

</section>

<!-- DECLARAÇÃO -->

<section class="section container">

  <div class="love-box">

    <h2>
      Minha declaração pra você 💖
    </h2>

    <p>
      Mel, você se tornou meu lugar favorito no mundo.<br><br>

      Amar você é fácil.<br>
      Difícil é encontrar palavras suficientes para explicar o quanto você significa pra mim.<br><br>

      Eu amo sua voz, seu jeito, suas manias, sua presença,
      sua força, sua delicadeza e até o jeito que você ocupa meus pensamentos o dia inteiro.<br><br>

      Se algum dia você duvidar do quanto é especial,
      volta aqui e lembra:
      existe alguém nesse mundo que olha pra você como a coisa mais preciosa que a vida poderia oferecer.<br><br>

      E esse alguém sou eu. 💜
    </p>

  </div>

</section>

<footer>
  Feito com amor exclusivamente para Mel 💜
</footer>

</body>
</html>
