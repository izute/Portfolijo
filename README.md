# Portfolio
<!DOCTYPE html>
<html lang="lv">
<head>
  <title>Mans datorikas portfelis</title>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <!-- W3.CSS pamatbibliotēka -->
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css" />
  <!-- Papildus stili (ja nepieciešams) -->
  <style>
    body,h1,h2,h3,h4,h5,h6 {
      font-family: "Segoe UI", Arial, sans-serif;
    }
    .w3-bar .w3-button {
      text-decoration: none;
    }
  </style>
</head>
<body>

<!-- Navigācijas josla (līdzīga Band paraugam) -->
<div class="w3-top">
    <div class="w3-bar w3-black w3-card" style="display: flex; justify-content: center;">
      <a href="#home" class="w3-bar-item w3-button w3-padding-large">Sākums</a>
      <a href="#temas" class="w3-bar-item w3-button w3-padding-large">1. semestra tēmas</a>
      <a href="#gimp" class="w3-bar-item w3-button w3-padding-large">GIMP darbi</a>
      <a href="#modelesana" class="w3-bar-item w3-button w3-padding-large">3D modelēšana</a>
      <a href="#video" class="w3-bar-item w3-button w3-padding-large">Video projekts</a>
    </div>
  </div>
  

<!-- Sākuma galvene ar fona krāsu/attēlu -->
<header class="w3-container w3-blue w3-center" style="padding:128px 16px" id="home">
  <h1 class="w3-margin w3-jumbo">Mans datorikas portfolio</h1>
  <p class="w3-xlarge">Šeit apkopoti mani darbi un mācību progress 10. klasē</p>
</header>

<!-- 1. semestra tēmas un vērtējumi -->
<div class="w3-container w3-padding-64 w3-light-grey" id="tēmas">
  <h2 class="w3-center">1. semestrī paredzētie datorikas vērtējumi</h2>
  <p class="w3-center">Tabula ar plānotajiem uzdevumiem, iesniegšanas termiņiem un vērtējumu informāciju.</p>

  <div class="w3-responsive w3-card-4 w3-margin-top">
    <table class="w3-table w3-striped w3-bordered">
      <thead>
        <tr class="w3-blue">
          <th>Tēma</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Rastrgrafikas darbs (GIMP)</td>
        </tr>
        <tr>
          <td>Grupu darbs, ieskaite 3D modeļa izdrukai</td>
        </tr>
        <tr>
          <td>Pārbaudes darbs par MS Word</td>
        </tr>
        <tr>
          <td>Video projekts (uzdevums mapē 1810)</td>
        </tr>
        <tr>
          <td>Papildus uzdevums – vektorgrafikas darbs (Inkscape)</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<!-- GIMP darbi (rastrgrafikas sadaļa) -->
<div class="w3-container w3-padding-64" id="gimp">
    <h2 class="w3-center">GIMP darbi</h2>
    <p class="w3-center"> Mums bija jāizveido vairākas bildes 
        gimp vidē, apakšā pievienoju divas no tām 
        bildēm, kuras tika novērtētas ar ballēm.</p>
  
    <!-- Flex konteineris, kas centrē iekšējos elementus -->
    <div class="w3-row-padding" style="display: flex; justify-content: center; margin-top:32px;">
      <div class="w3-col m4 w3-center">
        <img src="Capture.PNG" alt="GIMP darbs 1" style="width:100%">
        <p> Bildi veidoju pēc parauga un</p>
      </div>
      <div class="w3-col m4 w3-center">
        <img src="ziloni gimp.PNG" alt="GIMP darbs 2" style="width:100%">
        <p>Apraksts otrajam darbam</p>
      </div>
    </div>
  </div>
  

<!-- 3D modelēšana (Grupu darbs) -->
<div class="w3-container w3-padding-64 w3-light-grey" id="modelēšana">
  <h2 class="w3-center">3D modelēšana</h2>
  <p class="w3-center">Grupu darbs un 3D modeļu izdruka.</p>
  <div class="w3-row-padding" style="margin-top:32px">
    <div class="w3-col m6">
      <img src="images/3d_model1.jpg" alt="3D modelis 1" style="width:100%">
      <p>Īss apraksts par 3D modeli</p>
    </div>
    <div class="w3-col m6">
      <img src="images/3d_model2.jpg" alt="3D modelis 2" style="width:100%">
      <p>Īss apraksts par 3D modeli</p>
    </div>
  </div>
</div>

<!-- Video projekts -->
<div class="w3-container w3-padding-64" id="video">
  <h2 class="w3-center">Video projekts</h2>
  <p class="w3-center">Plānotais video projekts (uzdevums mapē 1810).</p>
  <div class="w3-content" style="max-width:600px">
    <!-- Šeit vari ievietot YouTube video iFrame vai attēlus no sava projekta -->
    <div class="w3-center w3-padding-16">
      <iframe width="100%" height="315" src="https://www.youtube.com/embed/VIDEO_ID" 
              title="YouTube video" frameborder="0" allowfullscreen>
      </iframe>
    </div>
    <p>
      Īss apraksts par video projekta mērķi un saturu: 
      <br>
      - Video sižets
      <br>
      - Montāžas rīki
      <br>
      - Prezentācijas datums
    </p>
  </div>
</div>

<!-- Kājene -->
<footer class="w3-container w3-black w3-center w3-padding-32">
  <p>Veidots ar <a href="https://www.w3schools.com/w3css/" target="_blank">W3.CSS</a> “Band” stila palīdzību</p>
</footer>

</body>
</html>
