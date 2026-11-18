# Okienko „nowa wersja” w Bloombox na telefonie

Gra na telefonie (z internetem) raz przy starcie czyta plik `version.json` z tego repozytorium.

```
{"latest_code": 18, "latest_name": "0.18", "required_code": 0, "message": ""}
```

- `latest_code`: numer (version code) najnowszej wersji, która JUŻ jest w Google Play. Gdy jest wyższy niż w grze gracza, gra pokazuje okienko „Update / Later”.
- `latest_name`: nazwa tej wersji, np. "0.19".
- `required_code`: gdy gra gracza ma niższy numer niż ten, okienko jest OBOWIĄZKOWE (nie ma „Later”, trzeba zaktualizować). `0` = nigdy nie obowiązkowa.
- `message`: krótki tekst w okienku (po angielsku), może być pusty.

Jak zmienić: otwórz `version.json`, kliknij ołówek (Edit), zmień liczby, kliknij „Commit changes”.
Zmieniaj `latest_code` dopiero wtedy, gdy nowa wersja jest już dostępna w Google Play.
