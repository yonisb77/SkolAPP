SkolSystem Console App

📚 SkolSystem är en konsolapplikation byggd i .NET som hanterar elever, kurser och registreringar. Applikationen använder Database First via Entity Framework Core och SQL Server, samt LINQ för rapporter. Den är utvecklad för att ge en stabil och användarvänlig hantering av skoldata.

Funktioner
📝 Grundläggande funktioner

Lista alla elever och kurser.

Registrera elever på kurser.

Uppdatera betyg (endast IG eller G).

Ta bort elever, inklusive deras kursregistreringar.

📊 Rapporter

Elever per kurs (visar vilka elever som är registrerade på varje kurs).

Möjlighet att enkelt lägga till fler rapporter, t.ex. kurser per elev.

⚡ Stabilitet

Validerar användarinput (tomt, fel format, heltal).

Felhantering med try/catch för att programmet inte ska krascha.

Betyg kan endast sättas till giltiga värden: IG eller G.

🎨 Användarvänlighet

Konsolen använder UTF-8, vilket gör att emojis fungerar för att göra menyn mer visuell.

Tydliga meddelanden vid fel och bekräftelse på utförda operationer.

Teknologi

.NET 7 Console App

C# 11

Entity Framework Core 7 (Database First)

SQL Server (databas)

LINQ för rapportering
