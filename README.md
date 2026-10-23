## Fråga 1: Versionshantering vs vanliga filer

 - Versionshantering är kort att man kan gå tillbaka och se historiska ändringar som har skett i koden, att spara lokalt lämnar ingen historik. Genom att köra commits när ändringar har skett kan man få den historiken och gå tillbaka ifall något t.ex. slutar att fungera. Varje commit får ett eget unikt ID som underlättar för att välja rätt samt även går att jämnföra med ett annat commitID för att se förändringen där emellan.

## Fråga 2: Arbetsytan, Staging och Commits

- git status kollar vad/ om något har skett sedan senaste push, visar detta genom att ange i text vilken fil (om någon) som ändring skett på.
- git add används för att lägga till den fil som ska pushas, krävs för att git ska kunna visa flera olika commits.
- git commit används för att ge en kort och konkret beskrivning av vad som pushas och varför. Det gör det enklare att navigera i efterhand ifall något var bättre förr eller slutar fungera (delat ägande om man samarbetar kan anges där t.ex.).

- Arbetsbordet är endast lokalt och det är jag som kommer åt det tills dess att jag använder mig av staging för att på så vis lägga till den/ dom filer jag vill pusha upp och dela. Steget där emellan är att göra en commit för att på så vis underlätta för mig själv men även andra som kanske ska jobba med samma projekt och behöver kunna navigera uppdateringarna. 


## Fråga 3: Lådan hemma vs Montern på GitHub

- Ändringar som jag gör på min dator sker enbart här lokalt och jag kan jobba på helt vanligt utan uppkoppling medans det som ligger på GitHub är mer en sorts backup av det jag gör och har gjort. På GitHub kan jag inte redigera något utan endast "ta hem" en version av projektet för att lokalt hantera och göra ändringar. git push skickar min valda commit till GitHub.

- "lådan hemma" syftar på min lokala dator/ arbetsyta där alla ändringar och uppdateringar sker och "glasmontern" är GitHub där jag väljer vad jag ställer ut eller visar upp när jag är nöjd nog att pusha upp något. 

- git push utan add och commit jämnför min senaste push med det som finns på GitHub, om de matchar så är "everything up-to-date". OM det inte stämmer med mitt lokala repo så får jag påminna mig själv om att använda add och commit, sedan push.