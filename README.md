# English
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Acerca de mí – Lucas David</title>

<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Nunito:wght@400;600;800&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}

body{
  font-family:'Nunito',sans-serif;
  background:#eef3ef;
  padding:30px 15px;
}

/* HEADER */
header{
  text-align:center;
  margin-bottom:30px;
}

header h1{
  font-family:'Bebas Neue',sans-serif;
  font-size:3rem;
  color:#2c3e50;
  letter-spacing:2px;
}

header p{
  color:#6c7a89;
  font-size:0.9rem;
  font-weight:700;
}

.line{
  width:60px;
  height:4px;
  background:#e63946;
  margin:8px auto;
  border-radius:20px;
}

/* CARDS */
.container{
  max-width:500px;
  margin:auto;
  display:flex;
  flex-direction:column;
  gap:20px;
}

.card{
  border-radius:18px;
  padding:20px;
  color:white;
  box-shadow:0 8px 20px rgba(0,0,0,0.15);
  position:relative;
  overflow:hidden;
}

.card::after{
  content:'';
  position:absolute;
  width:120px;
  height:120px;
  background:white;
  opacity:0.1;
  border-radius:50%;
  top:-30px;
  right:-30px;
}

/* COLORS */
.blue{background:linear-gradient(135deg,#1d3557,#457b9d);}
.red{background:linear-gradient(135deg,#c1121f,#e63946);}
.green{background:linear-gradient(135deg,#2d6a4f,#52b788);}
.orange{background:linear-gradient(135deg,#e76f51,#f77f00);}
.purple{background:linear-gradient(135deg,#6a0572,#7b2d8b);}

/* TITLE */
.card h2{
  font-family:'Bebas Neue',sans-serif;
  letter-spacing:1px;
  margin-bottom:10px;
}

/* TAGS */
.tags{
  display:flex;
  flex-wrap:wrap;
  gap:8px;
}

.tag{
  background:rgba(255,255,255,0.25);
  padding:5px 10px;
  border-radius:20px;
  font-size:0.8rem;
  font-weight:700;
  border:1px solid rgba(255,255,255,0.4);
}

/* FOOTER */
footer{
  text-align:center;
  margin-top:25px;
  font-size:0.8rem;
  color:#6c7a89;
}
</style>
</head>

<body>

<header>
  <h1>ACERCA DE MÍ</h1>
  <p>LUCAS DAVID · 8° GRADO · PROYECTO DE INGLÉS</p>
  <div class="line"></div>
</header>

<div class="container">

  <div class="card blue">
    <h2>¿QUIÉN SOY YO?</h2>
    <div class="tags">
      <span class="tag">Lucas David</span>
      <span class="tag">13 años</span>
      <span class="tag">Octavo grado</span>
      <span class="tag">Cumpleaños: 25 de abril</span>
      <span class="tag">Asunción</span>
      <span class="tag">Nuevo capítulo</span>
    </div>
  </div>

  <div class="card red">
    <h2>RUTINA DIARIA</h2>
    <div class="tags">
      <span class="tag">Horario escolar: 7:00–12:00</span>
      <span class="tag">Inglés: 13:00–16:00</span>
      <span class="tag">Trabajar con mi hermana</span>
      <span class="tag">Fines de semana: aire libre</span>
      <span class="tag">Estadio</span>
      <span class="tag">Cena con mamá</span>
    </div>
  </div>

  <div class="card green">
    <h2>FAMILIA</h2>
    <div class="tags">
      <span class="tag">2 hermanas + 1 hermano</span>
      <span class="tag">Hermana en España</span>
      <span class="tag">Hermana mayor: trabajo</span>
      <span class="tag">Mamá: Asunción</span>
      <span class="tag">Papá: afuera</span>
      <span class="tag">Perro: Ares</span>
    </div>
  </div>

  <div class="card orange">
    <h2>CULTURA Y RAÍCES</h2>
    <div class="tags">
      <span class="tag">Mamá paraguaya</span>
      <span class="tag">Papá argentino</span>
      <span class="tag">Tereré</span>
      <span class="tag">Chipa · Mbeju</span>
      <span class="tag">Asado</span>
      <span class="tag">Dulce de leche</span>
      <span class="tag">Fútbol ⚽</span>
    </div>
  </div>

  <div class="card purple">
    <h2>PERSONALIDAD</h2>
    <div class="tags">
      <span class="tag">Responsable</span>
      <span class="tag">Orgullo nacional</span>
      <span class="tag">Autoconsciente</span>
      <span class="tag">Activo</span>
      <span class="tag">Mi habitación = hábitat</span>
      <span class="tag">Creciente</span>
    </div>
  </div>

</div>

<footer>
🇵🇾 Paraguay · 🇦🇷 Argentina — Una vida a la vez desafiante y hermosa ✨
</footer>

</body>
</html>
