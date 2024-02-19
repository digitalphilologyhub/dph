[![Get invited](https://slack.developers.italia.it/badge.svg)](https://slack.developers.italia.it/)

# I template HTML del modello per i siti web e i servizi digitali delle PA, modificati per la descrizione del Pilot "Digital Philology Hub"
 
## ⌨️ Il codice pronto all'uso

In questo repository è possibile trovare alcune pagine statiche esemplificative. È possibile visualizzare e scaricare il codice HTML/CSS e Javascript dei template, già pronto all’uso e validato in termini di accessibilità e conformità alle [Linee guida di design per i servizi web della PA](https://docs.italia.it/italia/design/lg-design-servizi-web/), e costruiti sulle fondamenta fornite dallo [UI Kit](https://github.com/italia/design-ui-kit) e dalla libreria [Bootstrap Italia](https://italia.github.io/bootstrap-italia/).

## 📖 Come usare i template

Per l'esecuzione del repository, è necessario avere installato una versione di node >= `14.18.0` o comunque non superiore alle `16.x.x`

Come _templating language_ è stato usato Handlebars, insieme a fogli di stile in SCSS e Javascript. Il progetto viene compilato tramite Webpack.

### Installazione e Sviluppo

Per iniziare, è necessario `utilizzare una versione di Node uguale o superiore a 18` e installare le dipendenze del progetto:

```node

npm i

```

In seguito, avvia il progetto in modalità sviluppo:

```node

npm run start

```

Infine, compila i templates generando la cartella "dist": 

```node

npm run build

```

## 🔧 Segnalazione bug e richieste di aiuto

Per segnalare un bug apri un issue qui su GitHub. Se invece vuoi discutere delle scelte fatte o qualcosa non ti è chiaro, puoi farlo su [Slack](https://slack.developers.italia.it/) o scrivere su [Forum Italia](https://forum.italia.it/c/design) di Designers Italia.
