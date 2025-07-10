# ❤️ Web del primer Aniversari junts
 
Una pàgina web romàntica, interactiva, creada amb Astro, per celebrar el nostre aniversari. Inclou un reproductor de música avançat, vídeo embed de YouTube i seccions personalitzades per compartir els nostres moments més especials.

## ✨ Característiques principals

- 🎵 **Reproductor Musical Avançat** - Playlist completa amb controls professionals
- 🎥 **Vídeo YouTube Embed** - Reprodueix directament des de YouTube
- 💝 **Missatge Personalitzat** - Paraules d'amor des del cor
- ✨ **Animacions Fluides** - Transicions optimitzades per màxima fluidesa
- 📱 **Disseny Responsiu** - Perfecte en mòbil i desktop
- 🎛️ **Controls de Reproductor** - Minimitzar, tancar i reobrir

## 🚀 Estructura del Projecte

```text
/
├── public/
│   └── music/           # Playlist de cançons
│       ├── song1.mp3
│       ├── song2.mp3
│       ├── song3.mp3
│       ├── song4.mp3
│       └── song5.mp3
├── src/
│   ├── components/      # Components reutilitzables
│   │   ├── VideoSection.astro      # Component de vídeo YouTube
│   │   └── PlaylistPlayer.astro    # Reproductor musical avançat
│   ├── layouts/         # Layout base
│   │   └── Layout.astro
│   └── pages/           # Pàgines de l'aplicació
│       └── index.astro
└── package.json
```

## 🎯 Configuració

1. **Configura el vídeo de YouTube:**
   - Edita `src/pages/index.astro`
   - Canvia la variable `videoSrc` per la teva URL d'embed de YouTube
   - Format: `https://www.youtube.com/embed/VIDEO_ID?si=HASH`

2. **Afegeix la música:**
   - Copia les cançons a `public/music/`
   - Anomena-les com `song1.mp3`, `song2.mp3`, etc.
   - Actualitza la playlist a `src/pages/index.astro` amb títols i artistes

3. **Personalitza els textos:**
   - Edita `src/pages/index.astro` per canviar missatges, títols i dedicatòries

## 🧞 Comandos

Tots els comandos s'executen des de l'arrel del projecte:

| Comando                   | Acció                                            |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instal·la les dependències                      |
| `npm run start`           | Inicia el servidor local a `localhost:4321`     |


## 📱 Funcionalitats del Reproductor

### 🎵 Controls Principals
- ⏯️ **Play/Pause** - Control de reproducció principal
- ⏮️ **Anterior/Següent** - Navegació entre cançons  
- 🔀 **Mode Shuffle** - Reproducció aleatòria
- 🔊 **Control de Volum** - Ajusta el volum o silencia
- 📊 **Barra de Progrés** - Salta a qualsevol moment de la cançó

### 🎛️ Controls de Finestra
- 📋 **Toggle Playlist** - Mostra/oculta la llista de cançons
- ➖ **Minimitzar** - Redueix el reproductor mantenint la música
- ❌ **Tancar** - Oculta completament el reproductor
- 🎵 **Reobrir** - Botó flotant per tornar a mostrar el reproductor

### ✨ Característiques Avançades
- 📱 **Disseny Responsiu** - S'adapta perfectament a mòbil
- 🎨 **Animacions Fluides** - Transicions optimitzades per màxim rendiment
- 🎵 **Indicadors Visuals** - Mostra la cançó activa amb icones animades
- 📊 **Comptador de Cançons** - Visualitza posició actual a la playlist

## 🚀 Desplegament

1. Executa `npm run build`
2. Puja la carpeta `dist/` al teu servidor web
3. Assegura't que els arxius de música a `public/music/` estiguin inclosos
4. Verifica que la URL de YouTube Embed sigui accessible

## 🎬 Configuració del Vídeo YouTube

Per canviar el vídeo, edita la variable `videoSrc` a `src/pages/index.astro`:

```javascript
const videoSrc = "https://www.youtube.com/embed/VIDEO_ID?si=HASH";
```

*Creat amb ❤️ ny Gabriel Borrás Serra*