# Progetti Arduino: LED e Semafori

Questa repository contiene una serie di semplici progetti realizzati con Arduino per imparare le basi dell'elettronica e della programmazione embedded.

## Contenuto
-  **Unico LED**
- **Semaforo semplice**
-  **Quattro semafori (incrocio)**
- **Semaforo con pulsante (attraversamento pedonale)**

## 1. Unico LE
### Descrizione
Accensione e spegnimento di un LED a intervalli regolari.

### Componenti
- 1 LED
- 1 Resistenza
- Arduino
- Breadboard e cavi

### Funzionamento
Il LED lampeggia con un intervallo definito tramite `delay()`.

## 2. Semaforo semplice
### Descrizione
Simulazione di un semaforo con tre LED:
- Verde
- Giallo
- Rosso

### Componenti
- 3 LED (verde, giallo, rosso)
- 3 Resistenze
- Arduino

### Funzionamento
Il ciclo del semaforo segue questa sequenza:
1. Verde → vai
2. Giallo → attenzione
3. Rosso → fermati


## 3. Quattro semafori (incrocio)
### Descrizione
Simulazione di un incrocio stradale con quattro semafori coordinati.

### Componenti
- 12 LED (4 semafori × 3 colori)
- 12 Resistenze
- Arduino

## Funzionamento
- Due direzioni opposte sono verdi contemporaneamente
- Le altre due restano rosse
- Il ciclo si alterna per gestire il traffico

## 4. Semaforo con pulsante
### Descrizione
Semaforo con richiesta di attraversamento pedonale tramite pulsante.

### Componenti
- 3 LED (semaforo auto)
- 1 Pulsante
- Resistenze
- Arduino

### Funzionamento
- Il semaforo resta verde per le auto
- Quando si preme il pulsante:
  - Il sistema attende
  - Poi passa a rosso per le auto
  - Consente l’attraversamento pedonale

## Obiettivi didattici
- Uso dei pin digitali
- Controllo dei LED
- Gestione dei tempi con `delay()`
- Lettura input da pulsante
- Logica di controllo sequenziale

## Come usare i progetti
1. Collega i componenti seguendo lo schema
2. Carica il codice su Arduino tramite IDE
3. Avvia il circuito
4. Osserva il comportamento

## Requisiti
- Arduino (UNO o compatibile)
- Arduino IDE
- Componenti elettronici base

## Note
Puoi modificare:
- I tempi dei semafori
- I pin utilizzati
- La logica di funzionamento
