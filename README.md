# EFOS | Sustavi poslovne inteligencije


materijali za predavanja iz kolegija Sustavi poslovne inteligencije


## Priprema

Kako bi mogli kvalitetno razvijali svoj softver poželjno je koristiti sljedeće:
  1. alate za razvoj (IDE) kao što je npr. [Visual Studio Code](https://code.visualstudio.com/)
  2. sustav za praćenje verzije softvera (SVN) poznat kao `git`

## Visual Code

Stvoriti mapu na računalu u kojem ćemo spremati vježbe i otvoriti ga u VSCode

## Git
Koraci za korištenje:

1. **Instalirajte Git**: Ukoliko nemate Git, preuzmite i instalirajte Git sa [Git web stranice](https://git-scm.com/downloads) i pratite upute.

2. **Kreirajte mapu**: Stvorite mapu za svoj projekt na svom računalu.

3. **Kopirajte Git repozitorij**: Otvorite naredbeni redak, navigirajte do željene name i klonirajte ovaj repozitorij s `git clone https://github.com/dseverdi/BI.git`.

4. **Dodajte datoteke**: Upotrijebite `git add .` da biste dodali sve datoteke u Git repozitorij.

5. **Napravite "commit"**: Izvršite `git commit -m "Vaša poruka"` kako biste sačuvali promjene.

6. **Povežite s GitHub repozitorijem**: Stvorite prazan repozitorij imenom `BI` na GitHubu i povežite ga s lokalnim repozitorijem pomoću `git remote add origin https://github.com/vase-korisnicko-ime/BI.git`.

7. **Prenesite "commit"ove na GitHub**: Koristite `git push -u origin master` kako biste prenijeli svoje "commit"ove na GitHub. Prilikom prvog "commit"-a morat ćete se registrirati na GitHub. Koristite PAT prema sljedećim uputama kako bi to napravili.

8. Kako bi provjerili status koje promjene ste zabilježili upišite `git status`
9. Ponavljajte postupak redoslijedom 8,4,5,7 za svaku sljedeću novu promjenu

Sada imate inicijaliziran GitHub repozitorij i možete upravljati svojim projektom na GitHubu.



