##Fråga 1: Versionshantering vs vanliga filer

 - Versionshantering är kort att man kan gå tillbaka och se historiska ändringar som har skett i koden, att spara lokalt lämnar ingen historik. Genom att köra commits när ändringar har skett kan man få den historiken och gå tillbaka ifall något t.ex. slutar att fungera. Varje commit får ett eget unikt ID som underlättar för att välja rätt samt även går att jämnföra med ett annat commitID för att se förändringen där emellan.

##Fråga 2: Arbetsytan, Staging och Commits

- git status kollar vad/ om något har skett sedan senaste push, visar detta genom att ange i text vilken fil (om någon) som ändring skett på.
- git add används för att lägga till den fil som ska pushas, krävs för att git ska kunna visa flera olika commits.
- git commit används för att ge en kort och konkret beskrivning av vad som pushas och varför. Det gör det enklare att navigera i efterhand ifall något var bättre förr eller slutar fungera (delat ägande om man samarbetar kan anges där t.ex.).

- Arbetsbordet är endast lokalt och det är jag som kommer åt det tills dess att jag använder mig av staging för att på så vis lägga till den/ dom filer jag vill pusha upp och dela. Steget där emellan är att göra en commit för att på så vis underlätta för mig själv men även andra som kanske ska jobba med samma projekt och behöver kunna navigera uppdateringarna. 


##Fråga 3: Lådan hemma vs Montern på GitHub
För Godkänt (G): Vad är skillnaden mellan mappen på din dator och repot på GitHub, och vad gör kommandot git push?
För Väl Godkänt (VG): Förklara konceptet med de två rummen / minnesytorna (lådan hemma på datorn vs glasmontern på GitHub). Förklara varför git push svarar Everything up-to-date om du har ändrat i koden men glömt att staga och committa innan du kör push.