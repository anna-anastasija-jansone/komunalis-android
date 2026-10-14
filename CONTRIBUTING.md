# Darba kārtība

## Atzari

- `feature/<īss-nosaukums>` jaunai funkcionalitātei
- `fix/<īss-nosaukums>` kļūdu labojumiem
- `test/<īss-nosaukums>` testu papildinājumiem

Piemēri: `feature/expense-form`, `feature/equal-split`, `test/split-rounding`.

## Commit ziņojumi

Ziņojumam īsi jāpasaka, ko commits izdara. Izmanto darbības vārdu tagadnes formā.

Piemēri:

- `Add expense amount validation`
- `Preserve participant selection during navigation`
- `Test cent remainder rotation`

Neizmanto neskaidrus ziņojumus, piemēram, `fix`, `changes` vai `update`.

## Pull request

1. Izveido pull request no darba atzara uz `main`.
2. Apraksti saistīto backlog vienību un pārbaudes soļus.
3. Pārliecinies, ka testi un linteris izpildās.
4. Koda apskatītājs atstāj trīs konkrētus komentārus pie konkrētām rindām.
5. Izskati komentārus un tikai pēc tam apvieno izmaiņas.

## Noslēpumi un lokālie faili

Repozitorijā nedrīkst pievienot paroles, API atslēgas, `.env`, `local.properties` vai parakstīšanas atslēgu failus.

