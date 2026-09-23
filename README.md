<p align="center">
  <img src="icon.png" width="180" alt="PizzaLab Icon" />
</p>

<h1 align="center">PizzaLab</h1>

<p align="center">
  <strong>Calcolatore scientifico per impasti pizza</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-iOS%2018%2B-007AFF?logo=apple&logoColor=white" alt="Platform" />
  <img src="https://img.shields.io/badge/swift-6.2-F05138?logo=swift&logoColor=white" alt="Swift 6.2" />
  <img src="https://img.shields.io/badge/SwiftUI-blue?logo=swift&logoColor=white" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/SwiftData-34C759" alt="SwiftData" />
  <img src="https://img.shields.io/badge/Xcode-16%2B-147EFB?logo=xcode&logoColor=white" alt="Xcode" />
  <img src="https://img.shields.io/badge/price-free-brightgreen" alt="Free" />
  <img src="https://img.shields.io/badge/offline-100%25-orange" alt="Offline" />
  <img src="https://img.shields.io/badge/language-italiano-green" alt="Italiano" />
  <img src="https://img.shields.io/badge/privacy-no%20data%20collected-blueviolet" alt="Privacy" />
  <img src="https://img.shields.io/badge/AVPN-2024-red" alt="AVPN" />
  <img src="https://img.shields.io/badge/APITER-disciplinare-red" alt="APITER" />
  <img src="https://img.shields.io/badge/version-2.0.0-lightgrey" alt="Version" />
</p>

<p align="center">
  <a href="https://apps.apple.com/us/app/pizzalab-calcolo-impasti/id6762013087">
    <img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/it-it" alt="Scarica su App Store" height="50" />
  </a>
</p>

---

## Descrizione

PizzaLab e' un'app iOS gratuita per il **calcolo scientifico degli ingredienti** per impasti pizza. Calcola farina, acqua, sale, lievito e temperatura dell'acqua in base ai parametri scelti, e genera un procedimento dettagliato passo-passo.

I parametri sono allineati ai disciplinari ufficiali **AVPN** (Associazione Verace Pizza Napoletana) e **APITER** (Associazione Pizza in Teglia e Romana).

## Ricette

### Pizze
- **Pizza Napoletana Verace** — Disciplinare AVPN 2024
- **Pizza Contemporanea** — Lunga maturazione
- **Pizza in Teglia** — Disciplinare APITER
- **Pizza Pala Romana** — Disciplinare APITER
- **Schiacciata Toscana** — Ricca di olio EVO
- **Pizza Fritta Napoletana** — Disciplinare AVPN

### Altre Ricette Tradizionali
- **Casatiello Napoletano** — Calcolo automatico in base alle dimensioni del ruoto, procedimento completo in 7 fasi

## Funzionalita'

### Calcolo
- Wizard guidato a 4 step
- Metodo diretto, indiretto con **biga** e indiretto con **poolish** (lievito secondo la tabella Giorilli)
- Selezione fermentazione: solo temperatura ambiente o frigo + ambiente
- Selezione tipo impastatrice con delta temperatura automatico
- Indicatori di conformita' ai disciplinari
- Supporto unita' metriche e imperiali

### Timer di lievitazione
- **Timer a conferma**: a fine fase il timer si ferma e attende la tua conferma prima di avviare la fase successiva; promemoria se non confermi
- **Live Activity interattiva** su Lock Screen e Dynamic Island: Pausa, Riprendi e "Avvia prossima fase" senza aprire l'app
- **Sveglia a fine fase (iOS 26.1+)**: con AlarmKit suona come una sveglia di sistema anche in silenzioso o Full Immersion
- **Comandi Siri e Comandi Rapidi**: "Avvia la prossima fase in PizzaLab", "Metti in pausa il timer di PizzaLab", "Quanto manca in PizzaLab", "Annulla il timer di PizzaLab"
- Notifiche locali con pre-avviso 10 minuti prima della scadenza di ogni fase

### Pianifica l'infornata
- Scegli data e ora in cui vuoi infornare: l'app calcola a ritroso quando impastare, mettere in frigo e stagliare, tenendo conto di riposi e pieghe
- Promemoria 15 minuti prima e all'ora di iniziare

### Procedimento e ricette
- Procedimento dettagliato con checkbox interattive; lo schermo resta acceso mentre lo segui
- Salvataggio ricette personalizzate
- Esportazione PDF professionale e condivisione come testo
- **Guida farine** e **Glossario termini** in Impostazioni

### Lingue e accessibilita'
- Italiano e **inglese** (segue la lingua di iOS): i termini tecnici restano in italiano con la spiegazione accanto, es. "puntata (bulk fermentation)"
- **VoiceOver**, Dynamic Type e Riduci movimento, verificati con l'audit di accessibilita' di Apple
- Interfaccia Liquid Glass su iOS 26
- Modalita' chiara e scura, haptic feedback

### Sempre
- 100% offline: nessun account, nessuna pubblicita', nessuna raccolta dati

## Contatti

Per supporto, segnalazioni o suggerimenti: [Issues](https://github.com/dindonio/pizzalab-release/issues)

## Privacy

La [Privacy Policy](PRIVACY.md) e' disponibile in questo repository.

---

<p align="center">
  <em>La scienza al servizio della pizza</em>
</p>
