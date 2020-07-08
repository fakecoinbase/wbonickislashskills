Analiza została przeprowadzona na podstawie kilkunastu tysięcy plików json z danymi o przedsiębiorstwach w Polsce z okresu marca i kwietnia.
Hierarchiczny plan działania:

1. Pobranie plików json ze strony KRS
2. Napisanie skryptu do analizy plików json
3. Stworzenie bazy danych dotyczącej kodów PKD
4. Końcowa analiza i statystyki

*.json - pliki json z danymi o przedsiębiorstwach (jedno przedsiębiorstwo - jeden plik, tutaj zostały załączone dwa przykładowe)
analiza_csv.ipynb - notebook wczytujący pliki .csv z danymi o przedsiębiorstwach i analizujący je
kody.ipynb - notebook pobierający ze strony internetowej dane o kodach PKD (symbol i objaśnienie) i zapisuący je w formacie .csv
skrypt_do_plikow_json.ipynb - skryp analizujący pliki json i zapisujący wyniki w formacie .csv (w nim można przeanalizować przykładowe pliki json)
calosc_summary.xlsx - excel z ostatecznymi danymi (3 zakładki, w każdej podsumowanie ilości branż w likwidacji, upadłości i zawieszeniu)
PKD.csv - plik z kodami PKD
likwidacje,upadlosci,zawieszenia.csv - dane o przedsiębiorstwach
