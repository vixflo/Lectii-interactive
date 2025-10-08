# Proiecte - Lecții Interactive Excel

Acest folder conține proiectele tale de lecții organizate.

## 📁 Structura Organizare

Fiecare lecție are propriul folder cu toate fișierele asociate:

```
proiecte/
├── lectia-01-introducere/
│   ├── lectia-01.story              # Fișier principal Storyline
│   ├── obiective.md                 # Obiective de învățare
│   ├── assets/                      # Resurse specifice acestei lecții
│   │   ├── imagini/
│   │   ├── audio/
│   │   └── video/
│   ├── publicate/                   # Output-uri published
│   │   ├── web/                     # HTML5 pentru web
│   │   ├── scorm/                   # SCORM package pentru LMS
│   │   └── review/                  # Pentru Articulate Review
│   ├── versiuni/                    # Backup versiuni anterioare
│   │   ├── lectia-01-v1.0.story
│   │   ├── lectia-01-v1.1.story
│   │   └── changelog.md
│   └── README.md                    # Documentație lecție
│
├── lectia-02-formule-baza/
│   └── [structură similară]
│
└── lectia-03-formatare/
    └── [structură similară]
```

## 🎯 Template pentru Fiecare Proiect

### obiective.md

```markdown
# Obiective de Învățare - [Titlu Lecție]

## Informații Generale
- **Titlu:** [Numele complet]
- **Cod:** Lecția XX
- **Durata estimată:** XX minute
- **Nivel:** Începător / Intermediar / Avansat
- **Prerequisite:** [Lista]

## Obiective Principale

La finalul acestei lecții, cursantul va putea să:

1. [Obiectiv 1 - folosește verbe acționale: identifice, creeze, aplice]
2. [Obiectiv 2]
3. [Obiectiv 3]

## Obiective Secundare

- [Înțelegere conceptuală]
- [Recunoaștere]

## Competențe Excel Acoperite

- [ ] Interfață și navigare
- [ ] Introducere date
- [ ] Formule de bază
- [ ] Formatare
- [ ] Tabele și liste
- [ ] Grafice
- [ ] Funcții avansate
- [ ] Analiza datelor
- [ ] Automatizare

## Rezultate Așteptate

După finalizare, cursantul ar trebui să poată:
- [Aplicare practică 1]
- [Aplicare practică 2]

## Evaluare

- Quiz: X întrebări
- Passing score: XX%
- Exerciții practice: X
- Proiect final: [Descriere]
```

### README.md (per lecție)

```markdown
# [Titlu Lecție]

## Detalii Proiect

- **Status:** 🟢 Activ / 🟡 În dezvoltare / 🔴 Arhivat
- **Versiune curentă:** X.X
- **Ultima actualizare:** YYYY-MM-DD
- **Autor:** [Nume]

## Conținut

### Slides Overview
- Slides 1.1-1.2: Introducere și obiective
- Slides 2.1-2.5: Conținut principal
- Slides 3.1-3.3: Practică
- Slides 4.1-4.2: Quiz
- Slide 5.1: Rezumat

**Total slides:** XX

### Interactivități
- Screen recordings: X
- Drag-and-drop: X
- Hotspots: X
- Quiz questions: X

### Durate
- Estimat: XX minute
- Actual (media utilizatori): XX minute

## Assets Folosite

### Imagini
- `excel-interface.png` - Screenshot interfață
- `ana-character.png` - Personaj ghid
- [Lista completă...]

### Audio
- `narration-intro.mp3` - Voice-over introducere
- [Lista completă...]

### Video
- [Dacă aplicabil]

### Fonts
- Montserrat Bold
- Open Sans Regular

### Colors
- Primary: #217346
- [Palette completă...]

## Publishing Info

### Web Version
- **URL:** [Link dacă hosted]
- **Ultima publicare:** YYYY-MM-DD

### LMS Version
- **Format:** SCORM 1.2
- **Tracking:** Quiz results, completion
- **Uploaded to:** [Nume LMS]
- **Ultima publicare:** YYYY-MM-DD

## Testing Log

| Data | Tester | Issues Found | Status |
|------|--------|--------------|--------|
| 2024-01-15 | Ana M. | Navigation bug slide 5 | ✅ Fixed |
| 2024-01-16 | Ion P. | Audio sync issue | ✅ Fixed |

## Known Issues

- [ ] Issue 1: [Descriere]
- [ ] Issue 2: [Descriere]

## Planned Updates

- [ ] Adaugă exercițiu suplimentar
- [ ] Update screenshots pentru Excel 365
- [ ] Îmbunătățire feedback quiz

## Notes

[Orice observații relevante despre lecție]
```

### changelog.md (per lecție)

```markdown
# Change Log - [Titlu Lecție]

## Version 1.2 (2024-01-20)
### Changed
- Updated Excel screenshots to Office 365 interface
- Improved hint timing in simulation (slide 3.2)

### Fixed
- Audio sync issue on slide 2.1
- Typo in quiz question 3

### Added
- Additional practice exercise (slide 3.4)
- Downloadable cheat sheet resource

## Version 1.1 (2024-01-15)
### Fixed
- Navigation bug on slide 5
- Incorrect feedback on quiz question 2

### Changed
- Simplified instructions on drag-and-drop exercise

## Version 1.0 (2024-01-10)
### Initial Release
- First published version
- 25 slides
- 5 quiz questions
- 2 simulations
```

## 🔄 Workflow Recomandat

### 1. Începerea unui Proiect Nou

```bash
# Creează folder nou
mkdir lectia-XX-nume-descriptiv
cd lectia-XX-nume-descriptiv

# Creează structura
mkdir assets assets/imagini assets/audio assets/video
mkdir publicate publicate/web publicate/scorm publicate/review
mkdir versiuni

# Creează fișiere documentație
touch obiective.md README.md versiuni/changelog.md
```

### 2. Dezvoltare

1. **Start cu template**
   - Copiază template potrivit din `/template-uri`
   - Salvează ca `lectia-XX.story` în folder proiect

2. **Creează conținut**
   - Editează obiective.md cu planul clar
   - Dezvoltă slides în Storyline
   - Organizează assets în subfolderele respective

3. **Version control**
   - Salvează incremental: File > Save As > Add to versiuni/
   - Naming: `lectia-XX-vX.X.story`
   - Actualizează changelog.md

4. **Testing**
   - Preview frecvent (F12 în Storyline)
   - Test complet înainte de publish
   - Log issues în README.md

### 3. Publishing

1. **Publish pentru review**
   ```
   File > Publish > Articulate Review
   Output: publicate/review/
   Share link cu stakeholders pentru feedback
   ```

2. **Publish final**
   ```
   File > Publish > LMS (SCORM 1.2)
   Output: publicate/scorm/
   
   File > Publish > Web  
   Output: publicate/web/
   ```

3. **Documentation**
   - Actualizează README.md cu publishing info
   - Tag version în changelog.md
   - Archive în versiuni/

### 4. Post-Launch

1. **Monitoring**
   - Colectează feedback utilizatori
   - Monitorizează completion rates din LMS
   - Identifică issues

2. **Maintenance**
   - Planned updates din README.md
   - Bug fixes în versiuni noi
   - Re-publish când necesar

## 📊 Project Dashboard

Creează un fișier `PROJECT-STATUS.md` în root `/proiecte`:

```markdown
# Status Toate Lecțiile

| # | Titlu | Status | Versiune | Ultima Update | Completion % | Avg Score |
|---|-------|--------|----------|---------------|--------------|-----------|
| 1 | Introducere Excel | ✅ Live | 1.2 | 2024-01-20 | 95% | 87% |
| 2 | Formule Bază | 🟡 Review | 0.9 | 2024-01-18 | - | - |
| 3 | Formatare | 🔵 Dev | 0.5 | 2024-01-15 | - | - |
| 4 | Grafice | 📋 Planned | - | - | - | - |

**Legend:**
- ✅ Live - Published și activ
- 🟡 Review - În review, aproape gata
- 🔵 Dev - În development activ
- 📋 Planned - Planificat, nu început încă
- 🔴 Archived - Arhivat/deprecat

**Overall Progress:** 45% (3/10 lecții complete)
```

## 🎯 Best Practices

### Naming Conventions

**Fișiere Storyline:**
```
lectia-XX-nume-scurt.story

Exemple:
lectia-01-introducere.story
lectia-02-formule-baza.story
lectia-03-formatare.story
```

**Versiuni:**
```
lectia-XX-vMAJOR.MINOR.story

Exemple:
lectia-01-v1.0.story (initial release)
lectia-01-v1.1.story (bug fixes, minor updates)
lectia-01-v2.0.story (major rewrite/new features)
```

**Published packages:**
```
lectia-XX-nume-FORMAT-vVERSION-DATE.zip

Exemple:
lectia-01-introducere-SCORM-v1.2-20240120.zip
lectia-01-introducere-WEB-v1.2-20240120.zip
```

### Backup Strategy

**Frecvență:**
- **Daily:** Auto-save Storyline (File > Preferences > Save)
- **Weekly:** Manual save ca nouă versiune
- **Before major changes:** Duplicate current version
- **Before publishing:** Full project backup

**Locații:**
- **Local:** Folderul `versiuni/` al proiectului
- **Cloud:** Google Drive / OneDrive / Dropbox (automated sync)
- **Git:** Pentru documentație (nu fișiere .story - prea mari)

**Ce să incluzi în backup:**
- Fișier .story
- Assets folder complet
- Documentation (obiective, README, changelog)
- Published packages (ultimele 2-3 versiuni)

### Optimizare Spațiu

**Fișiere .story pot deveni mari:**
- Regular: 10-50 MB
- Cu mult media: 100-200 MB
- Huge courses: 500+ MB

**Strategii:**
1. **Optimizează assets înainte de import**
   - Compresie imagini
   - Audio bitrate redus
   - Video rezoluție adecvată

2. **Curăță unused media**
   - Resources > Manage Project Assets
   - Delete unused pictures/audio/video

3. **Archive old versions**
   - Keep doar ultimele 3-5 versiuni local
   - Archive older în cloud/external drive

4. **Published output separat**
   - Nu commita published folders în Git
   - Store doar final versions

## 🔍 Quality Checklist

Înainte de a marca o lecție ca "gata":

### Content
- [ ] Obiectivele sunt clare și măsurabile
- [ ] Conținutul e precis și up-to-date
- [ ] Exemple sunt relevante
- [ ] Exerciții practice incluse
- [ ] Quiz testează obiectivele

### Technical
- [ ] Toate interacțiunile funcționează
- [ ] Audio sincronizat cu vizual
- [ ] Navigarea e intuitivă
- [ ] Tracking configurat corect
- [ ] Testat pe multiple browsere

### Design
- [ ] Design consistent
- [ ] Lizibilitate text
- [ ] Imagini clare
- [ ] Culori accesibile
- [ ] Animații smooth

### Accessibility
- [ ] Alt text pentru imagini
- [ ] Captions pentru audio/video
- [ ] Keyboard navigation
- [ ] Color contrast suficient
- [ ] Screen reader compatible

### Documentation
- [ ] obiective.md completat
- [ ] README.md actualizat
- [ ] changelog.md cu versiune
- [ ] Assets documentate
- [ ] Known issues noted

## 📚 Resurse Utile

**Articulate Resources:**
- [Storyline 360 User Guide](https://articulate.com/support/storyline-360)
- [E-Learning Heroes Community](https://community.articulate.com/)
- [Articulate Blog](https://articulate.com/blog)

**Project Management:**
- Trello / Asana - pentru task tracking
- Notion / Evernote - pentru notes și ideas
- Google Sheets - pentru project dashboard

**Collaboration:**
- Articulate Review 360 - pentru stakeholder feedback
- Loom - pentru video feedback/explanations
- Slack / Teams - pentru team communication

---

## 💡 Tips

**Productivitate:**
- Setează routine: 2-3 ore focused work per zi
- Batch similar tasks (ex: toate screen recordings într-o sesiune)
- Use templates pentru consistență
- Keyboard shortcuts în Storyline (F12 = Preview)

**Feedback:**
- Testează cu minimum 3 utilizatori reali
- Colectează feedback specific ("What confused you on slide 5?")
- Iterează bazat pe date, nu opinii

**Learning:**
- Participă la E-Learning Heroes weekly challenges
- Studiază cursuri bune din industrie
- Share și învață de la alții

---

**Baftă cu proiectele tale! 🚀**
