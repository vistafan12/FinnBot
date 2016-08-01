#FinnBot - lista komend  
Wersja: 1.3 beta
### Pomoc
Komenda | Działanie | Sposób użycia
--------|-----------|--------------
`-h`, `-help`, `@BotName help`, `@BotName h`, `~h`  |  Wysyła do użytkownika prywatną wiadomość ze wskazówkami w obsłudze bota i komendami. 
`-readme`, `-guide`  |  Wysyła na kanale linki do poradników (w języku angielskim).

### Rozmowy  
Komenda | Działanie | Sposób użycia
--------|-----------|--------------
`..`  |  Dodaj nowy cytat. Pierwszy wyraz do nazwa cytatu. Reszta to treść cytatu (bez ograniczeń). Tą samą nazwę może mieć wiele cytatów. Cytat może mieć więcej niż jedną linijkę. |  .. abc Cześć cwelu.
`...`  |  Pokazuje cytat. |  .. abc
`..qdel`, `..quotedelete`  |  Usuwa cytat |  `..qdel abc`
`@BotName rip`  |  Wstawia obrazek z nagrobkiem wedle schematu "@BotName rip osoba rok_urodzenia". Osobą nie musi być użytkownik serwera. Można w tym miejscu wpisać np. "ziemniaki" (osoba nie może w nazwie mieć spacji). |  @Finn rip Cebula! 6969
`@BotName uptime`  |  Sprawdza ile Finn jest on-line.
`@BotName die`  |  Tylko dla właścicieli. Bot po wpisaniu tej komendy zostanie wyłączony.
`@BotName do you love me`  |  Spytaj się Finna, czy on cię kocha.
`@BotName, how are you?`, `@BotName how are you?`  |  Odpowiada pozytywnie tylko, gdy bot owner jest online.
`@BotName fire`  |  Tworzy ogień Unicode. Za pomocą cyfry na końcu można ustawić, ile razy ma powtórzyć ogień. Dozwolone wartości między 0 i 12 |  @Finn fire 2
`@BotName slm`  |  Pokazuje ostatnie rozmowy 
`@BotName ab`  |  Wpisuje 'abalabahaha'

### Hazard  
Komenda | Działanie | Sposób użycia
--------|-----------|--------------
`$draw`  |  Pokazuje losowe karty. |  $draw [x]
`$flip`  | Wykonuje rzut monetą. Możesz podać na końcu liczbę prób. |  `$flip` lub `$flip 3`
`$$$`  |  Pokazuje ile użytkownik ma PokeDolarów (do gry Pokemonów) | `$$$` lub `$$$ @AshKetchum50`
`$give`  |  Zabiera kilka pokedolarów i daje userowi.
`$award`  |  Dodaje pokedolary użytkownikowi **TYLKO WŁAŚCICIEL BOTA MOŻE WPISAĆ TĄ KOMENDĘ!** |  `$award 100 @AshKetchum50`
`$take`  |  Zabiera Pokedolary użytkownikowi. **TYLKO WŁAŚCICIEL BOTA MOŻE WPISAĆ TĄ KOMENDĘ!** 
`$leaderboard`, `$lb`  |  Pokazuje statystyki wszystkich pokemonów (użytkowników) na serwerze.

### Gry 
Komenda | Działanie | Sposób użycia
--------|-----------|--------------
`>poll`  |  Rozpoczyna głosowanie. Tylko osoba mająca uprawnienia może to robić. Pozostali swój głos muszą wysłać za pomocą prywatnej wiadomości do Finna. |  >poll Pytanie?;Odp1;Od2;O3
`>8ball`  |  Spytaj się Finna o różne rzeczy!
`>pollend` | Kończy głosowanie.	
### Muzyka  
Komenda | Działanie | Sposób użycia
--------|-----------|--------------
`!m q`  | Zaczyna puszczać muzykę. UWAGA! Musisz być na kanale głosowym aby komenda ta zadziałała! | !m q (link do muzyki)
`!m s`  | Przerywa graną piosenkę. (JUŻ WKRÓTCE TA LISTA ZOSTANIE UZUPEŁNIONA!)
### NSFW  
Komenda | Działanie | Sposób użycia
--------|-----------|--------------
`~hentai`  |  Pokazuje randomowe hentaii |  ~hentai yuri+kissing
`~danbooru`  |  Pokazuje randomowe hentaii z danbooru. |  ~danbooru yuri+kissing
`~e621`  |  Wyświetla losowy hentai ze strony e621 z podanymi tagami (opcjonalne). |  ~e621 yuri kissing
`~cp`  |  	Wyświetla losowy obrazek z dziecięcą pornografią. Kusi, prawda? :)
`~boobs`  |  Cycki!
`~butts`, `~ass`, `~butt`  |  Pośladki! 
### Pokegra
Komenda | Działanie | Sposób użycia
--------|-----------|--------------
`>attack`  |  Atakuje użytkownika. | >attack "nuzzle" @vistafan12
`>movelist`, `>ml`  |  Lista Ruchów którą możesz wybrać do atakowania przeciwnika.
`>heal`  |  Uzdrawiająca komenda. Trzeba mieć 1 pokedolar aby ją użyć.  | >heal @AshKetchum50
`>type`  |  Zobacz jaki użytkownik jest pokemonem. |  >type @AshKetchum50
`>settype`  |  Ustawia typ pokemona. Potrzeba dużo pokedolarów. |  >settype walczący

### Translator  
Komenda | Działanie | Sposób użycia
--------|-----------|--------------
`~translate`, `~trans`  |  Tłumaczy z>do |  ~trans en>fr Hello
`~translangs`  |  Wyświetla listę obsługiwanych języków w tłumaczu.	

### Autorskie komendy
Komenda | Działanie | Sposób użycia
--------|-----------|--------------
`pt`  |  Przeniesienie do np. innego kanału. | pt #placki
`chodztudomniebracie`  |  Walka z bratem. | chodztudomniebracie @vistafan12
`pikasiema`  |  Żart z "Siema xDDDDDDD" | pikasiema
`@BotName przezwij`, `<@!209230749725884417> przezwij`  | Wiadomo, hejt na ciebie. | @Finn przezwij
`@BotName pochwal`, `<@!209230749725884417> pochwal`  |  Wiadomo, pochwalenie. | @Finn  pochwal
`@BotName pogłaskaj`, `<@!209230749725884417> pogłaskaj`  |  Finn przesyła wesołego gifa. |  @Finn pogłaskaj
`@BotName smutek`, `<@!209230749725884417> smutek`  |  Finn wysyła smutnego gifa. | @Finn  smutek
`@BotName, jesteś żywy?`, `<@!209230749725884417>, jesteś żywy?`  |  Spytaj się, czy Finn żyje | @Finn, jesteś żywy?
`@BotName Siema xD`, `<@!209230749725884417> Siema xD`  |  Siema XDDDDDDDDDDDD | @Finn Siema xD
`-s inne`  |  Inne komendy. | -s inne
`-s`  |  Specjalna komenda | -s
`@BotName siema xD`, `<@!209230749725884417> siema xD`  |  Siema XDDDDDDDDDDDD | @Finn siema xD
`@BotName Kenex`, `<@!209230749725884417> Kenex`  |  Kto to Kenex? | @Finn Kenex
`@BotName jesteś tam?`, `<@!209230749725884417> jesteś tam?`  |  Sprawdź, czy Finn nie umarł. | @Finn jesteś tam?
`@BotName jesteś gdzieś indziej?`, `<@!209230749725884417> jesteś gdzieś indziej?`  |  Sprawdź, czy Finn jest gdzieś indziej! | @Finn jesteś gdzieś indziej?
`@BotName 69`, `<@!209230749725884417> 69`  |  ( ͡° ͜ʖ ͡°)@Finnon% 69
`.info`  |  Informacje o bocie, itp. | .info
`@BotName dziewczyna`, `<@!209230749725884417> dziewczyna`  |  Pokazuje obrazek dziewczyny. | @Finn dziewczyna
`-s teksty`  |  Losowy tekst od Kacpra3100. | -s teksty
