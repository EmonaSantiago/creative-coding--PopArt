<body>
  <header>
    <h1 class="logo">CMD MIDTERM</h1>
    <nav class="navigation">
      <a href="" class="">Beoogde leerresultaten</a>
      <a href="" class="">Onderwijsleeromgeving</a>
      <a href="" class="">Toetsing</a>
      <a href="" class="">Gerealiseerde leerresultaten</a>
    </nav>
  </header>

  <section id="hero-section">
    <h1>Communication and Multimedia Design</h1>
  </section>

  <section id="introduction">
    <h2>Midterm</h2>

    <p />

    <p>
      De midterm review 2022 willen we graag inzetten om feedback te krijgen op
      ons onderwijs en met het panel te kijken naar de toekomst van het
      vakgebied en ontwerp-onderwijs. Deze website beschrijft het onderwijs bij
      CMD Amsterdam, onze kritische reflectie hierop en ambities voor de
      toekomst. CMD Amsterdam is een leergemeenschap waarbij studenten, docenten
      en medewerkers met en van elkaar leren. Deze site is daar ook een
      voorbeeld van: de inhoud is verzorgd door docenten en medewerkers (Diantha
      Kinkhouwers, Laura van der Vlies, David de Vries, Jos Kok, Arif Khan,
      Michel Alders, Tatjana Finke en Zuzana van Polen) en het ontwerp is
      gemaakt door studenten van CMD Agency (Alana Eastman, Ryan Zoeters, Nina
      Rijntjes en Pip Harsveld), de minor Web development (Fabienne van den
      Steen, Kai van Wezel en Nathan Bommezijn) van CMD Amsterdam en Justin Lung
      (AD Frontend Design en Development, HvA) onder begeleiding van Joost Faber
      (docent), alles overzien door onze hoofddocent Irene Kamp.
    </p>

    <p />
    <div id="scroll-text">
      <img
        src="https://static.vecteezy.com/system/resources/previews/013/079/618/original/speech-bubble-comic-pop-art-design-png.png"
        alt="pop-art"
        width="200em"
      />
    </div>
  </section>
  <section id="chapters">
    <div class="1.0">
      <h3>1.0 Beoogde leerresultaten</h3>
      <ul>
        <li>1.1 Humanity-centered digital designers</li>
        <li>1.2 Competenties</li>
        <li>1.3 Werkveld en maatschappij</li>
        <li>1.4 Ontwikkelingen</li>
        <li>1.5 Ambities en dilemma’s</li>
      </ul>
    </div>

    <div class="2.0">
      <h3>2.0 Onderwijsleeromgeving</h3>
      <ul>
        <li>2.1 Onderwijsvisie en didactiek</li>
        <li>2.2 Curriculumopbouw</li>
        <li>2.3 Borging onderwijskwaliteit</li>
        <li>2.4 Onderwijs en praktijk</li>
        <li>2.5 Onderwijs en onderzoek</li>
        <li>2.6 Internationalisering</li>
        <li>2.7 Studenten begeleiding</li>
        <li>2.8 Digitale en analoge voorzieningen</li>
        <li>2.9 Ambities en dilemma's</li>
      </ul>
    </div>

    <div class="3.0">
      <h3>3.0 Toetsing</h3>
      <ul>
        <li>3.1 Toetsbeleid en -plan</li>
        <li>3.2 Toetsprogramma en -praktijk</li>
        <li>3.3 Toetsing en feedback</li>
        <li>3.4 Borging en kwaliteit</li>
        <li>3.5 Ambities en dilemma's</li>
      </ul>
    </div>

    <div class="4.0">
      <h3>4.0 Gerealiseerde leerresultaten</h3>
      <ul>
        <li>4.1 Afstudeerproces</li>
        <li>4.2 Borging afstudeerniveau vanuit examencommissie</li>
        <li>4.3 Ambities en dilemma's</li>
      </ul>
    </div>
  </section>

  <footer>
    <!-- <section id="Footer">© 2022 CMD AMSTERDAM</section> -->
    <div id="Footer">
      <div id="scroll-text">
        © 2022 CMD AMSTERDAM
        <div />
      </div>
    </div>
  </footer>
</body>

<style>
  #Footer {
    border: 3px solid black;
    overflow: hidden;
  }

  #scroll-text {
    text-align: right;

    /* animation properties */
    -moz-transform: translateX(-100%);
    -webkit-transform: translateX(-100%);
    transform: translateX(-100%);

    -moz-animation: my-animation 50s linear infinite;
    -webkit-animation: my-animation 50s linear infinite;
    animation: my-animation 50s linear infinite;
  }

  /* for Firefox */
  @-moz-keyframes my-animation {
    from {
      -moz-transform: translateX(-100%);
    }
    to {
      -moz-transform: translateX(100%);
    }
  }

  /* for Chrome */
  @-webkit-keyframes my-animation {
    from {
      -webkit-transform: translateX(-100%);
    }
    to {
      -webkit-transform: translateX(100%);
    }
  }

  @keyframes my-animation {
    from {
      -moz-transform: translateX(-100%);
      -webkit-transform: translateX(-100%);
      transform: translateX(-100%);
    }
    to {
      -moz-transform: translateX(100%);
      -webkit-transform: translateX(100%);
      transform: translateX(100%);
    }
  }

  p {
    width: auto;
  }

  .logo {
    color: white;
  }
  #hero-section h1 {
    top: 0%;
    position: sticky;
    box-shadow: inset 0 0 0 0 #ffffff;
    color: white;
    margin: 0 -0.25rem;
    padding: 0 0.25rem;
    transition: color 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
    font-family: "Raleway", sans-serif;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 100px;
    letter-spacing: 0.1em;
    -webkit-text-fill-color: transparent;
    -webkit-text-stroke-width: 3px;
    -webkit-text-stroke-color: white;
    text-shadow: 8px 8px #530988, 20px 20px #000000;
  }

  #hero-section h1:hover {
    box-shadow: inset 2000px 0 0 0 rgb(241, 241, 39);
    color: black;
  }

  #hero-section {
    background-size: cover;
    background-position: center;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
      url(https://cmd-mid-term.netlify.app/assets/images/hero-image.jpg);
    height: 25rem;
    text-align: center;
    font-size: 2em;
    background-color: white;
    /* Set a specific height */
    min-height: 500px;

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }

  #introduction {
    display: grid;
    grid-template-columns: 1fr 1fr;
    flex-direction: column;
    gap: 2em;
    padding: 4rem 9rem;
    /* flex-direction: row;
    align-items: center;
    justify-content: center; */
    padding: 3rem;
    padding-left: 8.5em;
    gap: 1rem;
    /* display: grid;
      grid-template-columns: 40em 30em;
      grid-template-rows: auto;
      grid-template-areas: "main"; */
    background-color: #fff021;
    border: 10px solid black;
  }

  #introduction h2 {
    font-size: 2rem;
    padding-bottom: 1em;
  }

  #introduction p {
    margin-bottom: 1rem;
  }

  #chapters {
    display: grid;
    grid-template-columns: 1fr 1fr;
    flex-direction: column;
    gap: 3em;
    padding: 4rem 9rem;
    color: white;
    background-size: 100%;
    background-image: url(../vecteezy_halftone-dotted-background_11887512_437.png);
  }

  #chapters div {
    display: flex;
    flex-direction: column;
    border-bottom: 10px solid #fff021;
  }
</style>
