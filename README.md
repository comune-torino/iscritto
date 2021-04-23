# Project Title
Soluzione per la presentazione e gestione delle domande di iscrizione ai nidi e alle scuole dell'infanzia

# Project Description
Soluzione software che gestisce la presentazione e gestione delle domande di iscrizione ai nidi e alle scuole dell'infanzia; 
Le principali funzionalità sono: 
- modulo front-end per l'iscrizione ai nidi e alle scuole dell'infanzia
- servizi di back-end che realizzano la logica di business di frontoffice cittadino per presentazione di una domanda 
- soluzione di back-office (presentation e business logic) che realizza funzionalità di istruttoria, graduatoria ed accettazione domande presentata da frontoffice 
- procedure batch per l'invio delle notifiche di ammissione posti nidi/scuole dell'infanzia e per la produzione delle graduatorie da pubblicare sul portale della Città di Torino
		  

# Getting Started
Il prodotto ISCRITTO è composto dalle seguenti componenti:
- [ISCRITTOFE](https://github.com/comune-torino/iscritto-iscrittofe) (modulo front-end per l'iscrizione ai nidi e alle scuole dell'infanzia)
- [ISCRITTOBOWEBAPP](https://github.com/comune-torino/iscritto-iscrittobowebapp) (soluzione di back-office che realizza funzionalità di istruttoria, graduatoria ed accettazione domande di iscrizione nidi/scuole dell'infanzia)
- [ISCRITTOBOSRV](https://github.com/comune-torino/iscritto-iscrittobosrv) (componente che espone servizi REST di back-end per il back-office di gestione domanda di iscrizione ai nidi/scuole dell'infanzia)
- [SERVISCRITTO](https://github.com/comune-torino/iscritto-serviscritto) (componente che espone servizi REST di business)
- [ISCRITTOFOSRV](https://github.com/comune-torino/iscritto-iscrittofosrv) (componente che espone servizi REST di back-end per il front-end di gestione domanda di iscrizione ai nidi/scuole dell'infanzia)
- [ISCRITTOJB](https://github.com/comune-torino/iscritto-iscrittojb) (componente batch a tecnologia java per le notifiche e report PDF)
- [ISCRITTODB](https://github.com/comune-torino/iscritto-iscrittodb) (componente che realizza il database applicativo del prodotto)

# Prerequisites
I prerequisiti per l'installazione della componente sono i seguenti:
## Software
- [JDK 8](https://www.apache.org)
- [Apache 2.4](https://www.apache.org)
- [RedHat JBoss 6.4 GA](https://developers.redhat.com)  
- [PostgreSQL 9.6](https://www.postgresql.org)  

- Tutte le librerie elencate nel BOM.csv devono essere accessibili per compilare il progetto. Le librerie sono pubblicate su http://repart.csi.it, ma per semplicità sono state incluse nella cartella lib/ di ogni singola componente, ad esclusione della libreria weblogic-client-3.0.0.jar che deve essere scaricata autonomamente dal sito di Oracle.

# Versioning
Per la gestione del codice sorgente viene utilizzata Git. Per la gestione del versioning si fa riferimento alla metodologia [Semantic Versioning](https://semver.org/) 

#Copyrights
(C) Copyright 2021 Città di Torino

# License
Questo software è distribuito con licenza EUPL-1.2
Consultare i file EUPL v1_2 IT-LICENSE.txt e EUPL v1_2 EN-LICENSE.txt per maggiorni dettagli.
