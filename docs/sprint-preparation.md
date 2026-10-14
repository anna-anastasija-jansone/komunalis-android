# K4 sprinta sagatavošana

## Sprinta mērķis

Izveidot strādājošu Komunālis Android lietotnes pamatplūsmu, kurā lietotājs var ievadīt kopīgu izdevumu, izvēlēties maksātāju un dalībniekus, pārbaudīt sadalījumu, saglabāt izdevumu un apskatīt rezultātu vēsturē.

## Sākotnējais backlog

Stundu novērtējumi un galīgais apjoms jāapstiprina plānošanas sapulcē atbilstoši reāli pieejamajam laikam. Ja kopējais novērtējums pārsniedz pieejamo laiku, zemākas prioritātes vienības tiek izņemtas no sprinta.

### 1. Android projekta pamats un navigācija

Akcepta kritēriji:

- Projekts atveras un kompilējas Android Studio.
- Lietotne startē emulatorā vai fiziskā Android ierīcē.
- No sākuma ekrāna var atvērt izdevuma pievienošanas ekrānu un atgriezties atpakaļ.

### 2. Izdevuma datu ievade un validācija

Akcepta kritēriji:

- Lietotājs var ievadīt izdevuma nosaukumu un summu eiro.
- Summa pieņem komatu vai punktu un tiek attēlota ar divām zīmēm aiz komata.
- Tukšs nosaukums, nulle vai nederīga summa parāda saprotamu kļūdas tekstu.
- Pēc kļūdas labošanas ievadītie dati netiek pazaudēti.

### 3. Maksātāja un dalībnieku izvēle

Akcepta kritēriji:

- Var izvēlēties vienu maksātāju no Annas, Līgas un Marka.
- Katru dalībnieku var iekļaut vai neiekļaut sadalījumā.
- Plūsmu nevar turpināt, ja nav izvēlēts neviens dalībnieks.
- Izvēle saglabājas, pārejot uz apstiprinājuma ekrānu un atpakaļ.

### 4. Vienāds summas sadalījums un apstiprinājums

Akcepta kritēriji:

- Apstiprinājuma ekrānā redzams nosaukums, kopējā summa, maksātājs un dalībnieki.
- Katram izvēlētajam dalībniekam redzama aprēķinātā daļa.
- Daļu summa centos precīzi sakrīt ar kopējo izdevuma summu.
- Noapaļošanas papildu cents netiek sistemātiski piešķirts vienai un tai pašai personai.

### 5. Izdevuma saglabāšana un vēsture

Akcepta kritēriji:

- Pēc apstiprināšanas izdevums parādās vēstures sarakstā.
- Vēstures rindā redzams nosaukums, summa, maksātājs un dalībnieku skaits.
- Vienas lietotnes sesijas laikā jauns izdevums nepārraksta iepriekšējos ierakstus.
- Tukšai vēsturei redzams skaidrs tukšais stāvoklis.

### 6. Bilances rezultāts un kvalitātes pārbaude

Akcepta kritēriji:

- Pēc izdevuma saglabāšanas bilance tiek pārrēķināta.
- Norēķinu teksts nepārprotami pasaka, kurš maksā kam un cik.
- Ir vismaz vienību testi vienāda sadalījuma un centu noapaļošanas loģikai.
- Pull request pārbaudē testi un linteris izpildās bez kļūdām.

## Prioritāte, ja laika nepietiek

Vienības 1–4 veido minimālo demonstrējamo plūsmu. Vienības 5 un 6 drīkst pārcelt uz nākamo sprintu tikai plānošanas sapulcē, nevis samazinot to akcepta kritērijus.

## Pabeigtības definīcijas priekšlikums

- Kods atrodas atsevišķā atzarā, un ir izveidots pull request.
- Izvēlētās backlog vienības atbilst visiem akcepta kritērijiem.
- Projekts kompilējas un strādā demonstrācijas ierīcē vai emulatorā.
- Vienību testi un linteris izpildās bez kļūdām.
- Repozitorijā nav noslēpumu, `.env` failu vai lokālu konfigurācijas datu.
- Koda apskates komentāri ir izskatīti pirms apvienošanas `main` atzarā.

## Sapulcē aizpildāmie lauki

- Sprinta datumi un nākamās sapulces laiks
- Reāli pieejamās stundas
- Katras vienības novērtējums stundās
- Galīgais sprintā iekļautais apjoms
- Abu komandas biedru vārdi
- Koda apskates un procesa pārbaudes uzdevumu sadale

