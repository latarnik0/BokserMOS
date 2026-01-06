# PROJEKT - BokserMOS
Projekt boksera z koła naukowego MOS.

# CEL
Celem jest wykonanie boksera który po uderzeniu będzie pokazywał wynik od 0 do 999.

# DZIAŁANIE
Użytkownik wpisuje swój nick wybierając pojedyncze litery za pomocą gałki potencjometru. Oprócz gałki dostępny jest przycisk "reset", "enter", "usuń znak". Po wciśnięciu enter bokser czeka 5 sekund wyświetlając jednocześnie komunikat aby się odsunąć. Po tym czasie następuje opuszczenie gruszki i oczekiwanie na uderzenie. Po uderzeniu (jeśli było wystarczająco mocne) gruszka się chowa i tam zostaje. Jeśli uderzenie nie było wystarczająco mocne, gruszka chowa się automatycznie po wyświetleniu wyniku. Na wyświetlaczu pokazywany jest wynik. 

Na razie, ze względu na skomplikowanie mechaniczne maszyny stojącej (budowa obudowy, ramy) proponuję zrobienie gruszki wiszącej z akcelerometrem i wyświetlaczem. W zadaniach do zrobienia w nawiasach będzie litera **(W)** - wisząca lub **(S)** - stojąca.

# WYKORZYSTANY SPRZĘT (dotychczas)
- ESP32-C3
- Akcelerometr MPU-6050
- Raspberry Pi Pico H (do LCD)
- Wyświetlacz LCD (20x4)
- Potencjometr liniowy
- Przyciski
- Przełącznik On/Off
- Inne: płytka stykowa, kable, przejściówka na potencjometr

# DODATKOWE INFORMACJE
- **Data rozpoczęcia:** październik 2025
- **Status:** w trakcie rozwoju
- **Ostatnia aktualizacja:** 06.01.2026

# DO ZROBIENIA
- Zrobić gruchę prowizorycznie (może potem kupi się profesjonalną). **(W) (S)**
- Zrobić czujnik siły uderzenia. Najlepiej tensometr/acelerometr bo piezo jest zbyt kruche. **(W) (S)**
- Sposób na montaż i umiejscowienie elektroniki. Grucha będzie wisieć ale elektronika musi być stabilna. **(W)**
- Zrobić mechanizm opuszczania gruchy. Ramie opuszczające musi być solidne żeby wytrzymało wielokrotne uderzenia. **(S)**
- Zrobić obudowę. Musi być dobrze dociążona żeby się nie przewróciła podczas uderzania. **(S)**
