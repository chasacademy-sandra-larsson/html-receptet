# HTML Receptet

1. Skapa filen index.html i VS Code
2. Utgå från grundmallen för HTML 

```html
<!DOCTYPE html>
<html lang="sv">
    <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sidans titel</title>
    </head>
<body>
    <!-- Här lägger jag mitt innehåll--> 
</body>
</html>
```
3. Lägg in all text från filen recipe.txt inuti body-taggen och strukturera html-dokumentet genom att märka 
upp varje del med lämplig html-tagg.  

## Rekommenderade taggar för detta dokument: 

```
<h1> - <h5>                      Rubriker och underrubriker
<p>                              Textstycke
<strong>                         Stark betonad text (fetstil)
<em>                             Viktig text (kursiv) 
<a href="#">Länk</a>             Länk där adressen skrivs i #
<button>                         Klickbar knapp
<img src="path/bild.jpg>         Bild
<ul>
     <li></li>
     <li></li>
</ul>                           Oordnad lista
<ol> 
   <li></li>
   <li></li>
<ol>                            Ordnad lista
```


## Diskutera

1. Vad har HTML för roll inom frontend?
2. Vad defineras som start- och sluttagg, attribut, element?
3. Vad är block- och inline-element? 
4. Vad innebär det att validera ett html-dokument?

## Sätt upp projektet med Github

Följ nedanstående punkter för att komma igång:

1. **Skaffa ett konto på GitHub** om ni inte redan har ett.

2. **Gå till GitHub** och skapa ett nytt repository:
   - Klicka på **New Repository**.
   - Namnge repositoryt efter uppgiften.
   - Välj **Public** för att jag ska kunna se koden.
   - Lämna alla andra inställningar som standard och klicka på **Create Repository**.

3. **Kopiera klonings-URL:en** för repositoryt:
   - När repositoryt har skapats, kopiera klonings-URL:en (börjar med `https://github.com/`).

4. **Öppna VS Code** och välj **Clone Repository**:
   - I VS Code, tryck på `Ctrl+Shift+P` (eller `Cmd+Shift+P` på Mac) för att öppna **Command Palette**.
   - Skriv **"Git: Clone"** och välj det alternativet.
   - Klistra in klonings-URL:en du kopierade från GitHub och välj en plats på din dator där mappen ska sparas.

5. **Öppna den klonade mappen i VS Code**:
   - När kloningen är klar, välj **Open** för att öppna den klonade mappen i VS Code.

6. **Lägg till dina filer i mappen**:
   - Lägg till de filer som hör till uppgiften i den klonade mappen.

7. **Stage och commit dina ändringar**:
   - Gå till **Source Control**-panelen (klicka på grenen i vänstermenyn).
   - Klicka på **+** för att "stage:a" dina ändringar.
   - Skriv ett commit-meddelande och klicka på **commit-ikonen** (bockmarkeringen).

8. **Push dina ändringar till GitHub**:
   - Klicka på **"Sync Changes"** eller använd `Ctrl+Shift+P` och skriv **"Git: Push"** för att skicka dina commits till GitHub.

9. **Öppna ditt repository på GitHub**:
   - Gå tillbaka till ditt repository på GitHub och uppdatera sidan för att se de senaste ändringarna du har pushat.

Det går också bra att använda tillvägagångssättet **Publicera Branch** i VS Code, då skapas ett repo från VS Code. [Läs mer här](https://vscode.github.com/)
