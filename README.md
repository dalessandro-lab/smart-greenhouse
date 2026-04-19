# Smart Greenhouse Turi 4.0 - Sito Web Interattivo

Planimetria interattiva della Smart Greenhouse Turi 4.0 con dettagli tecnici delle isole tematiche.

## 🚀 Come pubblicare su GitHub Pages

### Metodo 1: Upload tramite interfaccia web GitHub (PIÙ FACILE)

1. **Vai su GitHub** e accedi al tuo account
2. **Crea un nuovo repository**:
   - Clicca sul pulsante `+` in alto a destra → "New repository"
   - Nome repository: `smart-greenhouse` (o un nome a tua scelta)
   - Seleziona "Public"
   - ✅ Spunta "Add a README file"
   - Clicca "Create repository"

3. **Carica i file**:
   - Nel repository appena creato, clicca su "Add file" → "Upload files"
   - Trascina tutti i file di questa cartella (index.html + tutti i .svg)
   - Scrivi un messaggio di commit (es. "Aggiunta planimetria interattiva")
   - Clicca "Commit changes"

4. **Attiva GitHub Pages**:
   - Vai su "Settings" (ingranaggio in alto)
   - Nel menu laterale clicca su "Pages"
   - Sotto "Source", seleziona "main" branch
   - Clicca "Save"
   - Aspetta 1-2 minuti

5. **Visita il tuo sito**:
   - L'URL sarà: `https://tuousername.github.io/smart-greenhouse/`
   - Sostituisci `tuousername` con il tuo username GitHub
   - Sostituisci `smart-greenhouse` se hai usato un nome diverso

### Metodo 2: Via Git (per utenti esperti)

```bash
# 1. Inizializza il repository
git init

# 2. Aggiungi i file
git add .

# 3. Fai il primo commit
git commit -m "Prima versione planimetria Smart Greenhouse"

# 4. Collega al repository GitHub
git remote add origin https://github.com/tuousername/smart-greenhouse.git

# 5. Pusha i file
git branch -M main
git push -u origin main

# 6. Attiva GitHub Pages dalle impostazioni del repository
```

## 📁 File inclusi

- `index.html` - Pagina principale con planimetria e link
- `planimetria_smart_greenhouse_turi_4_0.svg` - Planimetria generale
- `dettaglio_isola_tradizionale_evoluta.svg` - Dettaglio isola tradizionale
- `dettaglio_isola_idroponica_nft.svg` - Dettaglio sistema idroponico
- `dettaglio_isola_vertical_farming.svg` - Dettaglio vertical farming
- `dettaglio_digital_twin_controllo.svg` - Dettaglio sistema di controllo
- `dettaglio_stazione_meteo_xfarm.svg` - Dettaglio stazione meteo

## 🎨 Caratteristiche

- ✅ Design moderno e responsive
- ✅ Animazioni fluide
- ✅ Compatibile con tutti i browser
- ✅ Mobile-friendly
- ✅ Caricamento veloce
- ✅ Completamente gratuito con GitHub Pages

## 🔧 Personalizzazione

Se vuoi modificare il sito:
1. Modifica il file `index.html`
2. Carica il file modificato su GitHub
3. Le modifiche saranno online in 1-2 minuti

## 📱 Test locale

Per testare il sito prima di caricarlo:
1. Apri il file `index.html` con un browser
2. Verifica che tutti i link funzionino
3. Controlla che i file SVG si visualizzino correttamente

## 💡 Suggerimenti

- Usa nomi repository semplici e senza spazi
- GitHub Pages è gratuito per repository pubblici
- Il sito si aggiorna automaticamente quando carichi nuovi file
- Puoi usare un dominio personalizzato (vedi docs GitHub Pages)

## 🆘 Problemi comuni

**Il sito non si vede?**
- Aspetta 2-3 minuti dopo l'attivazione di GitHub Pages
- Verifica che il repository sia pubblico
- Controlla che tutti i file siano nella root del repository

**I link non funzionano?**
- Assicurati che tutti i file .svg siano nella stessa cartella di index.html
- I nomi dei file sono case-sensitive (maiuscole/minuscole contano)

**Errore 404?**
- Controlla l'URL: deve essere `https://username.github.io/nome-repo/`
- Verifica che GitHub Pages sia attivato nelle Settings

## 📞 Supporto

Per problemi con GitHub Pages: https://docs.github.com/pages

---

Creato per Smart Greenhouse Turi 4.0
