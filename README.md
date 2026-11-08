# Scopone

Scopone scientifico per imparare e giocare in 4 dal telefono.

- **Gioca con gli amici**: crei un tavolo, mandi il link, ognuno si siede. Non serve registrarsi.
- **Allenati**: partita contro il computer con consigli 💡.

Il tavolo vive sul telefono di chi lo crea: chi crea il tavolo deve tenere l'app aperta finché si gioca. I messaggi tra i telefoni passano da due broker MQTT pubblici (HiveMQ ed EMQX, via `wss` sulla porta 443), così il gioco funziona anche su 4G/5G e reti Wi-Fi dove la connessione diretta tra telefoni è bloccata. Se un telefono perde la linea, si ricollega da solo.

Per provarlo con un broker locale: `index.html?broker=ws://localhost:PORTA`.
