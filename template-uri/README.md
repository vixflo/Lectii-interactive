# Template-uri Articulate Storyline 360

Acest folder conține șabloane pre-configurate pentru lecțiile tale Excel.

## 📋 Template-uri Disponibile

### 1. Template Excel Basic
**Fișier:** `template-excel-basic.story` _(va fi adăugat)_

**Caracteristici:**
- Slide Master pre-configurat cu design Excel theme
- 5 slide layouts de bază:
  - Title Slide
  - Content Slide (text + imagine)
  - Two-Column Layout
  - Quiz Question
  - Result Slide
- Player customizat cu culori Excel (verde #217346)
- Variabile pre-definite pentru tracking
- Butoane standardizate (Next, Previous, Submit)

**Când să folosești:**
- Lecții introductive
- Conținut simplu, linear
- Timeline: 10-20 minute

**Cum să folosești:**
1. Deschide `template-excel-basic.story` în Storyline 360
2. File > Save As > `[nume-lectia-ta].story`
3. Editează slide-urile cu conținutul tău
4. Păstrează design-ul consistent folosind layouturile predefinite

---

### 2. Template Excel Advanced
**Fișier:** `template-excel-advanced.story` _(va fi adăugat)_

**Caracteristici:**
- Tot ce include Basic template, plus:
- Slide layers template pentru interactivitate
- Lightbox template pentru popup info
- Drag-and-drop interaction template
- Scenario branching structure
- Advanced variables și triggers predefinite
- Progress bar implementat
- Menu custom cu tracking

**Când să folosești:**
- Lecții cu interactivitate complexă
- Simulări și practice extensive
- Scenarii de branching
- Timeline: 20-45 minute

**Cum să folosești:**
1. Deschide `template-excel-advanced.story` în Storyline 360
2. File > Save As > `[nume-lectia-ta].story`
3. Studiază slide-urile "Template Examples" pentru a înțelege structura
4. Duplicate și adaptează slide-urile template
5. Șterge slide-urile example după ce ai terminat

---

## 🎨 Design Elements în Template-uri

### Slide Masters Incluse

**Master 1: Excel Theme (Default)**
```
- Background: Gradient alb-verde subtle
- Header: Verde Excel #217346
- Footer: Număr slide, logo mic
- Fonts: Montserrat (headings), Open Sans (body)
- Colors: Palette Excel (verde, albastru, portocaliu)
```

**Master 2: Dark Theme (Alternative)**
```
- Background: Gri închis #2D2D2D
- Header: Accent verde/albastru
- Text: Alb/Gri deschis pentru contrast
- Use case: Variety sau section breaks
```

### Layouts Predefinite

**1. Title Slide**
- Centru: Titlu mare (54pt)
- Sub-titlu (32pt)
- Zone pentru logo/icon
- Buton "Start" pre-configurat

**2. Content Slide**
- Header cu titlu (40pt)
- Content area flex (text sau mixed)
- Footer standard
- Navigation buttons

**3. Two-Column**
- Header cu titlu
- Left: Text area
- Right: Image/media area
- Auto-resize pentru balance

**4. Three-Column**
- Header cu titlu
- 3 coloane egale
- Perfect pentru comparații sau lists

**5. Full-Screen Image**
- Background image full-bleed
- Text overlay cu background semi-transparent
- Dramatic effect pentru section breaks

**6. Quiz Question**
- Question text area (centru-sus)
- Answer choices (4 opțiuni standard)
- Submit button
- Feedback layers pre-configurate

**7. Result Slide**
- Score display (mare, centru)
- Pass/Fail messaging
- Review și Retry buttons
- Custom messaging zones

**8. Interaction Slide**
- Zone dedicate pentru drag-drop
- Hotspot areas marcate
- Instructions zone
- Feedback area

### Player Settings

**Configurație Default:**
```
Features:
☑ Menu (automatic din slide titles)
☑ Resources (pentru downloadables)
☐ Glossary
☐ Notes
☑ Search (pentru cursuri mari)

Colors:
- Base: Verde Excel #217346
- Accent: Albastru #0078D4
- Visited: Verde închis #0F5132
- Background: Alb #FFFFFF

Text Labels (în română):
- Next → "Următorul"
- Previous → "Anterior" 
- Submit → "Trimite"
- Continue → "Continuă"
- Retry → "Reîncearcă"
- Review → "Revizuiește"
```

### Variables Predefinite

```javascript
// Progress Tracking
CompletedSlides = 0
TotalSlides = 0 // actualizează manual
ProgressPercent = 0

// User Info
UserName = ""
UserEmail = ""

// Quiz Tracking
QuizAttempts = 0
BestScore = 0
CurrentScore = 0

// Navigation Control
AllowNext = True
AllowPrevious = True
MenuEnabled = True

// Feature Toggles
AudioEnabled = True
ShowHints = True
ShowTranscript = False
```

### Triggers Utile Predefinite

**Auto-Progress Tracking:**
```
Trigger: Add 1 to CompletedSlides
When: Timeline starts on slide
Condition: If this is first visit

Trigger: Calculate ProgressPercent
When: Variable CompletedSlides changes
Action: Divide CompletedSlides by TotalSlides, multiply by 100
```

**Audio Toggle:**
```
Trigger: Mute audio
When: User clicks AudioToggle button
Condition: If AudioEnabled = True
Action: Set AudioEnabled to False

Trigger: Unmute audio
When: User clicks AudioToggle button  
Condition: If AudioEnabled = False
Action: Set AudioEnabled to True
```

**Smart Next Button:**
```
Trigger: Disable Next button
When: Timeline starts on slide

Trigger: Enable Next button
When: [Condiție completare - ex: media completes, interaction completes]
```

## 📦 Ce Este Inclus în Fiecare Template

### Slide-uri Template (păstrează pentru referință)

**Slide 1.1: "Cover - Template Instructions"**
- Explicație cum să folosești template-ul
- Quick start guide
- Link către documentație completă

**Slide 1.2-1.5: "Example Slides"**
- Exemple pentru fiecare tip de layout
- Sample content
- Design best practices demonstrate

**Slide 2.1: "Your Title Slide - Edit Me"**
- Primul slide real al lecției tale
- Pre-formatted, gata de editat

**Slide 2.2+: "Blank Slides - Duplicate Me"**
- Slide-uri blank cu fiecare layout
- Duplicate și editează pentru lecția ta

### Slide Layers Template

**"Info Layer" Template:**
```
Purpose: Display additional information
Elements:
- Semi-transparent overlay (block interaction cu base)
- Info box (centru, alb, shadow)
- Title, content, close button
Triggers:
- Show layer: when user clicks info icon
- Hide layer: when user clicks close button
```

**"Hint Layer" Template:**
```
Purpose: Provide progressive hints
Elements:
- Small hint box (sus-dreapta)
- Hint text
- "Got it" button
States: Hint1, Hint2, Hint3 (progresive)
```

**"Feedback Layer" Template:**
```
Purpose: Quiz/interaction feedback
Variants:
- Correct feedback (verde)
- Incorrect feedback (roșu)
- Try again feedback (portocaliu)
Elements: Icon, message, explanation, button
```

### Character Assets (dacă includere)

**Ana - Account Manager:**
- ana-neutral.png
- ana-happy.png  
- ana-thinking.png
- States predefinite pentru ușor switch

**Speech Bubbles:**
- Template pentru dialog boxes
- Multiple styles (casual, professional, thinking)

### Sound Effects Incluse

```
sfx-correct.mp3 - Pleasant ding
sfx-incorrect.mp3 - Soft error sound
sfx-click.mp3 - Button click
sfx-reveal.mp3 - Information reveal
sfx-complete.mp3 - Completion celebration
```

_(Notă: Asigură-te că ai licență pentru orice audio inclus)_

## 🛠 Cum să Customizezi Template-urile

### Schimbarea Culorilor

**Metodă 1: Design Colors**
1. Design > Colors > Edit Colors
2. Modifică culorile din palette
3. Aplică la tot proiectul

**Metodă 2: Slide Master**
1. View > Slide Master
2. Selectează Master Slide
3. Modifică culori, fonts, elements
4. Schimbările se aplică la toate slide-urile care folosesc acest master

### Adăugarea Logo-ului Tău

1. View > Slide Master
2. Insert > Picture > [logo-ul tău]
3. Poziționează în header sau footer
4. Adjust size și opacity dacă necesar
5. Close Master View

### Modificarea Fonturilor

1. View > Slide Master
2. Format > Replace Fonts
3. Alege font vechi și font nou
4. Replace All

**Atenție:** Asigură-te că fontul nou:
- Este instalat pe sistemul tău
- Suportă caractere românești
- Este lizibil la dimensiuni mici

### Crearea Layout-ului Tău Custom

1. View > Slide Master
2. Click-dreapta pe un layout existent > Duplicate Layout
3. Redenumește (ex: "My Custom Layout")
4. Editează: adaugă, șterge, rearanjează elemente
5. Close Master View
6. New Slide > My Custom Layout (va fi disponibil)

## 📖 Best Practices pentru Folosirea Template-urilor

### DO (Fă)

✅ **Salvează ca nou proiect** imediat (nu edita template-ul original)
✅ **Studiază slide-urile example** înainte de a începe
✅ **Folosește layouturile predefinite** pentru consistență
✅ **Păstrează slide-urile template** pentru referință
✅ **Documentează modificările** majore pe care le faci
✅ **Testează triggers-urile** înainte de a adăuga conținut complex

### DON'T (Nu face)

❌ **Nu edita direct template-ul** (salvează ca nou proiect)
❌ **Nu mixa prea multe stiluri** (păstrează consistența)
❌ **Nu șterge slide masterul** (poți strica layouts)
❌ **Nu modifica variabilele** fără să înțelegi impactul
❌ **Nu adăuga prea multe fonturi** (max 2-3)

## 🔄 Actualizare Template-uri

Când sunt disponibile versiuni noi:

1. **Backup proiectul curent**
   - File > Save As > `[project]-backup-[date].story`

2. **Compară schimbările**
   - Verifică ce e nou în template actualizat
   - Decide ce vrei să adopți

3. **Aplică selectiv**
   - Copiază doar elementele dorite (slide master, layouts, triggers)
   - Paste în proiectul tău

4. **Testează extensiv**
   - Verifică că nimic nu s-a stricat
   - Test all interactions

## 📝 Creare Template Propriu

Dacă vrei să creezi propriul template:

1. **Start cu un proiect blank**
   - File > New Project

2. **Configurează Slide Master**
   - View > Slide Master
   - Design master slide și layouts
   - Setează fonts, colors, common elements

3. **Configurează Player**
   - Design > Player
   - Customizează culori, features, text labels

4. **Creează variabile și triggers standard**
   - Define variables comune
   - Setup triggers reutilizabile

5. **Adaugă slide-uri template**
   - Create example slides
   - Add instructions

6. **Documentează**
   - Creează slide "How to Use"
   - External documentation

7. **Salvează ca template**
   - File > Save As > `template-[name].story`
   - Păstrează în folderul template-uri

8. **Testează**
   - Duplicate template
   - Creează un proiect sample
   - Verifică că totul funcționează

## 🎓 Video Tutorial (Link când disponibil)

- "Cum să folosești Excel Basic Template" (5 min)
- "Customizare Slide Master în Template-uri" (8 min)
- "Creare Template Propriu de la Zero" (15 min)

---

## ❓ FAQ

**Q: Pot folosi template-urile pentru proiecte comerciale?**
A: Da, template-urile din acest repo sunt pentru uz personal și educațional. Verifică licențele pentru orice asset terță parte inclus.

**Q: Cum actualizez template-ul fără să pierd munca făcută?**
A: Nu actualiza template-ul direct în proiectul tău activ. În schimb, deschide template-ul nou separat și copiază selectiv elemente noi (slide master, layouts) în proiectul tău.

**Q: Pot combina elemente din ambele template-uri?**
A: Da! Deschide ambele proiecte, copiază slide-uri sau elemente din unul în altul. Asigură-te că importi și slide masterul dacă copiezi slide-uri formatate.

**Q: Template-ul funcționează cu versiuni mai vechi de Storyline?**
A: Template-urile sunt create în Storyline 360 (latest). Backwards compatibility nu e garantată. Recomandare: upgrade la Storyline 360.

**Q: Unde găsesc mai multe template-uri?**
A: 
- E-Learning Heroes (community.articulate.com/downloads)
- Articulate官方 template library
- Community-shared templates

---

**Baftă la crearea lecțiilor tale! 🚀**

_Dacă întâmpini probleme cu template-urile, deschide un issue în acest repository._
