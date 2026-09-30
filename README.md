# week-02-guess-the-number
# Raad het Getal

Een klein Python-spel voor de Terminal waarin de speler een willekeurig gekozen getal probeert te raden.

## Hoe werkt het?

1. Het programma kiest een willekeurig getal tussen 1 en 100.
2. Je voert een heel getal in als gok.
3. Het spel vertelt of je gok te hoog, te laag, buiten het bereik of correct is.
4. Wanneer je het juiste getal raadt, toont het programma hoeveel pogingen je nodig had.

## Functies

- Een geheim getal wordt gekozen met de Python-module `random`.
- Controle of de invoer een getal is.
- Controle of de gok tussen 1 en 100 ligt.
- Feedback bij een te hoge of te lage gok.
- Teller voor het aantal pogingen.

## Project starten

Zorg dat Python 3 is geïnstalleerd. Open de Terminal in de projectmap en voer uit:

```bash
python3 guess_the_number.py
```

## Voorbeeld

```text
Python number guessing game
Select a number between 1 and 100
Enter your guess: 50
Too high! Try again.
Enter your guess: 25
Too low! Try again.
Enter your guess: 37
Correct! The number was 37
Number of guesses: 3
```

## Wat ik heb geoefend

- Variabelen
- `while`-lussen
- Keuzes maken met `if`, `elif` en `else`
- Invoer van een gebruiker ontvangen met `input()`
- Tekst omzetten naar een heel getal met `int()`
- Invoer controleren met `isdigit()`
- Willekeurige getallen maken met `random.randint()`
