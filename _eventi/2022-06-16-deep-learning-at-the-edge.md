---
title: "Deep Learning at the Edge"
excerpt: "Francesco Solera shares his professional experience on Deep Learning"
read_time: false
related: false
show_date: true
share: true
comments: false
author_profile: false
toc: true
tags:
  - Deep Learning
---

Allenare modelli è solo il primo passo che porta un progetto di DL al successo. 

É la parte che ci insegnano all'università e che leggiamo nei paper, ed è bellissima: risorse computazionali senza vincoli. Poi nel futuro del modello ci sono 3 strade: rimanere su un PC con una buona CPU/GPU, diventare un servizio cloud, oppure uscire nel mondo reale su dispositivi "embedded". Questo dipende dallo use case ma, in ambito aziendale, raramente si vuole consegnare i propri dati a terzi o installare grandi GPU e CPU costose sui propri prodotti. L'inferenza deve essere fatta il più vicino possibile a dove i dati sono raccolti - at the edge, appunto - e senza comprometterne accuracy e latenza. Nella prima parte del talk esploreremo il panorama hardware e gli step necessari per fare deploy at the edge, mostrando use case dall'esperienza di Deep Vision Consulting. 

La seconda parte, più teorica, introdurrà 3 tecniche per ottimizare l'inference su questi device: quantization, pruning, distillation.

**Francesco Solera**: Computer vision engineer and partner at Deep Vision Consulting

Ho ottenuto il mio PhD in Computer Engineering @ UniMoRe nel 2017 sotto la supervisione della prof. Rita Cucchiara e del prof. Simone Calderara. Ho pubblicato articoli in conferenze top-ranked e ho vinto due best papers award per i miei studi. Nel 2015 sono stato assistende di ricerca a Duke University e ho lavorato per prof. Tomasi. Attualmente lavoro presso Deep Vision consulting e il mio focus e nell'applicare tecniche di Deep Learning per risolvere problemi di Computer Vision. Di recente, sono stato menzionato come outstanding reviewer CVPR 19, 21 e ECCV 20.

## Video dell'evento

{% include video id="JROZ4ZWQb2k" provider="youtube" %}
