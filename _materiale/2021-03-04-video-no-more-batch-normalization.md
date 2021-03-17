---
title: "Video - No more batch normalization?"
excerpt: "Video dell'evento batch normalization del 4 Marzo 2021"
read_time: false
related: false
show_date: true
share: true
comments: false
author_profile: false
tags:
  - community
  - video
---


Nel campo della Computer Vision sono sempre piu presenti proposte di modelli basati su varianti di deep residual networks per superare lo stato dell'arte nel riconoscimento di immagini. Nell'addestrare questi modelli è spesso utilizzata Batch Normalization, e la combinazione di queste due innovazioni architetturali hanno portato a risultati sempre migliori in termini di accuratezza, sia sui dataset di test che su quelli usati per addestramento del modello. Batch normalization è diventato un compenente fondamentale nell'attuale mondo del Deep Learning (DL), ma presenta alcuni svantaggi.


Recentemente sono state presentate da Google [DeepMind](https://deepmind.com/) le Normalizer-Free Networks (NFNets), una classe di Convolutional Neural Networks (CNNs) che permette di allenare modelli per il riconoscimento di immagini senza l'utilizzo di Batch Normalization raggiungendo ugualmente risultati allo stato dell'arte in termini di accuratezza su ImageNet. Questi risultati sono stati raggiunti tramite l'utilizzo di Adaptive Gradient Clipping (AGC) e cambiamenti sull'architettura della rete neurale stessa.


In questo talk tratteremo prima i vantaggi e gli svantaggi di Batch Normalization, per poi passare all'analisi delle nuove soluzioni proposte e delle possibili direzioni future che si prefigurano in questo campo.

## Video

Potete trovare le **slide** che sono state presentate al seguente [link](https://github.com/mlmodena/meetups/blob/main/2021-03-04-no-more-batch-normalization.pdf)


{% include video id="gf7LTPtkQoM" provider="youtube" %}

## I relatori

**Mattia Verasani** è ML Engineer in Tetra Pak ed è uno dei fondatori di ML Modena.


