---
title: "Train and deploy TensorFlow models in Go"
excerpt: "Paolo Galeone ci mostra come usare il framework Tensorflow per allenare e mettere in produzione i nostri modelli"
read_time: false
related: false
show_date: true
share: true
comments: false
author_profile: false
tags:
  - Tensorflow
  - Go
---

Lo step finale del machine learning workflow è il deploy del modello nell'ambiente di produzione. Questo ambiente è molto spesso completamente diverso da quello usato durante il training: risorse limitate, non disponibilità di linguaggi e framework.

TensorFlow, grazie al suo SavedModel, permette il deploy di un modello allenato su diverse "deployment platform". Un modello allenato in Python, può essere esportato ed usato in un browser, in una applicazione Java, in uno script Python e su ogni dispositivo in grado di eseguire programmi C.

TensorFlow, infatti, ha una C API che viene usata per generare language bindings - ed è qui che grazie alla sua FFI per C, fa il suo ingresso Go.

In questo talk saranno introdotti i Go bindings per TensorFlow, le loro limitazioni e come la libreria tfgo ne semplifica l'uso. Infinite, grazie alla flessibilità del formato SavedModel vedremo come poter fare incremental learning... in Go!

{% include video id="SI0J9JBrH-s" provider="youtube" %}

**Paolo Galeone** *{Tech\|ML} Lead @ Zuru Tech Italy.*
Da sempre appassionato di informatica, Paolo Galeone sviluppa software da oltre un decennio. Dopo una laurea magistrale in ingegneria informatica, si specializza facendo ricerca nel laboratorio di visione artificiale dell'Università di Bologna. In seguito, diventa team leader del gruppo di Machine Learning a Zuru Tech Italy dove svolge anche il ruolo di techical leader per l'intero progetto. Technical blogger ([https://pgaleone.eu/](https://pgaleone.eu/)), open source supporter ([https://github.com/galeone](https://github.com/galeone)), smanettone
