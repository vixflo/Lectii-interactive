# Ghid Pas cu Pas: Crearea Lecțiilor Interactive Excel cu Storyline 360

## Introducere

Acest ghid detaliat vă va conduce prin întregul proces de creare a unei lecții interactive profesionale de Excel folosind Articulate Storyline 360.

## Faza 1: Pregătirea și Planificarea

### 1.1 Definirea Obiectivelor

**De ce este important?**
Obiectivele clare ghidează întregul proces de dezvoltare și asigură că lecția are un scop bine definit.

**Cum să procedezi:**

1. **Identifică competența Excel pe care vrei să o predai**
   - Exemplu: "Cursanții vor învăța să utilizeze funcția VLOOKUP"
   
2. **Formulează obiective măsurabile**
   - Format recomandat: "La finalul acestei lecții, cursantul va putea să..."
   - Exemplu: "La finalul acestei lecții, cursantul va putea să creeze o formulă VLOOKUP pentru a căuta date într-un tabel"

3. **Documentează obiectivele**
   - Creează un fișier în `docs/obiective/` pentru fiecare lecție
   - Include: obiective principale, obiective secundare, prerequisite

**Șablon pentru obiective:**
```
Titlu lecție: [Numele lecției]
Durata estimată: [X minute]

Obiective principale:
- Cursantul va putea să...
- Cursantul va putea să...

Obiective secundare:
- Cursantul va înțelege...
- Cursantul va recunoaște...

Prerequisite:
- Cunoștințe de...
- Experiență cu...
```

### 1.2 Analiza Publicului Țintă

**Întrebări cheie:**
- Care este nivelul actual de cunoștințe Excel al cursanților? (începător/intermediar/avansat)
- Au lucrat anterior cu Storyline sau alte cursuri e-learning?
- Ce vârstă au și care sunt preferințele lor de învățare?
- Cât timp pot dedica învățării?
- Pe ce dispozitive vor accesa cursul? (desktop/tablet/mobile)

**Acțiuni:**
1. Creează un profil al cursantului ideal
2. Adaptează complexitatea și ritmul lecției
3. Alege exemple relevante pentru publicul țintă

### 1.3 Structurarea Conținutului

**Principiul 5-3-2:**
- Maximum 5 concepte principale per lecție
- Maximum 3 puncte cheie per concept
- Maximum 2 minute per slide informativ

**Structură recomandată pentru o lecție:**

1. **Introducere (1-2 slide-uri)**
   - Titlul lecției
   - Obiectivele de învățare
   - Ce vor putea face la final

2. **Conținut Principal (5-10 slide-uri)**
   - Prezentare concept
   - Demonstrație pas cu pas
   - Exemplu practic
   - Explicații suplimentare

3. **Practică (2-4 slide-uri)**
   - Exercițiu ghidat
   - Exercițiu independent
   - Scenarii aplicative

4. **Evaluare (1-2 slide-uri)**
   - Quiz sau test de verificare
   - Întrebări de aplicare

5. **Încheiere (1 slide)**
   - Rezumat puncte cheie
   - Next steps
   - Resurse suplimentare

## Faza 2: Colectarea și Pregătirea Resurselor

### 2.1 Capturi de Ecran din Excel

**Instrumente necesare:**
- Excel (versiunea pe care o predați)
- Snipping Tool / Snagit / OBS Studio
- Editor de imagini (Paint / Photoshop / GIMP)

**Pași:**
1. **Pregătește Excel pentru capturi**
   - Curăță interfața (închide panouri inutile)
   - Zoom la 100% pentru claritate
   - Folosește date sample realiste dar anonimizate

2. **Realizează capturi de ecran**
   - Capturează întreaga fereastră Excel pentru context
   - Capturează zone specifice pentru detalii
   - Salvează în format PNG pentru calitate

3. **Editează capturile**
   - Adaugă săgeți și highlight-uri pentru a ghida atenția
   - Adaugă numere pentru pași secvențiali
   - Crop pentru a elimina spațiul inutil

4. **Organizează fișierele**
   - Salvează în `resurse/imagini/lectia-XX/`
   - Nume descriptive: `excel-vlookup-step1.png`
   - Menține rezoluție consistentă

### 2.2 Înregistrări Video/Screen Recording

**Pentru demonstrații Excel:**

1. **Pregătirea**
   - Scrie un script pentru ce vei demonstra
   - Pregătește fișierul Excel cu datele necesare
   - Testează înregistrarea (audio + video)

2. **Înregistrarea**
   - Folosește funcția de Screen Recording din Storyline
   - Mișcări lente și deliberate cu mouse-ul
   - Pause între acțiuni pentru claritate
   - Narează clar fiecare pas

3. **Tipuri de recording în Storyline:**
   - **View Mode**: Cursantul doar privește
   - **Try Mode**: Cursantul poate încerca cu ghidare
   - **Test Mode**: Cursantul este testat

4. **Best practices:**
   - Recordinguri scurte (1-2 minute max)
   - Un concept per recording
   - Include feedback vizual și audio

### 2.3 Audio și Narațiune

**Opțiuni:**
1. **Text-to-Speech** (în Storyline 360)
   - Rapid și ușor de editat
   - Calitate bună pentru prototipuri
   - Suportă română

2. **Înregistrare Proprie**
   - Microfon de calitate
   - Cameră liniștită
   - Software: Audacity (gratuit) sau Adobe Audition

3. **Voce Profesională**
   - Pentru proiecte finale importante
   - Servicii: Fiverr, Upwork

**Tips pentru narațiune:**
- Vorbește clar și moderat
- Fă pauze naturale
- Evită jargonul excesiv
- Menține un ton prietenos dar profesional

### 2.4 Grafică și Elemente Vizuale

**Resurse gratuite recomandate:**

**Icoane:**
- Flaticon.com - icoane pentru Excel, calculator, formule
- Icons8.com - set consistent de icoane
- The Noun Project - icoane simple și clare

**Ilustrații:**
- Freepik.com - ilustrații business și educație
- unDraw.co - ilustrații SVG personalizabile
- Storyset.com - scene ilustrate animate

**Imagini Stock:**
- Unsplash.com - fotografii gratuite de înaltă calitate
- Pexels.com - video și imagini stock
- Pixabay.com - imagini și video

**Paletă de culori:**
- Coolors.co - generator palete
- Adobe Color - creează scheme armonioase
- Păstrați 3-4 culori principale pentru consistență

## Faza 3: Crearea în Articulate Storyline 360

### 3.1 Configurarea Proiectului Nou

**Pași inițiali:**

1. **Deschide Storyline 360**
   - Fie din Articulate 360 Desktop App
   - Fie direct aplicația Storyline

2. **New Project**
   - Story Size: 16:9 (Standard) - recomandat
   - Sau: alege un template existent

3. **Setări Proiect**
   - File > Story Properties
   - **Title**: "Lecția Excel - [Nume]"
   - **Author**: numele tău
   - **Description**: scurtă descriere
   - **Duration**: estimare

4. **Configurare Player**
   - Design > Player
   - Alege un template de player
   - Personalizează culorile conform brandingului
   - Activează/dezactivează funcții: meniu, resurse, notițe

### 3.2 Crearea Slide-urilor de Bază

#### Slide de Titlu

**Elementele cheie:**
- Titlul lecției (font mare, bold)
- Subtitlu sau scurtă descriere
- Imagine relevantă (logo Excel, grafică)
- Buton "Start" sau "Începe"

**Pas cu pas în Storyline:**
1. Click pe primul slide (1.1)
2. Insert > Title Slide sau folosește un layout existent
3. Editează textul: dublu-click pe text box
4. Insert > Picture pentru a adăuga imagine
5. Insert > Button pentru buton "Start"
6. Setează trigger: When user clicks Start -> Jump to next slide

#### Slide de Obiective

**Conținut:**
- Titlu: "Obiectivele lecției" sau "Ce vei învăța"
- Listă cu bullet points
- Iconiță pentru fiecare obiectiv (opțional)
- Estimare timp: "Durata: 10 minute"

**Layout recomandat:**
```
┌─────────────────────────────────────┐
│  Obiectivele Lecției                │
│                                     │
│  ✓ Vei învăța să...                │
│  ✓ Vei putea să...                 │
│  ✓ Vei înțelege...                 │
│                                     │
│  ⏱ Durata estimată: 10 minute     │
│                                     │
│         [Continuă] →                │
└─────────────────────────────────────┘
```

#### Slide-uri de Conținut

**Tipuri de slide-uri:**

1. **Slide Informativ**
   - Titlu
   - Text explicativ (max 3-4 paragrafe scurte)
   - Imagine/diagramă de suport
   - Opțional: audio narațiune

2. **Slide Demonstrativ**
   - Screen recording din Excel
   - Highlight-uri sau callouts
   - Narațiune pas cu pas
   - Possibilitate de pauză/replay

3. **Slide Interactiv**
   - Hotspots de explorat
   - Click to reveal
   - Tabs sau accordions
   - Hover effects

### 3.3 Adăugarea Interactivității

#### Screen Recording pentru Simulări Excel

**Pași completi:**

1. **Pregătire**
   - Deschide fișierul Excel pe care vrei să-l demonstrezi
   - Aranjează fereastra la dimensiune optimă
   - Închide notificări și distrageri

2. **Start Recording**
   - În Storyline: Insert > Record Screen
   - Sau: shortcut Shift+Alt+R
   - Selectează zona de recording (Select Area)
   - Recording Mode:
     * ✓ **View**: pentru demonstrații
     * ✓ **Try**: pentru practică ghidată
     * ✓ **Test**: pentru evaluare

3. **Recording**
   - Click ⭘ Record (sau F9) pentru a începe
   - Execută acțiunile în Excel lent și deliberat
   - Narează dacă ai microfon conectat
   - F10 pentru a opri recording

4. **Insert Recording**
   - Storyline va genera automat slide-uri
   - View mode: 1 slide
   - Try/Test mode: slide-uri pentru fiecare pas

5. **Editare Post-Recording**
   - Edit audio narration
   - Ajustează timing
   - Adaugă callouts sau highlight boxes
   - Customizează success/failure captions

**Exemplu de utilizare:**
- **Lecția VLOOKUP**: Recordează procesul complet de creare a unei formule VLOOKUP în mode "Try" pentru ca cursanții să practice

#### Hotspots și Click-to-Reveal

**Hotspots pentru explorare:**

1. **Insert > Hotspot**
   - Desenează zona invizibilă peste elementul de interes
   - Shape: dreptunghi, cerc, sau polygon

2. **Adaugă Trigger**
   - When: User clicks [Hotspot name]
   - Action: Show layer [Layer name]
   - Sau: Jump to slide

3. **Creează Layer**
   - Slide Layers panel (dreapta jos)
   - New Layer
   - Adaugă conținut informativ
   - Adaugă buton "Închide" cu trigger: Hide layer

**Exemplu de utilizare:**
- Imagine Excel cu diferite zone (ribbon, formula bar, cells)
- Fiecare zonă = hotspot
- Click pe hotspot → layer cu explicații detaliate

**Click-to-Reveal cu States:**

1. **Creează obiecte**
   - Insert > Shape (dreptunghiuri pentru "carduri")
   - Adaugă text pe fiecare card

2. **Definește States**
   - Selectează shape
   - Edit States (în panel stânga)
   - Duplicate "Normal" state → "Selected"
   - Editează Selected state (schimbă culoare, adaugă text)

3. **Adaugă Trigger**
   - When: User clicks [Shape]
   - Action: Change state of [Shape] to Selected

**Exemplu de utilizare:**
- 5 carduri cu "Funcții Excel comune"
- Click pe card → se expandează și arată explicație

#### Drag-and-Drop

**Creare exercițiu Drag-and-Drop:**

1. **Pregătește elementele**
   - Insert > Picture sau Shape pentru obiectele "draggable"
   - Insert > Shape pentru "drop targets"

2. **Configurare Drag-and-Drop**
   - Insert > Drag & Drop Interaction
   - Sau: Form > Drag & Drop

3. **Set Drag Items**
   - Selectează obiectele care pot fi trase
   - Bifează în panel: "Drag Items"

4. **Set Drop Targets**
   - Selectează zonele unde pot fi plasate
   - Bifează: "Drop Targets"

5. **Define Correct Matches**
   - Panel Drag & Drop: stabilește care item merge la care target
   - Multiple matches posibile

6. **Opțiuni**
   - Drag items return to start if dropped incorrectly
   - Delay feedback until interaction complete
   - Număr de încercări permise

**Exemplu de utilizare:**
- **Exercițiu**: Trage formulele Excel la categoria corectă (Mathematical, Logical, Lookup, Text)
- Items: SUM, IF, VLOOKUP, CONCATENATE, AVERAGE, AND
- Targets: 4 categorii

#### Buttons și Navigation

**Butoane standard:**
- Next/Previous (Storyline le adaugă automat)
- Custom buttons pentru navigare specială

**Creare buton custom:**
1. Insert > Button
2. Editează text
3. Formatare: Shape Style sau Edit States
4. Trigger: When user clicks → Jump to slide X

**Butoane cu condiții:**
```
Trigger 1: When user clicks [Next Button]
Condition: If [Variable QuizScore] >= 80%
Action: Jump to slide "Congratulations"

Trigger 2: When user clicks [Next Button]  
Condition: If [Variable QuizScore] < 80%
Action: Jump to slide "Review Material"
```

### 3.4 Quizzes și Evaluări

#### Tipuri de Întrebări

**1. Multiple Choice**
- Insert > New Slide > Graded Question > Multiple Choice
- Scrie întrebarea
- Adaugă răspunsuri (2-5 opțiuni)
- Marchează răspunsul corect
- Form > Question Score: setează punctajul

**2. True/False**
- Similar cu Multiple Choice dar doar 2 opțiuni
- Util pentru verificări rapide de concept

**3. Fill-in-the-Blank**
- Cursantul trebuie să tape răspunsul
- Poți accepta multiple răspunsuri corecte
- Case-sensitive sau nu

**4. Matching (Drag-and-Drop)**
- Potrivește termeni cu definiții
- Sau concepte cu exemple

**5. Hotspot Question**
- Click pe zona corectă dintr-o imagine
- Exemplu: "Click pe Formula Bar în interfața Excel"

#### Configurare Feedback

**Pentru fiecare întrebare:**

1. **Form View**
   - Design > Form View
   - Correct/Incorrect feedback
   - Try Again feedback (dacă permitem reîncercări)

2. **Personalizare Feedback**
   - Feedback Master: Design > Feedback Master
   - Layout consistent pentru toate feedback-urile
   - Includeți:
     * Icon (✓ sau ✗)
     * Mesaj scurt
     * Explicație (de ce este corect/incorect)
     * Buton Continue

3. **Advanced Feedback**
   - Feedback specific per răspuns
   - Pentru răspunsuri incorecte: explicație detaliată
   - Link către material de review

#### Result Slide

**Generare automată:**
- Insert > New Slide > Result Slide
- Selectează care quiz-uri să includă
- Customizează:
  * Pass/Fail thresholds
  * Mesaje pentru Pass și Fail
  * Opțiuni de retry

**Personalizare:**
- Design > Slide Master > Result Slide
- Modifică layout, culori, mesaje
- Adaugă grafică motivațională

### 3.5 Variables și Triggers Avansate

#### Variabile Built-in

Storyline include variabile pre-definite:
- `Results.ScorePoints` - punctaj numeric
- `Results.ScorePercent` - punctaj procentual  
- `Results.PassFail` - pass sau fail
- `Player.SlideNumber` - numărul slide-ului curent

#### Variabile Custom

**Când să folosești:**
- Tracking progres cursant
- Personalizare conținut
- Logică complexă

**Creare variabilă:**
1. Project > Variables
2. Create New Variable
3. **Name**: `CompletedModules` (fără spații)
4. **Type**: Number, Text, sau True/False
5. **Default Value**: 0
6. **Use Count**: tracking automat

**Exemplu de utilizare:**
```
Trigger: When timeline starts on slide
Action: Add 1 to CompletedModules
```

```
Trigger: When user clicks Next button
Condition: If CompletedModules >= 5
Action: Show layer "UnlockCertificate"
```

#### Triggers Complexe

**Exemple Practice:**

**1. Blocare Navigare Până la Completare:**
```
Trigger: Change state of NextButton to Disabled
When: Timeline starts on this slide

Trigger: Change state of NextButton to Normal
When: Media completes (audio/video)
```

**2. Tracking Items Vizitate:**
```
Trigger: Set VisitedIntro to True
When: Timeline starts on "Intro" slide

Trigger: Show layer "AllTopicsCompleted"
When: Timeline starts
Condition: If VisitedIntro == True
         AND VisitedConcept1 == True
         AND VisitedConcept2 == True
```

**3. Feedback Personalizat:**
```
Trigger: Show layer "ExpertFeedback"
When: User clicks Submit
Condition: If QuizScore >= 90

Trigger: Show layer "GoodJobFeedback"  
When: User clicks Submit
Condition: If QuizScore >= 70 AND QuizScore < 90

Trigger: Show layer "NeedsImprovementFeedback"
When: User clicks Submit
Condition: If QuizScore < 70
```

## Faza 4: Design și Polish

### 4.1 Design Vizual Consistent

#### Slide Master

**Configurare Slide Master:**
1. View > Slide Master
2. Editează Master Slide (primul în listă)
3. Modificări se aplică la toate slide-urile care folosesc acest master

**Elementele de modificat:**
- **Background**: culoare sau gradient
- **Footer**: text, număr slide, data
- **Placeholders**: poziție și stil pentru Title, Content
- **Fonts**: tipul și dimensiunea default
- **Colors**: schema de culori

**Best Practice:**
- Creează 2-3 layout-uri: Title Slide, Content, Section Break
- Folosește Layout consistent pentru slide-uri similare

#### Tipografie

**Reguli:**
- **Maximum 2 fonturi** în tot cursul
  * Font 1: Titluri (sans-serif, bold)
  * Font 2: Conținut (sans-serif sau serif, regular)
- **Dimensiuni recomandate** (pentru 1920x1080):
  * Titlu slide: 44-54pt
  * Subtitlu: 32-36pt
  * Text body: 24-28pt
  * Captions: 18-20pt
- **Line height**: 1.5x pentru lizibilitate

**Fonturi recomandate:**
- **Sans-serif**: Montserrat, Open Sans, Roboto, Lato
- **Serif**: Merriweather, Crimson Text (pentru text lung)

#### Scheme de Culori

**Alegerea culorilor:**
1. **Culoarea primară**: brand sau asociată cu Excel (verde)
2. **Culoarea secundară**: complementară sau contrast
3. **Culoarea accent**: pentru highlights și CTA buttons
4. **Neutral**: gri pentru text și backgrounds

**Aplicare în Storyline:**
- Design > Colors > Edit Colors
- Creează schemă custom
- Aplică consistent la shapes, text, buttons

**Paleta recomandată pentru Excel:**
```
Primary:   #217346 (Verde Excel)
Secondary: #0078D4 (Albastru Microsoft)
Accent:    #FFC000 (Galben/Portocaliu)
Dark:      #333333 (Text)
Light:     #F5F5F5 (Background)
```

### 4.2 Animații și Tranziții

**Regula de aur: Less is more!**

**Când să folosești animații:**
- Să direcționezi atenția
- Să arăți procesul sau fluxul
- Să creezi interes vizual

**Când să eviți:**
- Animații excesive = distragere
- Animații lungi = pierdere timp
- Animații dizzy = inconfort

**Tipuri de animații în Storyline:**

1. **Entrance animations**
   - Fade, Fly in, Wipe
   - Pentru a introduce elemente pe slide

2. **Exit animations**
   - Mai rar folosite
   - Când vrei să scoți un element

3. **Motion paths**
   - Pentru a muta obiecte pe slide
   - Exemplu: săgeată care indică o zonă

4. **Emphasis animations**
   - Pulse, Grow/Shrink
   - Pentru a atrage atenția

**Setare animații:**
- Selectează obiect > Animations tab
- Alege tip animație
- Setează: Duration (0.5-1s), Timing (with previous/after previous)

**Best Practices:**
- **Animații scurte**: 0.5-1 secundă
- **Consistent**: același tip pentru elemente similare
- **Purposeful**: fiecare animație are un scop clar

### 4.3 Accesibilitate

**De ce este important:**
- Inclusivitate - toată lumea poate învăța
- Legal requirements (în multe țări)
- SEO și discovery

**Checklist Accesibilitate:**

**1. Text Alternativ (Alt Text)**
- Fiecare imagine trebuie să aibă alt text descriptiv
- Click-dreapta pe imagine > Size and Position > Alt Text
- Descrie conținutul, nu "imagine Excel"
- Exemplu: "Captură ecran Excel arătând formula VLOOKUP în celula B2"

**2. Navigare cu Tastatura**
- Testează: poți naviga doar cu Tab și Enter?
- Asigură-te că ordinea tab este logică
- Accessibility > Tab Order (pentru fiecare slide)

**3. Contrast Culori**
- Ratio minim: 4.5:1 pentru text normal
- Ratio minim: 3:1 pentru text mare
- Tool: WebAIM Contrast Checker

**4. Subtitrări și Transcripturi**
- Pentru orice audio/video
- Storyline: Insert > Closed Captions
- Importă fișier .vtt sau scrie manual

**5. Focus Order**
- Accessibility > Focus Order
- Stabilește ordinea în care screen readers citesc conținutul

**6. Descriptive Links**
- În loc de "Click aici"
- Folosește: "Descarcă ghidul VLOOKUP (PDF)"

**Testing:**
- NVDA (screen reader gratuit pentru Windows)
- JAWS (screen reader popular)
- Keyboard only navigation

## Faza 5: Testare și Rafinare

### 5.1 Testare Tehnică

**Checklist testare:**

**Funcționalitate:**
- [ ] Toate butoanele funcționează
- [ ] Navigarea este logică și consistentă
- [ ] Audio playback funcționează
- [ ] Screen recordings playback corect
- [ ] Drag-and-drop interactions funcționează
- [ ] Quizzes scoring corect
- [ ] Variables se actualizează corect
- [ ] Triggers se execută în ordinea corectă

**Conținut:**
- [ ] Text fără greșeli de ortografie
- [ ] Formule Excel sunt corecte
- [ ] Exemple sunt relevante și corecte
- [ ] Imagini sunt clare și relevante
- [ ] Audio este clar și fără zgomot

**Cross-Browser:**
- [ ] Chrome (ultimele 2 versiuni)
- [ ] Firefox (ultimele 2 versiuni)
- [ ] Safari (ultimele 2 versiuni)
- [ ] Edge (ultimele 2 versiuni)

**Device Testing:**
- [ ] Desktop (1920x1080)
- [ ] Laptop (1366x768)
- [ ] Tablet (iPad)
- [ ] Mobile (opțional, dacă relevant)

**Publicare Test:**
1. File > Publish
2. Format: Web sau LMS
3. Publish la folder local
4. Test complet înainte de upload

### 5.2 Testare cu Utilizatori

**Alpha Testing (intern):**
- Colegi sau prieteni testează
- Observă unde se blochează
- Notează confuzii sau erori
- Colectează feedback deschis

**Beta Testing (țintă reală):**
- 3-5 cursanți din publicul țintă
- Observare live sau recording screen
- Think-aloud protocol: verbalizează ce gândesc

**Întrebări de pus:**
1. Au fost obiectivele clare?
2. A fost conținutul ușor de înțeles?
3. Au fost interacțiunile intuitive?
4. A fost cursul prea ușor/dificil?
5. Cât a durat? (vs. estimare)
6. Ce au învățat?
7. Ce ar îmbunătăți?

**Metrici de urmărit:**
- **Completion rate**: câți termină cursul
- **Time to complete**: durata medie
- **Quiz scores**: media scorurilor
- **Replay rate**: câți reiau lecții
- **Drop-off points**: unde abandonează cursanții

### 5.3 Iterare și Îmbunătățire

**Pe baza feedback-ului:**

**Probleme comune și soluții:**

1. **"Prea mult text"**
   - Soluție: Chunk în slide-uri mai mici
   - Sau: Folosește tabs/accordions
   - Sau: Mută în audio narațiune

2. **"Nu știam că trebuie să dau click"**
   - Soluție: Instrucțiuni mai clare
   - Sau: Hint după 5 secunde
   - Sau: Cursor animation

3. **"Am ratat informația importantă"**
   - Soluție: Slow down animations
   - Sau: Highlight mai evident
   - Sau: Repetare concept

4. **"Nu pot reveni la slide anterior"**
   - Soluție: Activează Previous button
   - Sau: Adaugă menu
   - Sau: Review section la final

5. **"Prea ușor/dificil"**
   - Soluție: Ajustează complexitate
   - Sau: Adaugă pre-test pentru branching
   - Sau: Optional advanced content

**Procesul de iterare:**
1. Colectează feedback
2. Prioritizează issues (critical > nice-to-have)
3. Fă modificări
4. Re-testează
5. Repeat până la satisfacție

## Faza 6: Publicare și Distribuție

### 6.1 Opțiuni de Publicare

**Storyline oferă multiple formate:**

**1. Web (HTML5)**
- **Când**: Hosting pe website propriu
- **Avantaje**: Cross-platform, no plugin needed
- **Cum**: File > Publish > Web
- **Output**: folder cu index.html

**2. LMS (SCORM/xAPI/AICC)**
- **Când**: Integrare cu Learning Management System
- **Formate**:
  * SCORM 1.2 (cel mai compatibil)
  * SCORM 2004
  * xAPI (Tin Can) - tracking avansat
  * AICC
- **Cum**: File > Publish > LMS
- **Output**: .zip package

**3. Articulate Review**
- **Când**: Pentru review și feedback
- **Avantaje**: Share link, stakeholders comentează
- **Cum**: File > Publish > Review 360
- **Output**: link cloud

**4. Video**
- **Când**: Vrei video demo, nu interactivitate
- **Cum**: File > Publish > Video
- **Format**: MP4

**5. Word**
- **Când**: Documentație sau printing
- **Cum**: File > Publish > Word
- **Output**: Document cu screenshots

### 6.2 Configurări de Publicare

**Înainte de publicare:**

**Player Settings:**
- Design > Player
- **Features**: alegi ce se afișează
  * Menu: ON (pentru navigare ușoară)
  * Resources: ON (dacă ai adăugat resurse)
  * Glossary: opțional
  * Notes: opțional
  * Search: util pentru cursuri mari
- **Text Labels**: personalizează în română
  * "Next" → "Următorul"
  * "Previous" → "Anterior"
  * "Submit" → "Trimite"
  * etc.

**Publishing Settings:**
1. File > Publish
2. **Publishing Options:**
   - Title: numele cursului
   - Quality: High (pentru final)
   - Include HTML5 output: YES
   - Include Flash output: NO (deprecated)

3. **LMS Specific:**
   - Tracking: slides viewed sau quiz results
   - Reporting: passed/incomplete/failed
   - Completion: by completing course sau quiz threshold
   - Score: quiz score sau slide views

4. **Advanced:**
   - When running in LMS, ignore Flash cookie
   - Display Storyline for 508 compliance

**Publishing pentru Web:**
1. Publish > Web
2. Alege folder destinație
3. Publish
4. După finalizare: Zip > Upload pe server
5. Link direct la `index.html`

**Publishing pentru LMS:**
1. Publish > LMS
2. Alege Standard (SCORM 1.2 recomandat)
3. Configure tracking și reporting
4. Publish
5. Upload .zip în LMS

### 6.3 Hosting și Distribuție

**Opțiuni de Hosting:**

**1. Articulate 360 Teams**
- Cel mai simplu pentru utilizatorii Articulate
- Review, Publish, Share într-un singur loc

**2. Website Propriu**
- Upload folder publicat pe server
- Link direct către cursanți
- Necesită: hosting web, domeniu

**3. LMS (Moodle, Canvas, Blackboard, etc.)**
- Upload SCORM package
- Tracking avansat al progresului
- Integrare cu alte cursuri

**4. Google Drive / Dropbox**
- Nu recomandat pentru distribuție finală
- OK pentru testare și review
- Limitări la SCORM tracking

**5. Amazon S3 / CloudFront**
- Scalabil pentru multe accesări simultane
- Cost eficient
- Necesită configurare tehnică

**Best Practices Distribuție:**
- **Testează linkul** înainte de a trimite la cursanți
- **Verifică permisiunile** (public vs. privat)
- **Provide clear instructions** pentru acces
- **Anunță cerințe tehnice**: browser recomandat, JavaScript enabled
- **Oferă suport**: contact pentru probleme tehnice

### 6.4 Post-Launch

**Monitorizare:**
- Verifică analytics din LMS sau tool de tracking
- Identifică probleme comune
- Colectează feedback continuu

**Actualizări:**
- Excel se actualizează → actualizează lecția
- Feedback cursanți → îmbunătățiri
- Versioning: păstrează copii ale versiunilor anterioare

**Promovare:**
- Anunță în newsletter
- Social media posts
- Demonstrații live

## Resurse Suplimentare

**Articulate Support:**
- https://articulate.com/support/storyline-360
- https://community.articulate.com/

**Tutoriale Video:**
- Articulate YouTube channel
- LinkedIn Learning: Articulate Storyline courses

**Cărți recomandate:**
- "Design For How People Learn" de Julie Dirksen
- "e-Learning and the Science of Instruction" de Clark & Mayer

**Comunități:**
- E-Learning Heroes forum
- Articulate user groups (locale)

---

**Succes în crearea lecțiilor tale interactive!** 🎓
