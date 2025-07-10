## 📁 Estructura d'arxius
```
public/
├── images/              # Posa aquí les fotos del teu carrusel
│   ├── photo1.jpg
│   ├── photo2.jpg
│   ├── photo3.jpg
│   ├── photo4.jpg
│   ├── photo5.jpg
│   └── video-poster.jpg # Imatge de portada per al vídeo
├── videos/
│   └── our-video.mp4    # Posa aquí el teu vídeo especial
└── music/
    ├── song1.mp3        # Primera cançó especial
    ├── song2.mp3        # Segona cançó especial  
    ├── song3.mp3        # Tercera cançó especial
    └── song4.mp3        # Quarta cançó especial
```

## 🖼️ Com afegir les teves fotos

1. Copia les teves fotos favorites a la carpeta `public/images/`
2. Anomena-les com `photo1.jpg`, `photo2.jpg`, etc.
3. Formats recomanats: JPG, PNG
4. Mida recomanada: 1200x800px o similar

## 🎥 Com afegir el teu vídeo

1. Posa el teu vídeo a la carpeta `public/videos/`
2. Anomena'l com `our-video.mp4`
3. Formats compatibles: MP4, WebM
4. Crea una imatge de portada anomenada `video-poster.jpg` a `public/images/`

## 🎵 Com afegir les vostres cançons especials

1. Posa els teus arxius de música a la carpeta `public/music/`
2. Anomena'ls com:
   - `song1.mp3` (La vostra primera cançó)
   - `song2.mp3` (Quan us vau enamorar)  
   - `song3.mp3` (Sempre junts)
   - `song4.mp3` (El vostre futur)
3. Formats compatibles: MP3, WAV, OGG, M4A
4. Mida recomanada per cançó: menys de 10MB
5. Qualitat recomanada: 128-320 kbps

### Personalitzar la playlist
Per canviar els títols o afegir més cançons, edita `src/pages/index.astro`:

```astro
const playlist = [
  {
    src: "/music/song1.mp3",
    title: "El teu títol personalitzat",
    artist: "La teva descripció"
  },
  // Afegeix més cançons aquí...
];
```

## ✏️ Personalitzar el contingut

### Canviar el títol i missatge
Edita l'arxiu `src/pages/index.astro`:

```astro
<h1 class="hero-title">El Nostre Aniversari</h1>  <!-- Canvia aquí el títol -->
<p class="hero-subtitle">El teu missatge personalitzat aquí</p>  <!-- Canvia el subtítol -->
```

### Canviar el missatge final
A la secció "Per al Meu Amor", personalitza:

```astro
<h2 class="message-title">Per al Meu Amor</h2>  <!-- Canvia el títol -->
<p>El teu missatge personalitzat aquí...</p>  <!-- Canvia el missatge -->
```

### Afegir més fotos
A `src/pages/index.astro`, modifica l'array de fotos:

```astro
const photos = [
  '/images/photo1.jpg',
  '/images/photo2.jpg',
  '/images/photo3.jpg',
  '/images/photo4.jpg',
  '/images/photo5.jpg',
  '/images/photo6.jpg',  // Afegeix més fotos aquí
];
```

## 🚀 Com executar la web

1. Obre un terminal a la carpeta del projecte
2. Executa: `npm run start` o `npm run dev`
3. Obre el teu navegador a `http://localhost:4321`

## 🎨 Característiques incloses

- ✨ Carrusel de fotos interactiu amb navegació
- 🎥 Secció de vídeo amb controls personalitzats
- 🎵 Reproductor de playlist complet amb múltiples cançons
  - ⏯️ Controls de reproducció (play/pause, anterior/següent)
  - 🔀 Mode aleatori (shuffle)
  - 🔊 Control de volum amb silenci
  - 📊 Barra de progrés interactiva
  - 📋 Llista de reproducció desplegable
  - 🔄 Reproducció automàtica en bucle
- 📱 Disseny completament responsiu (mòbil i desktop)
- 💝 Disseny romàntic amb gradients i animacions
- ❤️ Animacions de cors i efectes visuals
- 🎯 Navegació suau entre seccions

## 💡 Consells

- Optimitza les teves imatges abans de pujar-les (usa eines com TinyPNG)
- Mantén els vídeos en una mida raonable (màxim 50MB)
- Prova la web en diferents dispositius
- Pots canviar els colors editant les variables CSS a `src/layouts/Layout.astro`

Espero que a la teva nòvia li encanti! 💕
