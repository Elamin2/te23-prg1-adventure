# Äventyr

Vad är det okej att använda AI till i programmeringen?

Exempelvis att skriva en berättlse, skapa ett innehåll. Problemlösningen är ditt jobb. AI kan hjälpa dig att skapa innehållet.

## Prompter

Du är en expert på att skriva äventyr i formatet [choose your own adventure]. Du har en väldigt lång erfarenhet av att skriva engagerande berättelser för [ungdomar] i det här formatet. 
Jag behöver din hjälp med skrivandet. Du kommer att svara i formatet av en python lista med dicts.
Jag klistrar in formatet som du ska svara i. Bekräfta att du förstår.

### Formatet 

Här är formatet för att skriva en berättelse i formatet [choose your own adventure]. 

```
format = [
    {
        "id": 1,
        "title": "String title for page",
        "text": "String text for page",
        "options": [
            {"text": "Option 1 with next page id", "next_id": 2},
            {"text": "Option 2 with next page id", "next_id": 3},
        ],
    },
]
```

## Nu är det dags att skriva en berättelse

Du har förberett AI med förutsättningarna. Vill du styra ännu mer över vad den kommer att skriva så skriv så mycket om förutsättningarna som möjligt. Vad är det för kontext, vilka karaktärer finns det, vilka är de viktigaste händelserna?

## Uppgift

Du ska arbeta med att ta fram en berättelse. Du ska sedan använda den färdiga koden för att visa upp berättelsen. Du ska skapa en ny fil för din berättelse och importera den till app.py.

Skapa en berättelse i formatet choose your own adventure med minst 5 sidor.
Skapa en ny fil för din berättelse och spara den i formatet som en lista med dicts.
Importera din berättelse till app.py genom att använda import.
Kör programmet och testa din berättelse.
Det är grunden för uppgiften.

Utveckling
Här finns en lista med förslag på hur du kan utveckla din berättelse och programmet:

Lägga till fler sidor och alternativ i berättelsen.
Skapa en huvudmeny för spelaren. Tips: använd en loop för att låta spelaren välja att starta ett nytt spel eller avsluta.
Spara en historik över användarens val och låta dem gå tillbaka till tidigare sidor. Tips: använd en lista för att spara historiken, du lägger till spelarens val i listan med append.
Skapa en replay-funktion som spelar upp berättelsen från historiken.
Lägga till fler funktioner för att förbättra användarupplevelsen, som att spara och ladda spel.
Stridsystem: Lägg till stridssekvenser där spelaren måste välja olika alternativ för att vinna striden.
Använd dig av sten, sax, påse för att simulera striden. A slår B, B slår C, C slår A.
Fienden kan vara en dict med olika egenskaper.
Skapa en funktion för combat som tar in spelarens liv, fiendens dict och sedan promptar stridssekvensen, returnera True om spelaren vinner och False om spelaren förlorar.
Lägg till fler val för spelaren, som att välja en karaktär i början som påverkar spelet.
Att kunna samla föremål under spelets gång.
inventory system, ett inventory(lista) med föremål(dicts) som spelaren kan samla på sig.
Faktiskt kunna använda föremålen för att lösa problem.
Skapa en poängräknare som ökar eller minskar beroende på spelarens val.
Lägg till en tidsbegränsning för att göra val, där spelaren måste välja inom en viss tid eller förlora.



