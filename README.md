Artikelpagina's
Next.js project voor de opdracht Reactiviteit: UX/UI Ontwerp en gedrag.
🔗 Live site: https://jouw-site.netlify.app

Artikels

UX/UI-beslissingen
Visuele hiërarchie
Elk artikel opent met een groot H1-titel, gevolgd door een subtitel en auteur/datum in kleinere tekst. Zo weet de lezer meteen wat het artikel is en wie het schreef, zonder te hoeven zoeken.
Typografie

Koppen gebruiken een groter lettertype (text-3xl / text-2xl) met font-bold voor duidelijke hiërarchie.
Bodytekst staat op text-base met leading-relaxed voor een comfortabele regelafstand — dit verbetert de leesbaarheid aanzienlijk tegenover de oorspronkelijke PDF-lay-out.
Kleur van de bodytekst is text-gray-800 in plaats van pure zwart, wat oogvermoeidheid vermindert bij langere teksten.

Witruimte & spacing
Ruime padding (px-6 py-10) en maximale breedte (max-w-2xl mx-auto) zorgen dat de tekst nooit te breed wordt. Brede tekstregels verlagen de leesbaarheid — dit is een van de UI-verbeterpunten die we identificeerden in de PDF-analyse.
Navigatie
Een vaste header bovenaan elke pagina met links naar de drie artikels maakt het eenvoudig om te wisselen zonder de back-button te gebruiken. De actieve paginalink wordt visueel benadrukt.
Responsive design
De lay-out past zich aan via Tailwind-breakpoints: op mobiel is de padding kleiner en de tekst iets kleiner geschaald (sm:text-base text-sm), zodat het artikel goed leesbaar blijft op elk schermformaat.
Herbruikbare componenten

Header — gedeelde navigatie op elke pagina
Footer — consistente afsluiting met bronvermelding
ArticleLayout — wrapper met de juiste spacing en max-breedte die elke artikelpagina gebruikt


Installatie
bashnpm i
npm run dev
Open http://localhost:3000 in je browser.

Tech stack

Next.js — paginastructuur & routing
Tailwind CSS — alle styling
Lucide React — iconen in de navigatie
Deployment via Netlify
