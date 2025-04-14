---
title: "Interfaces para la economía"
date: 2023-10-27T16:33:54-06:00
omit_header_text: true
featured_image: ""
draft: false
---

interface Capitalizable
  comercializar()
  consumir()
  // no importa que no utilices ese artículo, cómpralo
  // no importa que este artículo contamine

Cocacola implements Capitalizable
  comercializar()

// Esta interfaz puede ayudar a hacer consciencia