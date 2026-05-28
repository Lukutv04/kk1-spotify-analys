# KK1 – Spotify Songs: En dataanalys

**Kurs:** Artificiell Intelligens – programmering Python (MAI25MA)

## Om datasetet

Datasetet är *Spotify Songs* från TidyTuesday (2020-01-21). Det innehåller ~32 000 låtar hämtade via Spotifys publika API och inkluderar metadata (artist, album, genre) och automatiskt beräknade ljudfunktioner (danceability, energy, tempo, m.fl.).

Datasetet laddas ned automatiskt i notebooken – ingen manuell nedladdning behövs.

**Källa:** https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-01-21

## Struktur

```
notebook.ipynb    # KK1-notebooken med all analys
README.md         # Den här filen
```

## Hur notebooken körs

1. Se till att du har Python 3 med följande paket installerade:
   ```
    pip install -r requirements.txt
   ```
2. Öppna `notebook.ipynb` i Jupyter Lab eller Jupyter Notebook.
3. Kör alla celler uppifrån och ned (Kernel → Restart & Run All).

Notebooken laddar ned datasetet automatiskt från internet vid första körningen.
