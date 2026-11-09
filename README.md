# Enterprise Network Simulation (Cisco Packet Tracer)

Simulazione di un'infrastruttura di rete aziendale configurata e testata tramite **Cisco Packet Tracer**. Il progetto implementa la segmentazione della rete tramite switch multipli e la configurazione dei principali servizi di rete (DHCP, DNS e HTTP).

## 🛠 Architettura e Servizi Configurati
* **Topologia di Rete:** Infrastruttura basata su switch multipli connessi per la distribuzione del traffico ai dispositivi finali (Laptop).
* **DHCP Server:** Configurato per l'assegnazione dinamica degli indirizzi IP ai client della rete locale all'interno di un pool dedicato.
* **DNS Server:** Gestione della risoluzione dei nomi a dominio interni (es. `epicode.internal`).
* **HTTP Server:** Hosting di una pagina web di test interna accessibile dai client della LAN.

## ⚙️ Risoluzione dei Problemi (Troubleshooting)
Durante la fase di configurazione, sono stati risolti i problemi relativi alla mancata assegnazione degli indirizzi IP tramite DHCP (gestione degli errori APIPA) e verificata la corretta connettività end-to-end tra i server e i terminali.

---
*Nota: Progetto sviluppato a scopo didattico per l'approfondimento dei protocolli di rete, del routing e dei servizi di infrastruttura.*
