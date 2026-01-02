<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mapa UniAnchieta – Jundiaí</title>
  <link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #1e3c72, #982a65ff);
      color: white;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    .info-box {
      text-align: center;
      padding: 20px;
    }

    #map {
      height: 60vh;
      margin: 0 auto;
      width: 90%;
      border: 3px solid white;
      border-radius: 10px;
    }

    footer {
      margin-top: auto;
      background: rgba(0, 0, 0, 0.8);
      color: white;
      text-align: center;
      padding: 10px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="info-box">
    <h2>Mapa UniAnchieta – Jundiaí</h2>
    <p>Campus Residencial Anchieta com localização em tempo real.</p>
  </div>

  <div id="map"></div>

  <footer>
    Desenvolvido por Jéssica Thais Baccaro 👍
  </footer>

  <script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
  <script>
    const map = L.map('map').setView([-23.17328, -46.91183], 17);

    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      attribution: '© OpenStreetMap'
    }).addTo(map);

    const pontos = [
      { nome: "Prédio 1", coords: [-23.1735, -46.9120] },
      { nome: "Prédio 2", coords: [-23.1733, -46.9119], popup: "Estudantes de Análise e Desenvolvimento de Sistemas e outros cursos" },
      { nome: "Prédio 3", coords: [-23.1730, -46.9121] },
      { nome: "Prédio 4", coords: [-23.1732, -46.9123] },
      { nome: "Cantina / Food Truck", coords: [-23.1734, -46.9122] },
      { nome: "Biblioteca / Anfiteatro", coords: [-23.1731, -46.9118] }
    ];

    pontos.forEach(p => {
      const texto = p.popup ? `<b>${p.nome}</b><br>${p.popup}` : `<b>${p.nome}</b>`;
      L.marker(p.coords).addTo(map).bindPopup(texto);
    });

    const redIcon = L.icon({
      iconUrl: 'https://cdn-icons-png.flaticon.com/512/684/684908.png',
      iconSize: [32, 32],
      iconAnchor: [16, 32],
      popupAnchor: [0, -32]
    });

    map.locate({ setView: true, maxZoom: 17 });

    map.on('locationfound', function (e) {
      L.marker(e.latlng, { icon: redIcon }).addTo(map)
        .bindPopup("Você está aqui").openPopup();
      L.circle(e.latlng, { radius: e.accuracy / 2 }).addTo(map);
    });

    map.on('locationerror', function () {
      alert("Não foi possível obter sua localização. Verifique as permissões do navegador.");
    });
  </script>
</body>
</html>
