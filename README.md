# 🇦🇺 Australian To-Do List

Questo progetto rappresenta una web app di una to-do list, per dei souvenir che vorrei mi portassero i miei genitori dal loro viaggio di ferie estive in Australia.

## ✨ Caratteristiche principali

- 📝 **Aggiunta di attività** – Campo input intuitivo con pulsante "Aggiungi"
- ✅ **Completamento attività** – Checkbox per segnare i task come fatti (testo barrato)
- ✏️ **Modifica attività** – Pulsante matita per cambiare il testo di un task
- 🗑️ **Eliminazione attività** – Rimozione definitiva con conferma
- 🌙 **Toggle iOS** – Switch stile iOS per passare dalla **light mode** alla **dark mode** (con emoji sole/luna)
- 💾 **Salvataggio automatico** – I dati vengono persistenti nel `localStorage` del browser
- 📱 **Completamente responsive** – Interfaccia ottimizzata per desktop, tablet e smartphone

## 🚀 Tecnologie utilizzate

| Tecnologia | Ruolo |
|------------|-------|
| HTML5      | Struttura semantica dell'app |
| CSS3       | Stili personalizzati, variabili CSS per i temi, layout Flex/Grid |
| JavaScript | Logica dell'applicazione, gestione del DOM, localStorage, toggle dark mode |

## 📸 Anteprima

> *L'app si presenta come una card centrale con un campo per aggiungere nuove attività, la lista delle cose da fare, un contatore delle attività rimanenti e un toggle per il tema.*

## 🛠️ Come usare il progetto

1. **Clona o scarica** il file `index.html` (l'intera applicazione è in un unico file).
2. Apri il file con qualsiasi browser moderno (Chrome, Firefox, Safari, Edge).
3. **Non è richiesto alcun server** – l'app funziona completamente lato client.
4. Inizia ad aggiungere le tue attività:
   - Scrivi un task nel campo "Aggiungi nuova attività..."
   - Premi il tasto "Aggiungi" o premi `Invio`
   - Spunta la checkbox per segnare un'attività come completata
   - Usa i pulsanti ✏️ (modifica) e 🗑️ (elimina) per gestire ogni voce

## 🧩 Dati di esempio iniziali

Alla prima apertura, l'app mostra automaticamente quattro attività:

- Foto fatta bene di un Koala su un Eucalipto
- Foto fatta bene di un canguro nel suo ambiente naturale
- Salsa piccante dall'amico chef di Giaela
- Boomerang aborigeno originale (o qualsiasi boomerang acquistato in Australia) – **deve avere solo 2 punte**

Puoi modificarle o cancellarle liberamente.

## 🎨 Personalizzazione temi

- **Light mode** (default) – sfondo chiaro, card bianca, contrasto morbido
- **Dark mode** – sfondo scuro, card blu notte, ideale per l'uso serale o per ridurre l'affaticamento visivo

Il tema scelto viene salvato nel browser e ripristinato automaticamente al prossimo accesso.

## 📦 Struttura del progetto

Il progetto è contenuto in un **singolo file HTML** (self-contained).  
Non sono richiesti file esterni, framework o librerie.  
All'interno del file trovi:

- `<style>` – Tutti gli stili CSS (con variabili per i due temi)
- `<script>` – Tutta la logica JavaScript (gestione task, eventi, localStorage)
- HTML – Struttura semantica e accessibile

## 📱 Compatibilità

| Browser | Versione minima supportata |
|---------|----------------------------|
| Chrome  | 60+ |
| Firefox | 55+ |
| Safari  | 12+ |
| Edge    | 79+ |
| iOS Safari | 12+ |
| Android Chrome | 80+ |

## Author

[Andrea De Vita](https://github.com/andreadevita99)

## License

All rights reserved. This project is provided for demonstration purposes only. No permission is granted to use, copy, modify, merge, publish, distribute, sublicense, or otherwise reproduce any part of this software without explicit written consent from the author. Unauthorized use, modification, or redistribution is strictly prohibited.
