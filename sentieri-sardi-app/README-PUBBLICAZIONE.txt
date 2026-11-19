SENTIERI SARDI 2026 - APP DA CONDIVIDERE

Questa cartella è l'app completa. Per renderla raggiungibile dagli amici basta metterla su un hosting gratuito.

OPZIONE A - Netlify Drop (la più semplice, nessuna installazione)
1. Vai su https://app.netlify.com/drop (crea un account gratuito se richiesto).
2. Trascina l'intera cartella (o il file sentieri-sardi-app.zip decompresso) nella pagina.
3. Dopo pochi secondi ottieni un indirizzo del tipo https://nome-casuale.netlify.app
4. Puoi cambiare il nome in Site settings > Change site name (es. sentieri-sardi).
5. Manda l'indirizzo agli amici.

OPZIONE B - GitHub Pages
1. Crea un repository pubblico su GitHub e carica tutti i file di questa cartella.
2. Settings > Pages > Branch: main, cartella /root > Save.
3. L'indirizzo sarà https://tuonome.github.io/nome-repository/

COME SI INSTALLA SUL TELEFONO (per te e per gli amici)
Android (Chrome): apri l'indirizzo, tocca i tre puntini > "Installa app" oppure "Aggiungi a schermata Home".
iPhone (Safari): tocca Condividi > "Aggiungi alla schermata Home".

COME AGGIORNARE I CONTENUTI (solo tu)
- extra.json: foto/video ed elenco gare 2027. Si apre con qualsiasi editor di testo.
  Le date delle gare 2026 arrivano dal file Excel (cella B2/C2 di ogni foglio gara), non da qui.
  Esempio di foto/video (dentro "media": [ ]):
    {"ev":"Marganai","kind":"Foto","title":"Album Marganai 2026","url":"https://..."}
  "ev" deve essere uno di: Miniere, Marganai, NoraTrail, Limbara, Villacidro, Sardinia T, Pattada,
  Castiadas, CapoM, Sennori, Benedett, Oliena, Castelsardo, Luna, Cuccure, Cervo. "kind" è "Foto" oppure "Video".
- dati.json: risultati e classifiche. Non si modifica a mano: quando hai un nuovo Excel mandamelo e ti rigenero il file.
Dopo ogni modifica ricarica la cartella sull'hosting (su Netlify: Deploys > trascina di nuovo la cartella).
Gli utenti vedono l'aggiornamento alla seconda apertura dell'app.
