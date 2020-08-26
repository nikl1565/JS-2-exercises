# JS-2-exercises

Øvelser  til 2 semester Javascript intro <br>
Hvert script bør initialiseres først (se materiale om start funktion) <br>
# Instrukser står også i bunden af hver øvelse :)

# øvelse 1 instrukser 

### 1 - Instrukser Overblik
Få knapperne til at kunne skifte farven på bolden med js.
                <br> Knapperne har id'erne: "redBut", "yellowBut", og "blueBut".
                <br> De færdige farve-classes i css hedder: "red", "yellow", "blue", - de har allerede hver sin baggrundsfarve.
                <br> Bolden tilgås med id'et "bold".
                <br>

### 2 - Instrukser med Hjælp
 Initialiser scriptet (se materiale for start funktion).
                <br> Hver knap skal selectes, og tildeles sin egen funktion med klik-event. Start med en af knapperne og dens funktion.
                <br> I funktionerne: Du kan bruge classList.add, og classList.remove for at skifte farven på bolden. Husk bolden også skal selectes.
                <br> Finte: nogle classes skal måske fjernes, når man kun skal bruge 1..
### 3 - Videre - Hvis du tør 
Når man klikker på bolden skal farven forsvinde igen
                <br>lav en funktion der fjerner alle farver, som du også kalder før du lægger ny farve på..
               

# øvelse 2 instrukser 

### 1 - Instrukser Overblik
Knappen skal skifte tekst når man rør ved den med musen - til noget du selv synes er sjovt.
                <br> Når musen fjerner sig, skal teksten skifte tilbage igen.
                <br> knappens id er "bigBut".

### 2 - Instrukser med Hjælp
Initialiser scriptet (se materiale om start funktion).
                <br> knappen skal selectes og kalde 2 funktioner - denne gang med en anden event end "click". En knapfunktion til at "røre" og en andent il at "slippe" knappen igen.
                <br> Da du skal bruge den selectede knap mange gange er det smart at gemme den som variabel. (i toppen af scriptet)
                <br> I knappens funktioner: Vælg den dom-manipulation, som kan erstatte en tekst..
                <br> Finte: Gem den oprindelige tekst i en variabel, og også den nye.
                <br> Alle variabler skal ligge udenfor funktionerne, i toppen af scriptet, for at kunne læses af funktionerne..

### 3 - Videre - Hvis du gider 
Lad også knappen skrive forskellige tekster når man klikker, dobbeltklikker ..
                <br>Lad den skifte farve og blive firkantet . - se øvelse 1
                <br>Lav en lille knap ved siden af, med sine egne ord ..
               


# øvelse 3 instrukser 

### 1 - Instrukser Overblik
Få Tallene tilbage i de tilsvarende bokse. Klikker man på første boks, skal Tallet 1 komme tilbage. Samtidig skal det gamle tal sendes over til den boks, hvor tal 1 var havnet..
                <br>"spillet" er umuligt at gennemføre hvis ikke du klikker dig frem i den rigtige læse-retning. Hold øje med hor tallene smutter hen, for at skifte de rigtige ud.
                <br> boksene har id'erne: "box1", "box2", "box3"... indtil 10.
                <br> Når en boks bliver klikket får den også en class med blå border: ".ok".

### 2 - Instrukser med Hjælp
Initialiser scriptet (se materiale om start funktion).
                Initialiser scriptet (se materiale for start funktion).
                <br> Hver boks skal selectes, og tildeles sin egen funktion med klik-event.
                <br> Start med den første boks og dens funktion. Den anden boks (den tallet gemmer sig i - her er det box2, der indeholder tallet: 1) skal også refereres til i den funktion, (da indholdet skal ændre sig til: 10) . Du skal bruge den dom-manipulation der kan ændre tekst.
                <br> Du kan da ændre tallene ved at skrive dem direkte, eller du kan referere til gemte tal-variabler.
                <br> Du kan tilføje class'en ".ok" til den boks der er klikket på.
                <br> Finte: alle boksenes selectorer skal være tilgængelige som variabler til alle funktionerne.
                <br> Hvis funktionen for box2 først skal kunne aktiveres efter funktion 1, er det smart at kalde den indenfra funktion 1, osv.
                <br> EventListeneren skal fjernes igen, hvis man kun skal kunne klikke 1 gang..
                <br> En af de sidste funktioner får flere tal til at gå op - disses boxe skal så have den rigtige borderfarve, og så skal man ikke kunne klikke videre.


# øvelse 4 instrukser 

### 1 - Instrukser Overblik
Denne laver du stor set uden instrukser.
                <br> Vi har 1 boks med id "#box". I den lægger du et lille billede af fx. digselv - som sur - og når man klikker skal det skiftes ud med et andet lille billede fx. af dig selv som glad.
                <br> Du må selv om du lægger det ind som billede eller som baggrundsbillede. Javascripten i klik-funktionen vil dog blive forskellig afhængig af din metode.
### 2 - Den sværere..
Klik-funktionen skal "toggle"..
                <br> Du kan vente til du har code-campet dig frem til if-else og booleans (true-false variabler) -
                <br> Eller - du kan google dig frem til classList.toggle.
                <br> GOD ARBEJDSLYST
