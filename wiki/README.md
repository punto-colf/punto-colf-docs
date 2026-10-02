# wiki/

Contenuti della **Wiki pubblica di PuntoColf**, in italiano.

Questa cartella contiene i sorgenti Markdown delle pagine Wiki. Per pubblicarle sulla Wiki di
GitHub (repository `punto-colf-docs.wiki.git`), copia o sincronizza questi file nel repository
della Wiki:

```bash
git clone https://github.com/punto-colf/punto-colf-docs.wiki.git
cp wiki/*.md punto-colf-docs.wiki/
cd punto-colf-docs.wiki && git add -A && git commit -m "Aggiorna wiki" && git push
```

## Pagine

- `Home.md` — pagina iniziale.
- `_Sidebar.md` — menu laterale.
- `_Footer.md` — piè di pagina.
- `Guida-Datore-di-lavoro.md` — guida per i datori di lavoro.
- `Guida-Lavoratore.md` — guida per i lavoratori.
- `FAQ.md` — domande frequenti.
- `Glossario.md` — glossario dei termini.
- `Supporto.md` — supporto e contatti.

I nomi dei file corrispondono ai titoli delle pagine Wiki; i link tra pagine usano quei nomi
(senza estensione).
