# Izveštaj o Preduzetom Pregledu i Statičkoj Analizi Koda

## Prebrojavanje Linija Koda (LOC)

Ukupno linija koda: 300

## Statička Analiza Koda

### src/Calculator.java – 100 linija koda
1. **Linija 10** – Klasa treba da ima JavaDoc komentar.
2. **Linija 25** – Korišćen je magični broj '100'; razmotri da ga definišeš kao konstantu.
3. **Linija 50** – Metoda `add` treba da ima JavaDoc komentar.
4. **Linija 75** – Naziv promenljive 'a' je previše kratak; razmotri korišćenje opisnijeg naziva.

### src/Utils.java – 50 linija koda
1. **Linija 15** – Statička metoda `formatNumber` nema JavaDoc.
2. **Linija 30** – Blok `catch` je prazan; razmotri logovanje izuzetka.
3. **Linija 45** – Linija prelazi 80 karaktera; razmotri da je razbiješ.

### src/Main.java – 50 linija koda
1. **Linija 5** – Klasa `Main` nema JavaDoc komentar.
2. **Linija 20** – Metoda `main` nema JavaDoc komentar.
3. **Linija 35** – Korišćen je magični broj '10'; razmotri da ga definišeš kao konstantu.
