# Utrdimo osnove

`````{admonition} Programska oprema
:class: important
- [ukazna vrstica](namestitev:ukazna),
- [Visual Studio Code](namestitev:vscode).
`````

## 1. naloga: opisovanje vzorcev z regularnimi izrazi

[Regularni izrazi](https://en.wikipedia.org/wiki/Regular_expression) 
(angl. _regular expressions_ ali kratko _regex_) so zaporedja znakov, 
s katerimi lahko opišemo vzorce v navadnem besedilu.

Natančno ujemanje ste gotovo že kdaj videli - to je najbolj enostavna vrsta regularnega izraza.
V besedilu bi lahko poiskali vse pojavitve besede `kuža` z regularnim izrazom `kuža`.
Kaj pa če želite poiskati vse številke v besedilu?
To bi naredili z regularnim izrazom `\d+`: 
`\d` je vzorec ki predstavlja eno števko,
`+` pa pomeni eno ali več ponovitev tistega, kar piše pred znakom.

Regularni izrazi so lahko sila uporabni, in ta naloga je namenjena temu,
da se z njimi na kratko seznanite. 

Kakih 20 minut rešujte lekcije na spletni strani [RegexOne](https://regexone.com),
na spletni strani [RegexLearn](https://regexlearn.com/learn/regex101), ali pa na obeh.
Na gumb _Continue_ vam ni treba klikniti, dovolj je, da stisnete vnašalko <kbd>↵</kbd>.
Če ste regularne izraze že kdaj uporabljali, se lahko preizkusite v 
[regex križanki](https://regexcrossword.com).

## 2. naloga: ukazna vrstica, urejevalnik in Git

V tej nalogi boste na vsakem koraku dobili navodila za naslednji korak.
Navodila pozorno preberite, včasih bo v njih pisalo kaj, kar boste rabili šele kasneje.
V navodilih bo včasih tudi povezava na bolj podrobna navodila.

1. Začnite tako, da naložite arhiv (stisnjeni imenik) s [poglavji Visoške kronike](05-utrdimo-osnove/visoska-kronika.zip).
2. Imenik morate [odpakirati](faq:zip), sicer ne boste mogli nadaljevati.
   V poglavjih Visoške kronike je skrita QR koda, do katere boste prišli v naslednjih korakih.
   `head -n 147 vaje/05-utrdimo-osnove/visoska-kronika/-out/poglavje05.txt | tail -n 20`
3. [Odprite imenik v ukazni vrstici](faq:ukazna-imenik). 
   Z ukazom `pwd` lahko preverite, če ste v pravem imeniku: na koncu poti mora pisati `visoska-kronika`.
4. 



1. pogrepaj kose QR kode iz Visoške kronike (vrstice bodo oštevilčene)
2. počisti QR kodo, recimo v VSCode: sort, brisanje znakov, da se vrstice pravilno poravnane in QR koda dela
3. QR koda pelje na spletno stran, GitHub pages (lahko tudi z online decoderjem, recimo https://qrcodedynamic.com/qr-reader in screenshotom)
4. v izvorni kodi spletne strani najdejo namig za naslednji korak
5. klonirajo repozitorij; s checkoutom poiščejo pravi commit
6. ta commit ima skripto, ki jo poženejo, ki spremeni datoteke v repozitoriju
    ```
    chmod +x namig.sh 
    ./namig.sh 
    ```
7. z git status pogledajo spremembe, te so spet namig za zadnji korak
8. rickroll

Namen je, da ponovijo oz. vidijo nekaj malega novega pri ukazni, gitu in html/css.

## 3. naloga: postavite spletno stran

TODO: `username.github.io`? Domača naloga?

1. Odprite imenik s svojim repozitorijem.
2. Izberite si eno od HTML datotek, ki ste jih naredili pri vajah,
   in jo kopirajte vrhnji imenik.
   Preimenujte datoteko v `index.html` (sicer ne bo delovalo).
   V vrhnji imenik prekopirajte tudi slike in oblikovanje.
3. Zabeležite spremembe in jih pošljite na strežnik.
4. V brskalniku obiščite svoj repozitorij in pojdite na zavihek _Settings_.
5. V stranskem meniju izberite _Pages_.
6. V razdelku _Build and deployment_ pod _Branch_ izberite glavno vejo
   (`main` ali `master`) in kliknite na gumb _Save_.
7. Pustite ta zavihek odprt in se lotite naslednje naloge.
   Ko jo boste končali, se bi moral ta zavihek posodobiti z naslovom 
   vaše spletne strani.
   Pisalo bo _"Your site is live at ..."_.

Če boste urejali katero od datotek spletne strani, ter zabeležene spremembe
poslali na strežnik, se bo v nekaj minutah (ponavadi hitreje kot v desetih)
posodobila tudi spletna stran.

## Domača naloga

1. Preberite si začetek [poglavja o LaTeX-u](06-uvod-v-latex) (do 1. naloge).