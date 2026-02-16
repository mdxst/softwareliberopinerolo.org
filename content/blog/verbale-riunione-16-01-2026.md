---
title: "Riunione SLiP 16 gennaio 2026"
author: "Mirko Di Stefano"
date: "2026-01-16"
---

Ciao ragazzi,

vi scrivo un resoconto della riunione di ieri, a cui abbiamo partecipato in "pochi ma buoni" (eravamo in cinque a fine serata).

Abbiamo affrontato i temi Mailing List & Sito Web Slip, ognuno con le sue proposte, e collaborando per giungere a una soluzione.

(Vi ricordo che la mailing list, nella sua forma attuale, chiuderà i battenti a fine anno, e dobbiamo quindi adoperarci per trovare un rimpiazzo.)

Proposte:

- mailing list fornita da ILS (quota associativa 25 euro l'anno) -
  vantaggi: porterebbe più visibilità a Slip in quanto diventeremmo
  parte di un'associazione più grande
- piccola VPS, anche gratuita, come Oracle Cloud (dagli 0 ai 60 euro
  l'anno, se scegliamo invece un provider a pagamento) - vantaggi:
  possiamo adoperarci per averla gratis [da verificare
  limitazioni], possiamo spostare semplicemente la mostra mailing
  list esistente --> se adottiamo quest'ultima, esiste
  l'alternativa Lemmy, ovvero un nostro piccolo sito stile Forum
  (senza categorie separate però)/stule "Reddit", che si potrebbe
  eventualmente sostituire alla mailing list tradizionale (Lemmy è
  libero).

Abbiamo poi discusso e trovato accordo sulla forma che dovrà assumere
il sito, partendo dalla struttura della schermata Principale, che
dovrà avere titolo "Software Libero Pinerolo", un carosello con belle
immagini (2-3, magari di eventi come Coder Dojo, Linux Day quando li
organizzeremo).

Proseguendo, il sito dovrà presentare le pagine:

- chi siamo (breve descrizione di Slip e della nostra storia, di cosa
  facciamo)
- archivio mailing list copia-incollato (già generato)
- calendario eventi (passati e futuri, possiamo utilizzare un widget
  già pronto, ho proposto il sito murena.io che è gratis) - deve
  essere visibile da tutti, ma modificabile solo da noi soci
- blog (eventualmente collegato a calendario, quindi ogni evento
  diventa automaticamente un blog post?)

Inoltre, in fondo a ogni pagina, è stato deciso di mettere le tre
icone di mailing list, gruppo Telegram e gruppo Signal, oltre che
classiche scritte di copyright & cod. fiscale.

Abbiamo dibattuto sulla necessità di utilizzare Wordpress o no.
L'esito del dibattito è stato: proviamo Hugo - semplice, statico
(alla fine ci serve un semplice blog+calendario, fattibilissimo con
Hugo+JavaScript) - se non ci troviamo bene, facciamo Rollback a
Wordpress+tema ufficiale  (più sicuro).

I temi Hugo che abbiamo trovato sono: [Doks](https://themes.gohugo.io/themes/doks), [Paper](https://themes.gohugo.io/themes/hugo-paper), e **[Mana](https://themes.gohugo.io/themes/hugo-mana-theme) P.S. 16/02: Preferito per ora, in testing**.

Qualunque soluzione adotteremo, dovrà esserci la possibilità di
inviare mail a un indirizzo del sito per trasformarla automaticamente
in un blog post (che poi dobbiamo approvare, onde evitare
vandalismo).

Abbiamo infine discusso la possibilità di sincronizzare mailing
list/Signal/Telegram tramite automatismi. La proposta è stata
contestata per via del troppo caos che genererebbe, ma è stato
trovato un consenso sul collegare Telegram e Signal in qualche modo
(bot?).

Ringrazio tanto Claudio per avere preso appunti durante la serata,
col suo ThinkPad!!!

Ringrazio tutti i presenti per la compagnia e per l'entusiasmo
portato, come sempre.

Una buona serata a tutti,

_Mirko_.
