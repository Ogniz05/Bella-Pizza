# 🌮 Los Cerignola

<p align="center">
  <img src="./assets/logo.png" alt="Los Cerignola Logo" width="180" />
</p>

**Los Cerignola** è un’app sviluppata con **React Native (Expo)** che permette di esplorare in modo intuitivo i menù disponibili e visualizzare i prodotti offerti da una pizzeria.

---

## 🎨 Identità Visiva

### 🌈 Palette Colori

| Ruolo | Colore | Codice |
|:------|:--------|:-------|
| **Primario** | 🟡 Giallo Solare | `#FFD60A` |
| **Secondario** | 🟨 Giallo Oro | `#FFC300` |
| **Accento** | 🔵 Blu Cerignola | `#004AAD` |
| **Sfondo Chiaro** | ⚪ Crema | `#FFF7E0` |
| **Testo / Contrasto** | ⚫ Blu Notte | `#001D3D` |

<p align="center">
  <img src="https://dummyimage.com/600x80/fff/000&text=+ +++++++++++++++" alt="color separator" />
</p>

> 💡 Il **giallo** richiama il calore e la bontà della pizza,  
> mentre il **blu** rappresenta fiducia e professionalità — perfetto equilibrio per un brand accogliente ma moderno.

---

## 🐔 Mascotte — “Cerigno”

<p align="center">
  <img src="./assets/mascotte.png" alt="Cerigno Mascotte" width="180" />
</p>

**Cerigno** è la mascotte ufficiale di *Los Cerignola*:  
un simpatico **pollo pizzaiolo** con cappello da chef, sempre pronto a sfornare pizze perfette! 🍕🔥  
La mascotte incarna i valori del brand: **energia**, **calore**, **artigianalità** e **ospitalità**.

---

## 🎯 Obiettivo

L’obiettivo principale del progetto è creare un’app **semplice e funzionale** che consenta all’utente di:

- 🍽️ Navigare tra i diversi menù  
- 👀 Visualizzare i prodotti disponibili  
- 🔐 Gestire la propria sessione in modo sicuro e fluido  

---

## ⚙️ Funzionalità principali

### 🔐 Flusso di Autenticazione
Schermata di login per proteggere l’accesso all’area principale dell’app.

### 📚 Navigazione a Stack
Gestione della navigazione gerarchica tra le schermate (es. lista prodotti → dettaglio prodotto).

### 📱 Navigazione a Schede (Tabs)
Una comoda **Bottom Tab Bar** per muoversi tra le sezioni principali: **Home**, **Ordini** e **Profilo**.

### 🔄 Gestione della Sessione
Utilizzo del **reset dello stack di navigazione** per garantire un’esperienza di login/logout senza interruzioni.

### 🛒 Gestione degli Acquisti
Possibilità di acquisto tramite **carrello interattivo**.

### 📍 Gestione della Posizione
Visualizzazione sulla mappa dei **punti vendita più vicini** al cliente.

---

## 📋 Casi d’Uso Principali

### 1️⃣ Autenticazione
Il cliente accede all’app tramite **login**.  
- Senza autenticazione non può inserire i prodotti nel carrello.  
- Alternative: recupero password o messaggio di errore se credenziali errate.

### 2️⃣ Navigazione tra le schermate
Il cliente naviga tra le sezioni dell’app tramite la **Bottom Tab Bar** o la **navigazione a stack**.  
- Alternativa: l’utente può tornare alla pagina principale tramite lo stack navigation.

### 3️⃣ Visualizzazione menù e prodotti
Il cliente esplora i menù disponibili e visualizza i dettagli dei prodotti.  
- Estensione: possibilità di **filtrare i prodotti** o **cercare per nome**.

### 4️⃣ Logout / Gestione sessione
L’utente può uscire dall’app.  
- L’app effettua il **reset dello stack di navigazione** per proteggere la sessione.

---

