# ls_ITA_territorio
LimeSurvey 3, 4 e 5 -Territorio Italiano con domande tipo array duale

AGGIORNAMENTO 30/04/2021: Modifiche allo script causate da aggiornamenti di LimeSurvey 3 e 5. Sostituire nello script le stringhe  "array-flexible-duel-scale" con il nuovo nome "array-flexible-dual-scale". Inseriti nuovi lss e lsq.

Domande con territorio italiano per versioni 3 e 4 e nelle lingue "it" (default) e "it-informale".
I file lsq sono domande che possono essere importate direttamente nelle survey. I file lss sono survey con le sole domande di cui sopra. Gli xslx contengono codici e descrizioni delle domande:
- LINGUA IT (default):
	- regioni_province_it.lsq: domanda array duale per la selezione combinata di Province italiane previa selezione della Regione. Per le codifiche vedere l'xlsx relativo. E' possibile modificare tutto in modifica domanda. Per aggiungere righe, andare in "Sottodomande". Per modificare le regioni/province, andare in "Opzioni di Risposta".
	- province_comuni_it.lsq: domanda array duale per la selezione combinata di Comuni italiani previa selezione della Provincia. Per le codifiche vedere l'xlsx relativo. La modifica della domanda può essere molto difficoltosa a causa del numero elevato delle opzioni di risposta (Comuni) che potrebbe rallentare o bloccare. Per verificare il funzionamento, aprire prima in preview senza modifica. Nella versione 3 è possibile modificare facilmente quasi tutto, ma per modificare le opzioni di risposta (Provincie e Comuni) , l'apertura del pannello di modifica potrebbe risultare impossibile (limite del max_input_vars). Nella versione 4 attuale risulta impossibile qualsiasi modifica della domanda. Effettuare le modifiche direttamente sul file lsq (formato xml) per modifiche in caso di impossibilità.
	- reg_prov_prov_com_it.lss: survey in lingua "it" con le due domande di cui sopra.

- LINGUA IT-INFORMALE:
	- regioni_province_it_informal.lsq: domanda array duale per la selezione combinata di Province italiane previa selezione della Regione. Per le codifiche vedere l'xlsx relativo. E' possibile modificare tutto in modifica domanda. Per aggiungere righe, andare in "Sottodomande". Per modificare le regioni/province, andare in "Opzioni di Risposta".
	- province_comuni_it_informal.lsq: domanda array duale per la selezione combinata di Comuni italiani previa selezione della Provincia. Per le codifiche vedere l'xlsx relativo. La modifica della domanda può essere molto difficoltosa a causa del numero elevato delle opzioni di risposta (Comuni) che potrebbe rallentare o bloccare. Per verificare il funzionamento, aprire prima in preview senza modifica. Nella versione 3 è possibile modificare facilmente quasi tutto, ma per modificare le opzioni di risposta (Provincie e Comuni) , l'apertura del pannello di modifica potrebbe risultare impossibile (limite del max_input_vars). Nella versione 4 attuale risulta impossibile qualsiasi modifica della domanda. Effettuare le modifiche direttamente sul file lsq (formato xml) per modifiche in caso di impossibilità.
	- reg_prov_prov_com_it_informal.lss: survey in lingua "it.informal" con le due domande di cui sopra.

- CODIFICHE:
	- LS_Regioni_Province.xlsx
	- LS_Province_Comuni.xlsx
	
