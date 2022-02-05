<!-- JS -->
<script>
  import seahorses from "/static/assets/images/seahorses.png";
  import coquillage_1 from "/static/assets/images/coquillage_1.png";
  import coquillage_2 from "/static/assets/images/coquillage_2.png";
  import music from "/static/assets/audio/Mariage_d'Amour-Paul_de_Senneville.mp3";
</script>

<!-- HTML -->
<main>
  <audio src={music} autoplay loop controls></audio>
  <header>
    <h1>Faire-part de mariage</h1>
    <p>Nous aimerions vous inviter à nous rejoindre à bord de notre aventure contre vents et marée nous allons nous
      marier</p>
    <h2>Sous le theme Marin</h2>
    <img src={seahorses} alt="">
    <h3>Samedi le 6 août 2022 à <u>16:30</u></h3>
  </header>
  <div class="info">
    <h2>Informations</h2>
    <p>Notre union sera célébrée sur un terrain privé au bord de l’eau, par notre très charmante amie Manon Lyonnais
      qui se fera un honneur d’être notre célébrante. </p>
    <p>Lieu du mariage au <a target="_blank"
                             href="https://www.google.com/maps/place/78+Rue+Notre-Dame,+Saint-Damien,+QC+J5W+3X8/@45.7875558,-73.3990384,17z/data=!3m1!4b1!4m5!3m4!1s0x4cc8ef11de091177:0x60f41106258dcb77!8m2!3d45.7875558!4d-73.3968497">78
      rue, Notre-Dame à Saint-Sulpice</a></p>
    <div class="map">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2782.183279489529!2d-73.39903838408!3d45.7875557791061!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4cc8ef11de091177%3A0x60f41106258dcb77!2s78%20Rue%20Notre-Dame%2C%20Saint-Damien%2C%20QC%20J5W%203X8!5e0!3m2!1sfr!2sca!4v1644053245101!5m2!1sfr!2sca"
        width="400" height="400" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
    <p>Le stationnement pour les véhicules est au <u>81 Notre-Dame à St-Sulpice</u>, sur terrain privé, vous n’avez
      qu’à traverser la rue pour vous rendre sur les lieux de la réception.</p>
    <p>Nous vous demandons d’être présent pour <u>15:30</u>.</p>
    <div class="images">
      <img src={coquillage_1} alt="coquillage"><img src={coquillage_2} alt="coquillage">
    </div>
    <p>afin de ne rien manqué de cette magnifique fête au décor enchanteur animé par notre DJ Michel Lajoie, qui ne
      manquera pas de souligner cet évènement joyeux. </p>
    <p>Après l’échange de nos vœux, nous vous invitons à prendre un verre de mousseux en notre honneur avant de
      poursuivre avec un repas qui nous espérons sera combler vos papille gustative.</p>
  </div>
</main>

<!-- CSS -->
<style lang="scss">
  main {
    background-image: url("static/assets/images/starfishes_seashells_bg.jpg");
    background-size: cover;
    background-attachment: fixed;
    min-height: 100vh;
    padding: 20px;

    audio {
      margin-bottom: 20px;
    }

    header {
      background: rgba(25, 86, 86, 0.3);
      margin-bottom: 25px;

      h1, h2, p {
        margin-bottom: 10px;
      }

      h2 {
        color: #0303b7;
      }

      img {
        width: 200px;
      }
    }

    .info {
      background: rgba(68, 75, 24, 0.3);
      border-radius: 25px;
      padding: 10px;

      h2 {
        margin-bottom: 20px;
      }

      p {
        margin-bottom: 10px;
      }

      .map {
        margin: 20px auto;

        iframe {
          border: #f5c084 5px solid !important;
          border-radius: 20px;
        }
      }

      .images {
        margin: 20px auto;
        display: flex;
        justify-content: space-around;
        align-items: center;

        img {
          width: 200px;
          height: max-content;
        }
      }
    }

    header, .info {
      width: 45%;
      text-align: center;
      border-radius: 25px;
      padding: 10px;


      @media screen and (max-width: 900px) {
        width: 60%;
      }

      @media screen and (max-width: 666px) {
        width: 70%;
      }

      @media screen and (max-width: 590px) {
        width: 95%;
      }
    }
  }
</style>
