<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Tu Rincón Musical</title>
  <style>
    :root{
      --primario: #6841b1;
      --secundario: #e1c1f7;
      --acento: #f6d7ed;
      --claro: #fff;
    }
    *{box-sizing:border-box;}
    body {
      margin: 0;
      min-height: 100vh;
      font-family: 'Poppins', Arial, sans-serif;
      background: linear-gradient(180deg, var(--primario), var(--secundario));
      color: #260A40;
      padding: 0;
    }
    header{
      text-align: center;
      padding: 32px 0 12px 0;
    }
    header h1{
      margin: 0;
      font-size: 2.4rem;
      color: var(--claro);
      text-shadow: 0 4px 30px rgba(0,0,0,0.18);
    }
    header p{
      margin: 10px 0 0;
      font-size: 1.2rem;
      color: var(--acento);
    }
    section{
      max-width: 900px;
      margin: 24px auto;
      background: rgba(255,255,255,0.08);
      border-radius: 20px;
      padding: 24px;
      box-shadow: 0 10px 38px rgba(0,0,0,0.12);
    }
    .galeria{
      display: flex;
      gap: 18px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .foto{
      width: 220px;
      height: 320px;
      background: var(--claro);
      border-radius: 14px;
      overflow: hidden;
      box-shadow: 0 8px 30px rgba(0,0,0,0.09);
      border: 3px solid var(--acento);
      margin-bottom: 14px;
    }
    .foto img{
      width:100%;
      height:100%;
      object-fit:cover;
      display:block;
    }
    .audio-list{
      display: flex;
      flex-direction: column;
      gap: 22px;
      margin-top: 14px;
      align-items: center;
    }
    .audio-box{
      display: flex;
      align-items: center;
      gap: 12px;
      background: rgba(255,255,255,0.15);
      border-radius: 10px;
      padding: 10px 18px;
    }
    .audio-box button{
      background: var(--primario);
      color: var(--claro);
      border: none;
      border-radius: 8px;
      padding: 6px 18px;
      cursor: pointer;
      font-size: 1rem;
    }
    footer{
      text-align: center;
      color: var(--claro);
      background: var(--primario);
      margin-top: 40px;
      padding: 18px 0;
      border-top-left-radius:20px;
      border-top-right-radius:20px;
      box-shadow: 0 -4px 18px rgba(0,0,0,0.11);
    }
    @media (max-width:700px){.foto{width:45vw;height:65vw;} section{padding:8px;} header{padding:14px 0 4px 0;} }
  </style>
</head>
<body>
  <header>
    <h1>nuestro mundo musical 🎵</h1>
    <p>Bienvenido a mi espacio de música y recuerdos.</p>
  </header>
  <section>
    <h2>Galería de Imágenes</h2>
    <div class="galeria">
      <div class="foto"><img src="violuna.jpeg" alt="Foto especial"></div>
      <div class="foto"><img src="Violetta live.jpeg" alt="Mariposa animada"></div>
      <div class="foto"><img src="Leon and Violetta.jpeg" alt="Lutteo"></div>
      <div class="foto"><img src="Lutteo.jpeg" alt="leonetta"></div>
    </div>
  </section>
  <section>
    <h2>Mis Canciones</h2>
    <div class="audio-list">
     </div>
      <div class="audio-box">
        <audio id="audio2" controls preload="none">
          <source src="te esperare.mp3" type="audio/mpeg">
      </div>
      <div class="audio-box">
        <audio id="audio2" controls preload="none">
          <source src="eres.mp3" type="audio/mpeg">
        </audio>
         </div>
      <div class="audio-box">
        <audio id="audio2" controls preload="none">
          <source src="mitad y mitad.mp3" type="audio/mpeg">
        <button onclick="document.getElementById('audio2').play()">▶ Reproducir</button>
      </div>https://tuusuario.github.io/mi-sitio-musical/
    </div>¡Hola! Te comparto mi página de música 🎵

1. Descarga todos los archivos adjuntos.
2. Guarda el archivo musica.html junto con las imágenes y canciones en una misma carpeta.
3. Haz doble clic en musica.html para verlo en tu navegador.
  </section>
  <footer>https://mi-mundo.github.io/mi-sitio-musical/
    <!-- En el lugar donde quieras el enlace -->
<a href="musica.html" target="_blank">Accede a Nuestro Mundo Musical aquí</musica/>
    &copy; 2025 Tu Rincón Musical | Diseñado por Judith
  </footer>
</body>
</html>
---
permalink: /404.html
---
