---
title: "Warum Markdown?"
date: 2020-10-11T12:51:53+02:00
draft: false
---

![Markdownlogo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

Markdown ist eine Auszeichnungssprache, die bereits in Rohform leicht lesbar ist. Markdown ermöglicht leichte Einbindung von Dateien in Websites und eine schnelle Umwandlung in verschiedene Formate.

## Ausgangslage

- Ich habe Text und möchte diesen in Github etc. hochladen.
- Mein Text ist .pdf/.docx/.html/... und kann deswegen nicht bearbeitet/geteilt/gut dargestellt werden


## Markdownformatierung

[Editor mit Preview](https://dillinger.io/)  
[Anleitung vom genutzten Learn Theme](https://learn.netlify.app/en/cont/markdown/)  
[Anleitung von ionos.de](https://www.ionos.de/digitalguide/websites/web-entwicklung/markdown/)  

## Andere Formatierungen im Text

- Durch das Bearbeiten der config.toml Datei ist es möglich geworden HTML innerhalb der Markdowndatei sichtbar zu machen.
[Feature von Hugo dazu](https://gohugo.io/news/0.60.0-relnotes/)

- Shortcodes erlauben schnelles Einbinden verschiedster Medien in die Website, ohne den Text "hässlich zu machen"  
[Mögliche vordefinierte Shortcodes](https://gohugo.io/content-management/shortcodes/)  
Bsp.
  - Youtube
  - Twitter
  - iframes  
    -  Unser eigener Shortcut h5p ermöglich eine Einbindung von h5p!  
    Einbindung mit
```
    ((< h5p "link" "WeiteAlsZahl" "HöheAlsZahl" >))

    Nutze {{}} statt (()) !!
```
