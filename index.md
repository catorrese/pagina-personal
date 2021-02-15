<!DOCTYPE html>
<head>
  <meta charset="UTF-8" />
  <title>Mi Página Personal</title>
  <link rel="icon" type="image/png" href="../assets/Foto Personal.png" />
</head>

<body style="background-color: rgb(243, 234, 234)">
  <header style="background-color: rgb(240, 224, 224)">
    <table>
      <tr>
        <td width="700">
          <img
            src="/assets/Foto Personal.png"
            alt="Fotografia Personal"
            height="185"
            width="147"
          />
        </td>
        <td><h1>Mi Página Personal</h1></td>
      </tr>
    </table>
  </header>

  <nav style="background-color: rgb(240, 224, 224)">
    <table cellspacing="15">
      <tr>
        <td width="100" align="center"><a href="#Bienvenida">Bienvenida</a></td>
        <td align="center"><a href="#Datos_B">Datos biográficos</a></td>
        <td align="center"><a href="#Datos_A">Datos académicos</a></td>
        <td align="center"><a href="#Sitios">Sitios de interés</a></td>
        <td width="100" align="center"><a href="#Contactame">Contáctame</a></td>
        <td width="50" align="center"><a href="#Contacto">Contacto</a></td>
      </tr>
    </table>
  </nav>
  <br />

  <main>
    <section id="Bienvenida">
      <h2>Bienvenidos!</h2>
      <p>
        Les doy la bienvenida a mi página personal! Mi nombre es Carlos Torres y
        soy estudiante de Ingeniería de Sistemas y Computación en la Universidad
        de Los Andes. Me apasiona la tecnología, el deporte y los videojuegos.
      </p>
      <p>
        A continuación podrán encontrar más información acerca de mí, desde
        datos académicos hasta gustos e intereses personales. Los invito a que
        continúen leyendo y me contacten si tienen alguna duda.
      </p>
    </section>
    <br />

    <section id="Datos_B">
      <h2>Datos Biográficos</h2>
      <p>A continuación encontrarán información y datos biográficos míos:</p>
      <table border="1" cellpadding="3">
        <tr>
          <th>Nombres</th>
          <th>Apellidos</th>
          <th>Edad</th>
          <th>Sexo</th>
          <th>Estatura</th>
          <th>Fecha de nacimiento</th>
          <th>Nacionalidad</th>
          <th>Lugar de residencia</th>
          <th>Grupo sanguíneo</th>
          <th>RH</th>
        </tr>
        <tr>
          <td>Carlos Andrés</td>
          <td>Torres Echeverría</td>
          <td>21 años</td>
          <td>Masculino</td>
          <td align="center">1.70 m</td>
          <td align="center">21/01/2000</td>
          <td align="center">Colombiano</td>
          <td align="center">Bogotá, D.C</td>
          <td align="center">A</td>
          <td align="center">-</td>
        </tr>
      </table>
    </section>
    <br />

    <section id="Datos_A">
      <h2>Datos Académicos</h2>
      <p>A continuación encontrarán información y datos académicos míos:</p>
      <ul>
        <li>Universidad: Los Andes</li>
        <li>Programa: Ingeniería de Sistemas y Computación</li>
        <li>Nivel: Pregrado</li>
        <li>Semestre: 7mo</li>
        <li>Créditos: 103</li>
        <li>PGA: 4.03</li>
      </ul>
    </section>
    <br />

    <section id="Sitios">
      <h2>Sitios de Interés</h2>
      <p>
        A continuación encontrarán mis sitios interés en la web, así como mis
        videos e imágenes favoritas.
      </p>
      <br />

      <h3>Videos Favoritos</h3>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/CID-sYQNCew"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/5b8quYrnlTg"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/zF5Ddo9JdpY"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
      <br />

      <h3>Imágenes Favoritas</h3>
      <img
        src="../assets/Berserk Wallpaper.jpg"
        alt="Berserk Wallpaper"
        height="250"
        width="450"
      />
      <img
        src="../assets/AoT Wallpaper.png"
        alt="AoT Wallpaper"
        height="250"
        width="450"
      />
      <img
        src="../assets/Arthas Wallpaper.jpg"
        alt="Arthas Wallpaper"
        height="250"
        width="450"
      />
      <img
        src="../assets/LoL Wallpaper.jpg"
        alt="LoL Wallpaper"
        height="250"
        width="450"
      />
      <br />

      <h3>Enlaces de Interés</h3>
      <ul>
        <li>
          Plataforma de apoyo en matemáticas:
          <a href="https://www.wolframalpha.com/" target="_blank"
            >WolframAlpha</a
          >
        </li>
        <li>
          Plataforma para ver ánime legal:
          <a href="https://www.crunchyroll.com/es" target="_blank"
            >Crunchyroll</a
          >
        </li>
        <li>
          Plataforma para escuchar música:
          <a href="https://soundcloud.com/" target="_blank">Soundcloud</a>
        </li>
      </ul>
    </section>
    <br />

    <section id="Contactame">
      <h2>Contáctame</h2>
      <p>
        Si gustas enviarme un mensaje, a continuación puedes dejarlo junto con
        tus datos:
      </p>
      <form>
        <div>
          <label for="nombre">Nombre</label>
          <br />
          <input type="text" id="nombre" />
        </div>
        <div>
          <label for="correo">Correo</label>
          <br />
          <input type="text" id="correo" />
        </div>
        <div>
          <label for="mensaje">Mensaje</label>
          <br />
          <textarea id="mensaje"></textarea>
        </div>
        <div>
          <input type="reset" value="Borrar datos" />
          <input type="submit" value="Enviar" />
        </div>
      </form>
    </section>
  </main>
  <br />

  <footer id="Contacto" style="background-color: rgb(240, 224, 224)">
    <table cellpadding="15" align="center">
      <tr>
        <td align="center">
          <a
            href="https://www.facebook.com/people/Carlos-Torres/100001250455546"
            target="_blank"
            ><img
              src="../assets/facebook logo.png"
              alt="Perfil de Facebook"
              height="30"
              width="30"
          /></a>
        </td>
        <td align="center">
          <a href="https://www.instagram.com/carlostorres74/" target="_blank"
            ><img
              src="../assets/instagram logo.png"
              alt="Perfil de Instagram"
              height="30"
              width="30"
          /></a>
        </td>
        <td align="center">
          <a
            href="https://www.youtube.com/user/WereW0lf74/featured"
            target="_blank"
            ><img
              src="../assets/youtube logo.png"
              alt="Canal de Youtube"
              height="30"
              width="30"
          /></a>
        </td>
      </tr>
      <tr>
        <td>Cel: +57 3212373353</td>
        <td></td>
        <td>
          <a href="mailto:torres115.935@gmail.com">torres115.935@gmail.com</a>
        </td>
      </tr>
    </table>
  </footer>
</body>
