# Lärarguide för att stödja elevers problemlösning med AI-stöd

Detta är en interaktiv webbapplikation designad för att assistera lärare med att ge målinriktad feedback till elever under deras problemlösningsprocess. Applikationen kombinerar en strukturerad, interaktiv guide med en avancerad AI-chatbot, båda baserade på principer för effektiv läraråterkoppling.

## Funktioner

* **Interaktiv Lärarguide:**

  * Navigera genom fördefinierade kategorier (A, B, C, D, E) som representerar olika stadier och typer av elevsvårigheter i problemlösning.

  * Få tillgång till specifika förslag på frågor och återkoppling för varje scenario, direkt hämtade från den ursprungliga lärarguiden i PDF-format.

* **Avancerad AI-bot:**

  * Ställ frågor eller beskriv elevsituationer i ett chattgränssnitt.

  * AI:n har ett konversationsminne och kan svara på följdfrågor, vilket möjliggör en mer dynamisk dialog.

  * **Valbara AI-fokusområden:**

    * **Standard Lärarguide:** AI:n genererar återkoppling baserad på de breda principerna i den inbyggda lärarguiden.

    * **Matematisk Resonemangsförmåga:** AI:n utökar sin kontext med kompletterande principer som är specifika för att stödja elevers matematiska resonemangsförmåga, vilket leder till mer specialiserad feedback inom matematik.

## Källan till de Kompletterande Principerna (Matematisk Resonemangsförmåga)

De kompletterande principerna som används i AI-modellen "Matematisk Resonemangsförmåga" är en syntes baserad på väletablerade ramverk och forskningsfält inom matematikdidaktik. Dessa principer inkluderar:

* **Analysera och förstå problemet**

* **Resonera matematiskt**

* **Välja och använda metoder**

* **Kommunicera matematiska idéer**

* **Utvärdera och reflektera**

Dessa dimensioner av matematisk kompetens betonas i internationella riktlinjer (t.ex. National Council of Teachers of Mathematics - NCTM) och den svenska läroplanen (Lgr22, Gy11) för matematik. Syntesen är en destillering av insikter från forskning inom matematikdidaktik som fokuserar på hur elever utvecklar dessa förmågor och hur effektivt lärarstöd kan utformas.

## Tekniker som Använts

* **React:** För att bygga det dynamiska och interaktiva användargränssnittet.

* **Tailwind CSS:** För en modern och responsiv design.

* **Google Gemini API:** Används för att driva AI-botens konversationsförmåga och generera relevant feedback baserat på angiven kontext och fokusområde.

## Hur man Kör Applikationen

1. **Spara koden:** Kopiera hela den medföljande React-koden (som är inkapslad i en `App` komponent).

2. **Klistra in i en HTML-fil:** Skapa en ny fil (t.ex. `index.html`) och klistra in koden. Den förväntas köras i en miljö som är konfigurerad för React. I en Canvas/Immersive-miljö sker detta automatiskt. Om du kör lokalt behöver du en grundläggande React-inställning (t.ex. med Create React App eller Vite).

3. **Öppna i webbläsaren:** Öppna `index.html` i din webbläsare. Applikationen bör nu laddas och vara interaktiv.

## Viktigt att Notera

* AI-genererade svar är **förslag** och ska alltid granskas och anpassas av en mänsklig lärare. AI:n är ett verktyg för stöd, inte en ersättning för professionell bedömning.

* Användning av Google Gemini API kan medföra kostnader beroande på din förbrukningsnivå.
