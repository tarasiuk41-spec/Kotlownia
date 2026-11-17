# 🔥 Kotłownia – Asystent Spalania Ekogroszku

Lekka aplikacja webowa (SPA / PWA) działająca lokalnie w przeglądarce, stworzona do kontroli zapasu opału, analizy dobowego zużycia ekogroszku oraz korelacji spalania z temperaturą zewnętrzną.

## ✨ Główne funkcje

- **Magazyn i Finanse (Worki / kg / PLN):** Bieżący podgląd stanu opału w workach, kilogramach oraz przeliczeniu na złotówki.
- **Szybki Zasyp:** Rejestracja załadunku jednym kliknięciem (`+1`, `+2`, `+3`, `+4` worki) lub wpisanie dowolnej wartości.
- **Model obliczeń „zasyp zasila okres do kolejnego zasypu”:** Ilość wsypanego opału dzielona jest przez dokładny czas do kolejnego załadunku, co precyzyjnie oddaje spalanie przy zasypywaniu zasobnika do pełna.
- **Prognoza zapasów:** Wyliczanie szacowanej liczby dni oraz dokładnej daty wyczerpania opału na podstawie średniego spalania.
- **Pogoda na żywo i wykresy:** Automatyczne pobieranie temperatury z darmowego API **Open-Meteo** i zestawianie jej ze zużyciem opału na wykresach (Chart.js).
- **Dziennik nastaw sterownika:** Baza sprawdzonych parametrów podawania, nadmuchu i temperatury kotła.
- **Pełny Eksport / Import Excel (`.xlsx`):** Kopia zapasowa i analiza danych w arkuszu kalkulacyjnym dzięki bibliotece SheetJS.

## 🚀 Uruchomienie na GitHub Pages

1. Wrzuć wszystkie pliki z archiwum do swojego repozytorium na GitHubie (`main`).
2. Wejdź w **Settings → Pages** i jako źródło wybierz gałąź `main` oraz folder `/ (root)`.
3. Po chwili aplikacja będzie dostępna pod adresem `https://TWOJ_LOGIN.github.io/NAZWA_REPOZYTORIUM/`.
