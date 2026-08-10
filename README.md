# Tenuta Lunaria — Idea Vault

Questa è la base pronta per trasformare il prototipo in una vera app installabile.

## Cosa è già pronto
- nome: Tenuta Lunaria
- estetica lavanda
- archivio idee
- categorie: cosmetici, profumi, bagno, coltivazione, laboratorio, costi, bandi, branding
- ricerca
- stati delle idee
- PWA installabile dal browser
- struttura Capacitor per creare un'app Android

## Condivisione reale tra Arianna e Alessandro
Il prototipo attuale salva i dati localmente. Per la sincronizzazione tra due telefoni serve collegarlo a un database online (Firebase/Supabase).
Il progetto è volutamente predisposto per questo passaggio, ma non contiene credenziali o chiavi private.

## Pubblicazione sul Play Store
Per arrivare al Play Store bisogna:
1. collegare il database/autenticazione;
2. generare la build Android firmata;
3. creare l'account sviluppatore Google Play;
4. caricare la build e completare la scheda dell'app.

In alternativa, la PWA può essere installata direttamente dal browser come app senza passare dal Play Store.
