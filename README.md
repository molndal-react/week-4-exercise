## Hangman PT2

Vi ska nu fortsätta på Hangman uppgiften vi först påbörjade. Om ni inte är klara med de första uppgifterna från PT1, så måste dessa bli klara innan PT2 påbörjas. 

PT2 handlar om främst tre saker

 - Gör om PT1 enligt feedbacken jag gav
 - Gör om till hooks
 - Bygga klart spelet

I PT1 gjorde vi endast halva spelet och i denna del ska vi göra klart resterande och använda oss av de tekniker vi har lärt oss under veckorna. 

# Steg 1
Introducera en ny variabel som ska hålla antal felgissningar. Om denna överstiger 6 så ska spelet avsluta och användaren har förlorat

# Steg 2
Ladda ner och importerar dessa bilder. Lägg in dem i er */images* folder. 

[Bild 1](https://ibb.co/GThsskf)
[Bild 2](https://ibb.co/mtcVhf2)
[Bild 3](https://ibb.co/bL98bKG)
[Bild 4](https://ibb.co/V312S3Q)
[Bild 5](https://ibb.co/D4RgmCS)
[Bild 6](https://ibb.co/6RzRKq2)

# Steg 3
Lägg till en funktion som hämtar vilken bokstav användaren trycker på och sedan kontrollera ifall denna bokstav finns i det gömda ordet.

 1. Finns bokstaven så ska bokstaven renderas ut på rätt position i de horisontella strecken. 
 2. Finns inte ordet så ska användaren få veta att han har gissat fel och antal gissningar kvar ska minskas med ett
 3. Om användaren gissar fel så ska även nästa bild renderas ut (t.ex om användaren ser bild 1 så ska bild 2 visas)


Du måste alltså hålla koll på vilka bokstäver användaren har matat in under omgången.
 
 # Steg 4
 Om användaren har gissat rätt ord innan gissningarna är slut så ska den få upp en text "Grattis du har gissat korrekt" sedan en knapp som låter användaren starta om

Om användaren har slut på gissningar så ska användaren få se de rätta ordet samt en text som säger "Du har förlorat". Användaren ska även här se en knapp som låter den starta om.
