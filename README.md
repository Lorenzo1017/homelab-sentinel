# homelab-sentinel

Osservatore esterno per un homelab domestico: ogni 10 minuti legge un "battito di vita"
pubblicato via DNS TXT dal server di casa e avvisa su Telegram se smette di aggiornarsi
(blackout, router o linea giu') e quando torna.

Configurazione tramite segreti del repository: `HB_NAME`, `TG_BOT_TOKEN`, `TG_CHAT_ID`.
