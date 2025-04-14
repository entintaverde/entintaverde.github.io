---
author: "Damian Flores"
title: "Cultura y Sistemas Operativos"
description: "ser y sistemas operativos"
date: 2024-06-21T22:55:44-06:00
omit_header_text: true
featured_image: ""
draft: false
---

Si los individuos fueramos computadoras, entonces la cultura sería nuestro sistema operativo. Un sistema operativo define como usar los recursos de una computadora al mismo tiempo que puede limitar sus capacidades. Algunos sistemas operativos aceptan ciertas aplicaciones y otros no, algunas culturas aceptan ciertos comportamientos mientras que otras los reprimen.

Con algunas dificultades de por medio uno puede instalar un nuevo sistema operativo en cualquier computadora... No hay razón para ser la víctima de una cultura.

**Ejemplos de Sistemas Operativos**

- Consumismo capitalista
- Cristianismo
- Patriotismo
- Naturalismo
- Política
- Especismo
- Vegetarianismo

**En lenguaje de programación**

```PHP
interface Culture
{
  public function getValues(): array;
  public function getHabits(): array;
}

interface Individual
{
  public function __construct(Culture $culture): void;
  public function __destruct(): void;
}

ConsumerCapitalism implements Culture
{
  public function getValues(): array
  {
    return [
      'social status',
      'stereotypes',
      'work',
      'money',
    ];
  }

  public function getHabits(): array
  {
    return [
      'waste environment',
      'waste human resources',
    ];
  }
}

```

> El sistema operativo MUNDO montado en el kernel NATURALEZA se ejecuta en la infinita computadora UNIVERSO.

### Referencias

[Culture is your operation system](https://www.youtube.com/watch?v=9c8an2XZ3MU) - Terence Mckenna
