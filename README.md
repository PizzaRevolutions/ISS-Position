# 🛰️ ISS Tracker 3D

## 🇮🇹 Italiano

### Descrizione
Questa applicazione web visualizza la posizione in tempo reale della **Stazione Spaziale Internazionale (ISS)** su un globo 3D interattivo. Il progetto utilizza tecnologie web moderne ed esteticamente curate per offrire un'esperienza immersiva "spaziale".

### Funzionalità
- **Globo 3D Interattivo**: Utilizza la libreria `Globe.gl` per visualizzare la Terra.
- **Dati in Tempo Reale**: Ottiene la posizione (Latitudine, Longitudine, Altitudine, Velocità) dall'API pubblica `wheretheiss.at` ogni 3 secondi.
- **Tracciamento Percorso**: Disegna la scia rossa del percorso orbitale della ISS.
- **Interfaccia a Tema Spazio**: Grafica curata con font sci-fi ('Orbitron'), sfondo stellato procedurale e modalità scura.

### Come Funziona
1. **Frontend**: HTML5, CSS3, JavaScript.
2. **Librerie**:
   - `Globe.gl` (basato su Three.js) per il rendering 3D.
   - `jQuery` per le chiamate AJAX asincrone.
3. **Logica**: All'apertura, il globo si centra sulla posizione della ISS. Un timer interroga l'API ogni 3 secondi e aggiorna la posizione dell'icona e della tabella dati, tracciando una linea storica del movimento.

---

## 🇬🇧 English

### Description
This web application visualizes the real-time position of the **International Space Station (ISS)** on an interactive 3D globe. The project uses modern web technologies and polished aesthetics to provide an immersive "space" experience.

### Features
- **Interactive 3D Globe**: Uses the `Globe.gl` library to render the Earth.
- **Real-Time Data**: Fetches position (Latitude, Longitude, Altitude, Velocity) from the public `wheretheiss.at` API every 3 seconds.
- **Path Tracking**: Draws a red trail of the ISS orbital path.
- **Space Themed Interface**: Polished graphics with sci-fi font ('Orbitron'), procedural starry background, and dark mode.

### How it Works
1. **Frontend**: HTML5, CSS3, JavaScript.
2. **Libraries**:
   - `Globe.gl` (based on Three.js) for 3D rendering.
   - `jQuery` for asynchronous AJAX calls.
3. **Logic**: Upon opening, the globe focuses on the ISS position. A timer queries the API every 3 seconds and updates the icon position and data table, tracing a historical line of movement.