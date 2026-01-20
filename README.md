# Progetto-JavaScript-di-Paolo-Andrea-Taranto

Progetto Counter JavaScript

# Counter Progressivo

Piccola applicazione web realizzata in **HTML, CSS e JavaScript** che implementa un **contatore interattivo** con animazione progressiva della dimensione del numero.

## 📌 Funzionalità

- ➕ Incremento del contatore
- ➖ Decremento del contatore
- 🔄 Reset del valore
- 🔍 Animazione progressiva:
  - il numero **aumenta di dimensione** quando cresce
  - il numero **diminuisce di dimensione** quando cala
- Limiti minimo e massimo per evitare dimensioni estreme

## 🛠️ Tecnologie utilizzate

- HTML5
- CSS3
- JavaScript


## ▶️ Come eseguire il progetto

1. Scarica o clona il repository
2. Apri il file `index.html` con un browser web
3. Usa i pulsanti:
   - `+` per aumentare il contatore
   - `-` per diminuirlo
   - `Reset` per riportarlo a zero

## ⚙️ Logica dell’animazione

- La dimensione del numero è controllata tramite `transform: scale()`
- Ogni incremento/decremento modifica la scala di un valore fisso (`SCALE_STEP`)
- La scala è limitata da:
  - `MIN_SCALE = 0.6`
  - `MAX_SCALE = 2.5`

## 🎯 Possibili estensioni

- Blocco del contatore a valori negativi
- Cambio colore dinamico del numero
- Effetto “bounce” o easing avanzato
- Versione mobile-first
- Conversione in framework (React, Vue)
## Link Canva
  https://www.canva.com/design/DAG-9FjrHIg/kF8LRIcleSDK9-JRLgjVaQ/edit?utm_content=DAG-9FjrHIg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
## 👤 Autore

  Paolo Andrea Taranto
## Scopo

  Progetto didattico per esercitarsi con JavaScript e manipolazione del DOM.
