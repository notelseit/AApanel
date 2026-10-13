# aaPanel — traduzioni italiane frontend revisionate

Sorgenti: gli archivi en.tar.gz e it.tar.gz allegati dall’utente il 13 ottobre 2026.

File confrontati: 27. Voci inglesi confrontate: 9225. Voci italiane corrette: 1512.

## Contenuto

- it/: i 27 file JSON da usare al posto dei corrispondenti file italiani.
- modifiche.csv: percorso della voce, riferimento inglese, vecchio testo e testo corretto.
- validation.json: risultati dei controlli e hash SHA-256.

## Correzioni

- Tradotte le sezioni rimaste in inglese: preferenze del pannello, Docker, sicurezza, Git, regole Nginx, WAF e WordPress.
- Corrette etichette di stato, pulsanti e messaggi amministrativi con significato errato o poco chiaro.
- Uniformati log e download. I verbi “registra” e “scarica” e i record DNS sono mantenuti quando appropriati.
- Ripristinati quattro segnaposto danneggiati in index.json, la parentesi di chiusura in public.json e le alternative singolare/plurale in home.json.
- Ripristinati nomi di file, percorsi, opzioni ed esempi tecnici alterati, inclusi package.json, redis_cache, bt_mongodb, JAVA_HOME, HOSTNAME, defaults, limit_except, limit_rate e regex di URL.
- Mantenute le 14 voci aggiuntive del file italiano file.json senza eliminarle.

## Controlli

JSON validi; nessuna chiave inglese mancante; struttura e chiavi italiane conservate; segnaposto e tag HTML coerenti con l’inglese; numero di fine riga e alternative di pluralizzazione coerenti; URL del riferimento inglese preservati. Tutti i file inclusi nello ZIP sono stati riletti e l’archivio è stato verificato.

Il controllo strutturale copre tutte le 9.225 voci inglesi. La revisione linguistica è mirata alle parti rimaste in inglese, agli errori rilevati e alla terminologia tecnica: non equivale a una certificazione manuale frase per frase delle oltre 9.000 voci. Le 14 voci italiane senza corrispondenza inglese sono conservate e non hanno potuto essere confrontate con questo riferimento.

Nessun test è stato eseguito nell’interfaccia aaPanel. Prima di applicare i file, conserva il tuo archivio italiano originale e verifica in prova login, menu, operazioni sui file, SSL, database, Docker e WAF.

Nessun file è stato caricato su GitHub e nessun server è stato modificato.

## Riepilogo per file

| File | Voci corrette | Voci italiane |
|---|---:|---:|
| account.json | 41 | 159 |
| component.json | 30 | 130 |
| config.json | 131 | 655 |
| crontab.json | 27 | 221 |
| database.json | 27 | 268 |
| docker.json | 160 | 786 |
| file.json | 69 | 701 |
| ftp.json | 24 | 114 |
| home.json | 56 | 651 |
| index.json | 58 | 904 |
| layout.json | 38 | 130 |
| login.json | 12 | 38 |
| logs.json | 22 | 35 |
| mail.json | 40 | 493 |
| monitor.json | 15 | 35 |
| password.json | 4 | 9 |
| plugin.json | 14 | 81 |
| public.json | 59 | 120 |
| security.json | 278 | 805 |
| site-node.json | 11 | 259 |
| site.json | 217 | 1018 |
| soft.json | 12 | 73 |
| ssl.json | 11 | 174 |
| term.json | 4 | 27 |
| utils.json | 0 | 2 |
| waf.json | 94 | 1079 |
| wp.json | 58 | 272 |
