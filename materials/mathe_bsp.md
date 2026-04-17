<!--
author:   Volker Göhler

language: de

email:    volker.goehler@informatik.tu-freiberg.de

version: 0.1.5

narrator: German Female

edit: true
date: 2025-05-10

logo: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/LiaScript-Courses/refs/heads/main/img/Logo_234px.png

comment:  this short course explains math mode in liascript (in german)

import: https://raw.githubusercontent.com/liaTemplates/algebrite/master/README.md

title: Mathematik mit LaTeX in LiaScript

tags:  Wissensspeicher
-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/vgoehler/DiAgnostiK_LiaScript/master/mathe_bsp.md)

# Einführung in LaTeX-Mathematik mit LiaScript

Dieses Modul zeigt dir, wie du mathematische Ausdrücke in **[LiaScript](https://liascript.github.io)** mit LaTeX-Matheausdrücken schreibst.

> ℹ️ LiaScript basiert auf Markdown, unterstützt aber nur **`$...$`** zur Darstellung mathematischer Formeln.

Wir erklären erst die Matheanzeige und dann Quizes mit Algebrite. Damit kann LiaScript rechnen!

---

                        --{{0}}--

## Inline-Mathematik

Formeln im Fließtext setzt du mit einem Dollarzeichen `$...$`.

```
Die berühmte Formel: $E = mc^2$
```

> Die berühmte Formel: $E = mc^2$

Multiline-Mathematik
====================

Mit `$$` lässt sich eine Mathe Umgebung über mehrere Zeilen etablieren.

```
  $$
  \int_a^b f(x)\,dx
  $$

```

> $$
  \int_a^b f(x)\,dx
  $$


## Häufige mathematische Ausdrücke

| Eingabe               | Bedeutung                         |
| --------------------- | --------------------------------- |
| `$x^2$`               | Hochzahl: $x^2$  |
| `$a_1$`               | Tiefstellung: $ a_1 $           |
| `$\frac{a}{b}$`       | Bruch: $ \frac{a}{b} $          |
| `$\sqrt{x}$`          | Wurzel: $ \sqrt{x} $            |
| `$\sum_{i=1}^n i$`    | Summe: $ \sum_{i=1}^n i $       |
| `$\int_a^b f(x)\,dx$` | Integral: $ \int_a^b f(x)\,dx $ |
| `$\alpha \beta \gamma \delta \theta$`| Symbole: $\alpha \beta \gamma \delta \theta$ |
| `$\Alpha \Beta \Gamma \Delta \Theta$`| Symbole: $\Alpha \Beta \Gamma \Delta \Theta$ |

---

Beispielblock
====

```
$$
\sum_{i=1}^n i = \frac{n(n+1)}{2}
$$
```

> $$
 \sum_{i=1}^n i = \frac{n(n+1)}{2}
$$

---

## Testumgebung für LaTeX Mathemodus

Wenn du außerhalb von LiaScript mit LaTeX Mathemodus experimentieren möchtest, nutze:

🔗 [https://latexeditor.lagrida.com](https://latexeditor.lagrida.com)

→ Interaktiver Online-Editor mit Live-Vorschau und PDF-Export.

---

## Testquiz

Frage 1
============

Was ist die Lösung von $x = 2+3$ (Leerzeile ist hiernach wichtig!)

[[5]]
[[?]] größer als 4
[[?]] kleiner als 6

Frage 2
============

> Lösungen werden mit 2 Linien definiert ***


Was ergibt $x = \sum_{i=1}^4 i$?

- [( )] 10.5
- [(x)] 10
- [( )] 15
*****
Lösung:

x = 1+2+3+4

*****

Frage 3: Flächeninhalt eines Kreises
=================

Gegeben: Ein Kreis mit dem Radius $r = 5$.
Berechne den Flächeninhalt $A$ auf zwei Dezimalstellen.

[[78,54]]
[[?]]$A=\pi \cdot r^2$
****
$$
A = \pi \cdot r^2 = \pi \cdot 5^2 = \pi \cdot 25 = 25\pi \approx 78{,}54
$$
****

---

Frage 4: Quadratische Gleichung
============

Gegeben: $x^2 - 5x + 6 = 0$
Finde die Nullstellen mit der Mitternachtsformel:

$x_1=$

[[2]]

$x_2=$

[[3]]
*****
$$
x = \frac{-(-5) \pm \sqrt{(-5)^2 - 4 \cdot 1 \cdot 6}}{2 \cdot 1} \\
= \frac{5 \pm \sqrt{25 - 24}}{2} \\
= \frac{5 \pm \sqrt{1}}{2}
$$

$$
x_1 = \frac{5 - 1}{2} = 2, \quad x_2 = \frac{5 + 1}{2} = 3
$$
*****

---

Frage 5: Löse die Gleichung $x^2 = x + 1$
=====================

Was sind die Lösungen?

- [[x]] $x_i = \frac{1 - \sqrt{5}}{2}$
- [[x]] $x_j = \frac{1 + \sqrt{5}}{2}$
- [[ ]] $x_k = 2$
- [[ ]] $x_l = 3$
***
Lösungsweg:
===========

Bringe die Gleichung zunächst auf die Normalform:

$$
x^2 - x - 1 = 0
$$

Nun wenden wir die **p-q-Formel** an:

$$
x = -\frac{p}{2} \pm \sqrt{\left( \frac{p}{2} \right)^2 - q}
$$

In unserem Fall ist $p = -1$ und $q = -1$:

$$
x = -\frac{-1}{2} \pm \sqrt{\left( \frac{-1}{2} \right)^2 - (-1)} \\
= \frac{1}{2} \pm \sqrt{\frac{1}{4} + 1} \\
= \frac{1}{2} \pm \sqrt{\frac{5}{4}} \\
= \frac{1}{2} \pm \frac{\sqrt{5}}{2}
$$

**Lösungen:**

$$
x_1 = \frac{1 - \sqrt{5}}{2}, \quad x_2 = \frac{1 + \sqrt{5}}{2}
$$

Die Lösung $x_2$ ist übrigens der berühmte **Goldene Schnitt**.
***

---



Frage 6: Mathe-Quiz
=================

Was ist $6 + 6$?

```
[[12]]
@Algebrite.check(12)
```

[[12]]
@Algebrite.check(12)

Frage 7: Komplexer
==================

Parabel -1?

```
[[x ^ 2 - 1]]
@Algebrite.check(x^2-1)
```

[[x ^ 2 - 1]]
@Algebrite.check(x^2-1)

Frage 8: Runden
==========================

$1/3$ ?

```
[[1/3]]
@Algebrite.check2(1/3,0.01)
```

[[1/3]]
@Algebrite.check2(1/3,0.01)
