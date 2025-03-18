# Web Development checklist
Personal checklist

# PROJECT SETUP
- [ ] Finns en .gitignore fil?
- [ ] Finns en README.md med projektbeskrivning och installationsinstruktioner?
- [ ] Har rätt beroenden installerats? (npm/pnpm install)
- [ ] Är ESLint och Prettier konfigurerade?

# GENERAL
- [ ] Innehåller koden swenglish?
- [ ] Är bilder i formatet PNG, SVG eller WebP?
- [ ] Är bilder inte större än XXXXXXXXXX.
- [ ] Har alla bilder en alternativ text (alt-attribut)?
- [ ] Har projektet en responsiv design?
- [ ] Testad på olika skärmstorlekar och enheter?
- [ ] Går sidan zooma in till 300% utan att sidan förstörs?

# HTML
- [ ] Används semantiska taggar korrekt? (<article>, <section>, <nav> etc.)
- [ ] Har varje sida en title och en meta description?
- [ ] Finns det en korrekt <lang>-attribut i <html>?
- [ ] Är formulär korrekt uppmärkta med <label> och <input>?
- [ ] Används aria-*-attribut för tillgänglighet där det behövs?
- [ ] Är länkar och knappar beskrivande istället för "Klicka här"?
- [ ] Laddas bilder och resurser lazy-loaded där det är lämpligt?
- [ ] Är en HTML Validering körs på sidan?

# CSS
- [ ] Är knappar, ikoner och andra klickbara ytor minst 24x24px?
- [ ] Är font-size minst 16px/1rem?
- [ ] Finns en fallback-font i font-family?
- [ ] Används en konsekvent färgpalett och typografi?
- [ ] Har flexbox/grid använts istället för float/tabeller?
- [ ] Är CSS optimerad och innehåller inte onödig kod?
- [ ] Finns det en :focus-stil för interaktiva element?
- [ ] Är en CSS Validering körd på sidan?

# JAVASCRIPT
- [ ]  Är koden modulär och återanvändbar?
- [ ]  Finns det några onödiga console.log kvar?
- [ ]  Undviks globala variabler där det är möjligt?
- [ ]  Används let och const istället för var?
- [ ]  Har async/await eller .then()-kedjor korrekt hanterad felhantering?
- [ ]  Är event listeners optimerade och inte överanvända?
- [ ]  Testad i flera webbläsare?

# ACCESSIBILITY (A11Y)
 - [ ] Har webbplatsen testats med en skärmläsare?
 - [ ] Kan alla funktioner nås och användas via tangentbordet?
 - [ ] Finns det tydliga visuella fokusmarkeringar?
 - [ ] Används role-attribut korrekt där det behövs?
 - [ ] Är färgkontrasten tillräcklig enligt WCAG?
 - [ ] Har formulär autocomplete där det är relevant?
 - [ ] Används aria-live där dynamiskt innehåll uppdateras?
 
# SEO
 - [ ] Har alla sidor en unik <title> och <meta description>?
 - [ ] Finns robots.txt och en korrekt sitemap.xml?
 - [ ] Har bilder beskrivande filnamn och alt-attribut?
 - [ ] Används korrekta rubriknivåer (h1 → h6) utan att hoppa över nivåer?
 - [ ] Är URL:er läsbara och fria från onödiga parametrar?
 - [ ] Finns det strukturerad data (schema.org)?

# PERFORMANCE
 - [ ] Är CSS och JavaScript minifierade?
 - [ ] Finns det en cache-control-policy för statiska resurser?
 - [ ] Har font-display: swap använts för att förhindra FOUT/FOIT?
 - [ ] Finns det någon onödig render-blocking JavaScript eller CSS?
 - [ ] Är webbplatsen testad i Lighthouse och PageSpeed Insights?

# SECURITY
 - [ ] Används HTTPS?
 - [ ] Är användardata korrekt validerad både på klient och server?
 - [ ] Undviks inline-JavaScript och onödiga eval()-anrop?
 - [ ] Finns det Content Security Policy (CSP) inställd?
 - [ ] Är tredjepartsbibliotek uppdaterade och utan kända sårbarheter?

# TESTING & DEBUGGING
 - [ ] Har enhetstester/skärmdumpstester implementerats?
 - [ ] Har koden testats i olika webbläsare? (Chrome, Firefox, Edge, Safari)
 - [ ] Är alla formulärfält validerade och hanterar felmeddelanden korrekt?
 - [ ] Har Lighthouse, WebPageTest eller andra verktyg använts för att analysera prestanda och tillgänglighet?
 - [ ] Har 404- och 500-sidor testats och fungerar korrekt?

# USER EXPERIENCE (UX)
 - [ ] Är laddningstider acceptabla (<2s på mobila enheter)?
 - [ ] Finns det en tydlig "call to action" där det behövs?
 - [ ] Är interaktionsanimationer subtila och inte distraherande?
 - [ ] Har användartester genomförts?
 - [ ] Är formulärfält och knappar tillräckligt stora för touch-enheter?
