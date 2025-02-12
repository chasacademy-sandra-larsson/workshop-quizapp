# Gruppuppgift: Skapa ett Quiz med Next.js och Global State

I det här gruppprojektet ska ni skapa en enkel quizapp med hjälp av Next.js och Context för global state-hantering.

### Sätt upp projektet

1. Öppna en terminal och navigera (`cd`) till den katalog där ni vill skapa ert projekt.
2. Skapa ett nytt Next.js-projekt: `npx create-next-app@latest quiz-app`.
3. Gå in i projektet: `cd quiz-app`.

## Projektinstruktioner

- Använd Next.js routing för att skapa minst två sidor: en **Admin-sida** och en **Quiz-sida**.
- Använd dig av Reakt Hook Form för formulärhantering

  - På **Admin-sidan** ska administratörer kunna lägga till, ta bort och uppdatera quizfrågor.
  - På **Admin-sidan** ska administratörer kunna skapa ett quiz med X antal frågor och tillhörande svar 
  - På **Quiz-sidan** ska användare kunna starta ett quiz, välja svar på flervalsfrågor, och till slut se sitt resultat.
  - På **Quiz-sidan** ska användare kunna se quiz, välja svar på flervalsfrågor, och till slut se sitt resultat.

- Designa quizfrågor som flervalsfrågor där användaren väljer ett svar från flera alternativ.

- Överväg vilken data som behövs för att skapa frågor med tillhörande svarsalternativ och hur ni kan hålla reda på antal rätt i ett quiz.

- Implementera lämplig Context med useContext för atthantera ett befintligt quiz.

---

### :boom: Mål med uppgiften

Efter denna uppgift ska ni ha fördjupad förståelse för global state-hantering i moderna webbapplikationer och hur man skapar interaktiva, dynamiska webbsidor med Next.js.

---

### :runner: Extrauppgifter

1. **Lägg till spelare**: Implementera funktionalitet för att låta användare ange sina namn innan de startar quizet. Håll reda på vilken spelare som spelar och visa en **high-score-sida** med de bästa resultaten.

2. **Skapa flera quiz**: Utveckla applikationen så att den har flera olika quiz på separata sidor. Användare kan välja vilket quiz de vill ta från en huvudmeny.

3. **Använd localStorage**: Implementera localStorage för att spara och ladda quizfrågor, så att admin kan återanvända dem även efter att webbläsaren stängts.

4. **Responsiv design**: Se till att ert quiz ser bra ut och fungerar på både mobiltelefoner, surfplattor och datorer.

5. **Stil och användarupplevelse**: Använd CSS eller ett ramverk som Tailwind CSS för att förbättra användargränssnittet och användarupplevelsen på er quizsida.
