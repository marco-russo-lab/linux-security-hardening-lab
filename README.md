# Linux Security & Hardening Lab

Primo laboratorio pratico realizzato su una VM Ubuntu in VirtualBox, con l'obiettivo di applicare e verificare alcune configurazioni di base per la sicurezza di un sistema Linux.

## Ambiente

- Ubuntu Linux
- Oracle VirtualBox
- Windows Host
- OpenSSH Server
- UFW Firewall

## Attività svolte

- Analisi di rete, porte e servizi attivi
- Installazione e configurazione di OpenSSH Server
- Connessione SSH da Windows a Ubuntu tramite Port Forwarding
- Configurazione dell'autenticazione tramite chiavi ED25519
- Disabilitazione dell'autenticazione SSH tramite password
- Configurazione del firewall UFW
- Test finali di connettività e verifica delle configurazioni

## Risultato

Al termine del laboratorio, l'accesso SSH è consentito tramite autenticazione a chiave e protetto da passphrase, mentre l'autenticazione tramite password è disabilitata.

UFW è attivo con policy `deny incoming`, consentendo esplicitamente il traffico SSH sulla porta TCP 22.

## Documentazione

- `report/` report completo del laboratorio
- `screenshots/`  screenshot delle configurazioni e dei test effettuati
