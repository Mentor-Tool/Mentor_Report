# Mentor_Report — Performance Dashboard

Hub delle dashboard Amazon Advertising gestite da Mentor, pubblicato via GitHub Pages.

## Struttura

| File | Contenuto |
| :--- | :--- |
| `index.html` | Landing page con i link ai clienti |
| `promopharma.html` | Dashboard performance Promopharma |
| `natui.html` | Dashboard performance Natui |

## URL pubblico

La landing è online su GitHub Pages (branch `main`). L'URL è indicato nelle impostazioni del repo → Pages.

## Come aggiornare una dashboard (team)

1. Sostituire il file HTML del cliente (es. `promopharma.html`) con la versione aggiornata, **mantenendo lo stesso nome**.
2. Commit e push sul branch `main`:
   ```bash
   git add .
   git commit -m "Aggiornamento dashboard <cliente> <mese>"
   git push
   ```
3. GitHub Pages ripubblica in automatico entro 1-2 minuti.

## Note

- I nomi file NON vanno cambiati: l'`index.html` li linka con path fissi.
- Repo pubblico: non inserire dati sensibili non condivisibili.
