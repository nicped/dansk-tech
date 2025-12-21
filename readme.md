# 🇩🇰 Den danske tech stack

En oversigt over danske tech-systemer som alternativer til store internationale spillere. Få inspiration til din tech stack med danske SaaS-løsninger til betalinger, analytics, monitoring og mere.

🌐 **Live på:** [dansktechstack.dk](https://dansktechstack.dk)

---

## 📖 Om projektet

I en tid hvor der ofte tales om Danmarks afhængighed af udenlandsk software, vil vi fremhæve danske systemer, vi selv har tillid til - med hovedkontor i Danmark eller med danske stiftere eller medstiftere.

Danmark har nemlig en stolt tradition inden for softwareudvikling. Teknologier som Ruby on Rails, TypeScript, C# og PHP har danske rødder, og på dette site har vi samlet en liste over stærke danske alternativer til software, der ellers typisk købes i udlandet.

### Formål

Projektet har til formål at:
- ✅ Sætte fokus på danske tech-produkter til software-virksomheder
- ✅ Give inspiration til danske alternativer i tech stacks
- ✅ Fremme synligheden af dansk tech-innovation
- ✅ Støtte danske iværksættere og software-virksomheder

---

## 👥 Hvem står bag?

Initiativet er startet af en gruppe danske iværksættere, chefer og investorer, der gerne vil bidrage til at fremme dansk tech. Se listen på [dansktechstack.dk/#iværksættere](https://dansktechstack.dk/#iværksættere).

---

## 🤝 Hvordan bidrager du?

Vi er glade for bidrag! Der er flere måder at hjælpe på:

### 1. Tilføj et nyt produkt

Har du kendskab til et dansk tech-system, der mangler på listen? Følg disse trin:

1. **Fork dette repository** (klik på "Fork" øverst til højre)
2. **Clone din fork** til din computer:
   ```bash
   git clone https://github.com/DIT-BRUGERNAVN/dansk-tech.git
   cd dansk-tech
   ```
3. **Opret en ny branch**:
   ```bash
   git checkout -b tilfoej-produkt-navn
   ```
4. **Tilføj produktet** i `index.html`:
   - Find sektionen med produkterne (søg efter `id="produkter"`)
   - **VIGTIGT**: Tilføj det nye produkt **efter** de eksisterende produkter (ikke først i listen)
   - Tilføj et nyt `<li>` element efter samme struktur som eksisterende produkter
   - Tilføj produktets billede i `images/` mappen (400x400px, PNG format)
   - Opdater også Schema.org JSON-LD sektionen i `<head>` hvis muligt

5. **Commit og push**:
   ```bash
   git add .
   git commit -m "Tilføj [Produktnavn]"
   git push origin tilfoej-produkt-navn
   ```

6. **Opret en Pull Request** på GitHub med:
   - En beskrivelse af produktet
   - Hvorfor det er relevant
   - Link til produktets hjemmeside

### 2. Forbedre eksisterende indhold

- Ret fejl eller forbedre beskrivelser
- Tilføj manglende information
- Forbedre SEO eller tekniske aspekter

### 3. Rapporter problemer

Har du fundet en fejl eller har du en idé til forbedringer? Opret et [Issue](https://github.com/DIT-BRUGERNAVN/dansk-tech/issues) på GitHub.

### 4. Del projektet

Hjælp med at sprede budskabet:
- Del på sociale medier
- Nævn det i relevante fora eller communities
- Fortæl kolleger og bekendte om projektet

---

## 📋 Retningslinjer for bidrag

### Kriterier for produkter

For at et produkt kan inkluderes, skal det opfylde følgende:

**Danske kriterier** (mindst ét af følgende):
- ✅ Hovedkontor i Danmark
- ✅ Dansk stifter eller medstifter
- ✅ Primært dansk ejerskab

**Tech stack kriterier**:
- ✅ Produktet skal kunne anvendes i en tech-stack for software-virksomheder
- ✅ Produktet skal være relevant for SaaS-firmaer, e-commerce-firmaer eller lignende tech/web-firmaer

### Produktinformation

Når du tilføjer et produkt, skal du inkludere:

- **Navn**: Produktets fulde navn (inkl. domæne, f.eks. "Alunta.com")
- **Beskrivelse**: Kort beskrivelse af hvad produktet gør (1-2 sætninger)
- **Alternativer**: Hvilke internationale systemer det er alternativ til
- **Billede**: Et screenshot eller logo (400x400px, PNG format)
- **Link**: URL til produktets hjemmeside

### Eksempel på produktstruktur

```html
<li>
  <a href="https://produkt.dk" target="_blank" rel="noopener noreferrer" class="group block">
    <div class="relative">
      <div class="absolute -inset-4 rounded-3xl bg-gradient-to-br from-orange-50 via-orange-100/50 to-amber-50 opacity-0 group-hover:opacity-100 dark:from-orange-900/20 dark:via-orange-800/10 dark:to-amber-900/20 transition-opacity duration-300 blur-xl"></div>
      <div class="relative rounded-2xl bg-gradient-to-br from-gray-50 to-gray-100 dark:from-gray-800 dark:to-gray-900 shadow-lg shadow-gray-200/50 dark:shadow-gray-900/50 group-hover:shadow-xl group-hover:shadow-gray-300/50 dark:group-hover:shadow-gray-800/50 transition-all duration-300">
        <img src="images/produkt.png" alt="Produktnavn" width="400" height="400" loading="lazy" class="aspect-square w-full rounded-2xl object-cover transition-all duration-300" />
      </div>
    </div>
    <h3 class="mt-6 text-lg/8 font-semibold tracking-tight text-gray-900 dark:text-white group-hover:text-gray-700 dark:group-hover:text-gray-200 transition-colors">
      Produkt.dk
    </h3>
    <p class="text-base/7 text-gray-600 dark:text-gray-400">
      Kort beskrivelse af produktet
    </p>
    <p class="mt-2 text-xs text-gray-400 dark:text-gray-600">
      Alternativ til: Internationalt produkt 1, Internationalt produkt 2
    </p>
  </a>
</li>
```

---

## 🛠️ Teknisk information

### Tech stack

- **HTML5**: Semantisk markup
- **Tailwind CSS**: Styling via CDN
- **Vanilla JavaScript**: Minimal JavaScript for interaktivitet
- **Static hosting**: Kan hostes på GitHub Pages, Netlify, Vercel eller lignende

### Lokal udvikling

1. Clone repositoryet:
   ```bash
   git clone https://github.com/DIT-BRUGERNAVN/dansk-tech.git
   cd dansk-tech
   ```

2. Åbn `index.html` i din browser eller brug en lokal server:
   ```bash
   # Med Python
   python3 -m http.server 8000
   
   # Med Node.js (http-server)
   npx http-server
   ```

3. Åbn `http://localhost:8000` i din browser

### Filstruktur

```
dansk-tech/
├── index.html          # Hovedside
├── robots.txt          # SEO robots fil
├── sitemap.xml         # SEO sitemap
├── favicon.svg         # Favicon
├── favicon.ico         # Favicon (ICO format)
├── apple-touch-icon.*  # Apple Touch Icons
├── og-image-*.png      # Open Graph billede
├── images/             # Billeder mappe
│   ├── *.png           # Produktbilleder
│   ├── *.jpg           # Personbilleder og andre
│   └── *.webp          # WebP billeder
└── README.md           # Denne fil
```

---

## 📝 Licens

Dette projekt er open source og tilgængeligt under [MIT License](LICENSE) (eller den licens du vælger).

---

## 📧 Kontakt

Har du spørgsmål eller forslag? Kontakt os på:

- 📧 Email: [kontakt@langsom.com](mailto:kontakt@langsom.com)
- 🌐 Website: [dansktechstack.dk](https://dansktechstack.dk)

---

## 🙏 Tak

Tak til alle der bidrager til at fremme dansk tech! Hver tilføjelse, forbedring eller deling hjælper med at gøre danske tech-systemer mere synlige.

---

**Bygget i København af folkene fra langsom.com + venner fra branchen.** 🇩🇰
