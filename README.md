# 🥗 Sistema Agenti Alimentazione & Meal Prep

Benvenuto nel sistema integrato di agenti per la salute, la nutrizione e la gestione intelligente della spesa!

Questo sistema combina tre agenti specializzati focalizzati su nutrizione scientifica, cucina salutare in batch cooking e ottimizzazione della spesa alimentare.

---

## 🤖 I Tre Agenti del Sistema

```
  +--------------------+       +------------------------------+       +------------------------------------+
  |    NUTRIZIONISTA   | ----> |   CHEF HEALTHY & MEAL PREP   | ----> | SPESA INTELLIGENTE & FOOD ECONOMY |
  | (Macro, BMR, TDEE) |       | (Ricette & Batch Cooking)    |       | (Lista Reparti & Lettura Etichette)|
  +--------------------+       +------------------------------+       +------------------------------------+
```

### 1. 🍎 Nutrizionista Clinico & Sportivo (`nutrizionista`)
* **Ruolo**: Definizione del fabbisogno calorico (BMR, TDEE), pianificazione dei macronutrienti (proteine, carboidrati, grassi, fibre) e gestione di diete specifiche (dimagrimento, ipertrofia, ricomposizione, celiachia, vegetariana/vegana, FODMAP, ecc.).
* **Focalizzazione**: Scienza della nutrizione, salute metaboliica e bilanciamento energetico.

### 2. 🍳 Chef Healthy & Meal Prep Specialist (`chef_healthy_meal_prep`)
* **Ruolo**: Trasformazione dei piani alimentari in ricette gustose, sane ed efficienti. Pianificazione delle sessioni di **Batch Cooking** (preparare i pasti per 3-7 giorni in 2-3 ore), con guida precisa alle tecniche di cottura e conservazione (frigo, vetro, sottovuoto, freezer).
* **Focalizzazione**: Gusto, efficienza in cucina, tecniche di conservazione e qualità organolettica.

### 3. 🛒 Consulente Spesa Intelligente (`spesa_intelligente`)
* **Ruolo**: Conversione dei menù e delle ricette in una lista della spesa divisa per reparto del supermercato, calcolo dei quantitativi grezzi da acquistare, lettura delle etichette (INCI alimentare), selezione di prodotti stagionali ed eliminazione degli sprechi (Zero Waste).
* **Focalizzazione**: Economia domestica, budget optimization, qualità delle materie prime e stagionalità.

---

## 🚀 Come Utilizzare gli Agenti in Antigravity

Gli agenti sono già registrati e pronti per essere invocati direttamente tramite il comando `invoke_subagent` o ponendo domande specifiche.

### Workflow Consigliato Passo-Passo:

1. **Passo 1 - Nutrizionista**:
   > *"Invocando l'agente nutrizionista, calcola il mio fabbisogno calorico e crea una ripartizione macro per un obiettivo di dimagrimento (1800 kcal, 130g proteine)."*

2. **Passo 2 - Chef Healthy & Meal Prep**:
   > *"Invocando l'agente chef_healthy_meal_prep, crea un ricettario di 5 giorni basato su questi macro e pianifica la sessione di batch cooking della domenica."*

3. **Passo 3 - Spesa Intelligente**:
   > *"Invocando l'agente spesa_intelligente, genera la lista della spesa per il supermercato divisa per reparto per acquistare tutti gli ingredienti necessari senza sprechi."*

---

## 📁 Struttura della Cartella

- [agenti/nutrizionista.md](agenti/nutrizionista.md) - Scheda completa del Nutrizionista
- [agenti/chef_healthy_meal_prep.md](agenti/chef_healthy_meal_prep.md) - Scheda completa dello Chef Meal Prep
- [agenti/spesa_intelligente.md](agenti/spesa_intelligente.md) - Scheda completa del Consulente Spesa Intelligente
