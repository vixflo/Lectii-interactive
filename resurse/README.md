# Resurse pentru Lecții Interactive Excel

Acest folder conține toate resursele necesare pentru crearea lecțiilor interactive: imagini, icoane, fonturi, audio și video.

## 📁 Structura Folderelor

### `/imagini`
Capturi de ecran din Excel, diagrame, ilustrații

**Organizare:**
```
imagini/
├── lectia-01/          # Resurse pentru Lecția 1
│   ├── excel-interface.png
│   ├── ana-character.png
│   └── ribbon-highlight.png
├── lectia-02/          # Resurse pentru Lecția 2
│   └── ...
├── comune/             # Imagini reutilizabile
│   ├── backgrounds/
│   ├── characters/
│   └── diagrams/
└── templates/          # Template-uri și șabloane vizuale
```

**Guidelines:**
- Format: PNG pentru screenshots și grafică, JPG pentru fotografii
- Rezoluție: Max 1920px wide pentru full-slide images
- Naming: descriptiv și consistent (ex: `excel-vlookup-step1.png`)
- Compresie: optimizează înainte de import (TinyPNG.com)

### `/icoane`
Set de icoane pentru UI, buttons, concepte

**Recomandări surse:**
- Flaticon.com - set consistent de icoane
- Icons8.com - multiple stiluri
- The Noun Project - icoane simple

**Guidelines:**
- Format: PNG transparent sau SVG
- Dimensiune: 128px-256px
- Stil: consistent în tot cursul (același designer/set)
- Culori: adaptabile la paleta cursului

**Icoane necesare:**
```
✓ Checkmark (success)
✗ X mark (error)
💡 Lightbulb (tips)
⚠️ Warning (attention)
📊 Chart (data)
⏱️ Clock (time)
🎯 Target (goals)
📖 Book (learning)
⌨️ Keyboard (shortcuts)
🖱️ Mouse (click)
```

### `/fonturi`
Fonturi folosite în lecții

**Fonturi recomandate:**
- **Montserrat** (Google Fonts) - headings
- **Open Sans** (Google Fonts) - body text
- **Roboto** (Google Fonts) - alternative

**Instalare:**
1. Download de pe Google Fonts
2. Instalează pe sistemul tău
3. Verifică că sunt disponibile în Storyline

**Note:**
- Păstrează consistența: max 2 fonturi per curs
- Asigură-te că suportă caractere românești (ă, â, î, ș, ț)

### `/audio`
Narațiuni, efecte sonore, muzică de fundal

**Organizare:**
```
audio/
├── naratiuni/          # Voice-over per lecție
│   ├── lectia-01/
│   │   ├── intro.mp3
│   │   ├── slide-03.mp3
│   │   └── ...
│   └── lectia-02/
├── efecte-sonore/      # Sound effects
│   ├── success-ding.mp3
│   ├── error-buzz.mp3
│   ├── click.mp3
│   └── transition.mp3
└── muzica/             # Background music (dacă se folosește)
    ├── intro-theme.mp3
    └── outro-theme.mp3
```

**Guidelines audio:**
- Format: MP3 (compatibilitate universală)
- Bitrate: 96kbps pentru voce, 128kbps pentru muzică
- Mono vs Stereo: Mono pentru voice-over (reduce file size)
- Durată: potrivită cu slide-ul (nu prea lungă)
- Volume: normalizat (-3dB pentru headroom)

**Resurse pentru voice-over:**
- **DIY:** Microfon USB decent (Blue Yeti, Audio-Technica AT2020)
- **Software:** Audacity (gratuit) pentru editare
- **Text-to-Speech:** Storyline 360 TTS (rapid pentru prototipuri)
- **Professional:** Fiverr, Upwork pentru voce profesională

**Resurse pentru muzică/efecte:**
- **Epidemic Sound** - muzică royalty-free
- **AudioJungle** - efecte sonore
- **Freesound.org** - efecte gratuite
- **YouTube Audio Library** - muzică gratuită

### `/video`
Clipuri video demonstrative

**Guidelines video:**
- Format: MP4 (H.264 codec)
- Rezoluție: Max 1280x720 (pentru file size)
- Durată: Max 2 minute per clip (chunking)
- Bitrate: 1-2 Mbps
- Frame rate: 30fps

**Când să folosești video vs screen recording Storyline:**
- ✅ Video: Introduceri, testimoniale, demonstrații complexe
- ✅ Screen Recording: Tutorial-uri Excel (preferat în Storyline)

**Organizare:**
```
video/
├── lectia-01/
│   └── intro-excel.mp4
├── lectia-02/
│   └── formule-demo.mp4
└── comune/
    ├── testimonial-ana.mp4
    └── course-intro.mp4
```

## 🎨 Palette de Culori Recomandate

### Excel Theme (Recomandat)
```css
Primary (Excel Green): #217346
Secondary (Blue): #0078D4
Accent (Orange): #FFC000
Success: #28A745
Error: #DC3545
Warning: #FFA500
Dark Text: #333333
Light Text: #666666
Background Light: #F5F5F5
Background Dark: #2D2D2D
```

### Professional Corporate
```css
Primary (Navy): #003366
Secondary (Teal): #008B8B
Accent (Gold): #FFD700
Dark: #1A1A1A
Light: #F8F8F8
```

### Friendly & Approachable
```css
Primary (Blue): #4A90E2
Secondary (Green): #7ED321
Accent (Pink): #F5A623
Dark: #4A4A4A
Light: #FAFAFA
```

## 📐 Design Templates

### Slide Layouts

**Title Slide Template:**
```
┌─────────────────────────────────────────┐
│                                          │
│                                          │
│         [Logo/Icon]                     │
│                                          │
│     TITLU LECȚIE                        │
│     Subtitlu sau descriere scurtă       │
│                                          │
│                                          │
│         [Buton Start]                   │
│                                          │
└─────────────────────────────────────────┘
```

**Content Slide Template:**
```
┌─────────────────────────────────────────┐
│  Titlu Slide                      [Icon]│
│  ─────────────────────────────          │
│                                          │
│  Conținut principal                     │
│  - Bullet point 1                       │
│  - Bullet point 2                       │
│                                          │
│  [Imagine/Diagram]                      │
│                                          │
│                          [Next →]       │
└─────────────────────────────────────────┘
```

**Two-Column Layout:**
```
┌─────────────────────────────────────────┐
│  Titlu                                   │
│  ───────────────────────────────────    │
│                                          │
│  ┌──────────────┬──────────────┐       │
│  │              │              │       │
│  │   Coloană 1  │  Coloană 2  │       │
│  │   (Text)     │  (Imagine)  │       │
│  │              │              │       │
│  └──────────────┴──────────────┘       │
│                                          │
│                          [Next →]       │
└─────────────────────────────────────────┘
```

## 🎭 Character Design Guide

### Personajul Ana (Account Manager)

**Caracteristici:**
- Vârstă: 28-32 ani
- Ocupație: Account Manager în vânzări
- Stil: Profesional, prietenos
- Folosește Excel pentru: rapoarte, analize vânzări, tracking clienți

**Asset-uri necesare:**
- `ana-neutral.png` - expresie neutră/profesională
- `ana-happy.png` - zâmbitoare/entuziastă
- `ana-thinking.png` - gânditoare/contemplativă
- `ana-thumbs-up.png` - apreciativă/încurajatoare
- `ana-pointing.png` - explicativă/demonstrativă

**Palette culori:**
- Haine: Nuanțe profesionale (albastru, gri, alb)
- Background: Transparent sau office setting

### Alte Personaje (opțional)

**Mihai - Antreprenor**
- Folosește Excel pentru: bugete, planificare financiară
- Asset-uri: similar ca Ana

**Cristina - Data Analyst**
- Folosește Excel pentru: analize complexe, pivot tables
- Asset-uri: similar ca Ana

## 📥 Cum să Organizezi Resursele

### Naming Conventions

**Imagini:**
```
[categorie]-[descriere]-[varianta].png

Exemple:
excel-interface-clean.png
excel-vlookup-step1.png
excel-vlookup-step2.png
ana-character-happy.png
diagram-worksheet-workbook.png
```

**Audio:**
```
[tip]-[lectie]-[slide/scop].mp3

Exemple:
narration-l01-intro.mp3
narration-l01-slide03.mp3
sfx-success.mp3
sfx-error.mp3
music-intro-theme.mp3
```

**Video:**
```
[lectie]-[descriere].mp4

Exemple:
l01-intro-welcome.mp4
l02-vlookup-demo.mp4
testimonial-ana.mp4
```

### Metadata și Documentație

**Creează fișier `asset-inventory.xlsx`:**
```
Coloane:
- Filename
- Type (image/audio/video)
- Used in (lecții)
- Source (unde obținut)
- License (copyright info)
- Date added
- File size
- Notes
```

## ✅ Checklist Resurse

Înainte de a începe lecția:

**Imagini:**
- [ ] Screenshots Excel sunt clare și la rezoluție bună
- [ ] Toate imaginile sunt comprimate (<200KB)
- [ ] Format corect (PNG pentru UI, JPG pentru photos)
- [ ] Nume descriptive și organizate în foldere

**Audio:**
- [ ] Voice-over este clar și fără zgomot de fundal
- [ ] Volume normalizat
- [ ] Format MP3, bitrate adecvat
- [ ] Sincronizat cu durata slide-urilor

**Video:**
- [ ] Rezoluție și bitrate optimizate
- [ ] Durata sub 2 minute per clip
- [ ] Format MP4, codec H.264
- [ ] Testat playback în Storyline

**Generale:**
- [ ] Asset inventory actualizat
- [ ] License/copyright verificat pentru toate resursele
- [ ] Backup realizat
- [ ] Versioning pentru modificări

## 🔗 Resurse Externe Recomandate

**Imagini Stock Gratuite:**
- Unsplash.com
- Pexels.com
- Pixabay.com

**Icoane:**
- Flaticon.com
- Icons8.com
- TheNounProject.com
- FontAwesome (pentru web)

**Ilustrații:**
- unDraw.co (customizable, gratuite)
- Storyset.com (animate)
- DrawKit.io
- Freepik.com

**Audio:**
- Freesound.org (efecte)
- YouTube Audio Library (muzică)
- Incompetech.com (Kevin MacLeod - royalty free)
- Bensound.com

**Fonturi:**
- Google Fonts (gratuite, web-friendly)
- Font Squirrel (gratuite pentru comercial)
- DaFont (verifică licența)

**Tools:**
- TinyPNG.com - compresie imagini
- Canva.com - design grafică simplă
- Remove.bg - eliminare background imagini
- Audacity - editare audio gratuită
- HandBrake - conversie/compresie video

---

**Note:** Păstrează toate resursele organizate și documentate pentru ușurință în mentenanță și update-uri viitoare!
