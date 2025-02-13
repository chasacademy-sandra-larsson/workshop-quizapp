#  Workshop: Skapa ett Quiz med Next.js och Global State

I den här workshopen ska ni skapa en enkel quizapp med hjälp av Next.js och Context för global state-hantering.

### Sätt upp projektet

1. Öppna en terminal och navigera (`cd`) till den katalog där ni vill skapa ert projekt.
2. Skapa ett nytt Next.js-projekt: `npx create-next-app@latest quiz-app`.
3. Gå in i projektet: `cd quiz-app`.

## Projektinstruktioner

- Använd Next.js routing för att skapa minst två sidor: en **Admin-sida** och en **Quiz-sida**.

  - På **Admin-sidan** ska administratörer kunna lägga till, ta bort och uppdatera quizfrågor.
  - På **Quiz-sidan** ska användare kunna starta ett quiz, välja svar på flervalsfrågor, och till slut se sitt resultat.
 
- Använd dig av Reakt Hook Form för formulärhantering 

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

4. **Validering av formulär**: Använd biblioteket Zod för att validera formuläret för att skapa frågor

8. **Design och komponenter**: Använd CSS, Tailwind CSS och eller ett komponentbibliotek som shadcn
