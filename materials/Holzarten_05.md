<!--

author:   Hilke Domsch, Volker Göhler

email:    hilke.domsch@gkz-ev.de

version:  0.0.5

language: de

narrator: Deutsch Male

edit: true
date: 2025-07-31

comment:  Holzarten und die üblichen Kürzel
title: Holzarten V

tags:    Tischler,
         Holzarten

logo: ../assets/img/oakwoodbig.jpg
icon: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/LiaScript-Courses/refs/heads/main/img/Logo_234px.png


import: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/LiaScript_DragAndDrop_Template/refs/heads/main/README.md
import: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Piktogramme/refs/heads/main/makros.md
import: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/LiaScript_ImageQuiz/refs/heads/main/README.md
import: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Holzarten/refs/heads/main/makros.md

@style
.flex-container {
    display: flex;
    flex-wrap: wrap; /* Allows the items to wrap as needed */
    align-items: stretch;
    gap: 20px; /* Adds both horizontal and vertical spacing between items */
}

.flex-child {
    flex: 1;
    margin-right: 20px; /* Adds space between the columns */
}

@media (max-width: 600px) {
    .flex-child {
        flex: 100%; /* Makes the child divs take up the full width on slim devices */
        margin-right: 0; /* Removes the right margin */
    }
}

.image-container {
  width: 200px;
  height: 200px;
  border: 1px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  background-color: #f8f8f8;
}

.image-container img {
  width: fit-content;
  height: fit-content;
  object-fit: cover;
  display: block;
}

.choice-selected {
    padding: 10px !important;
    border-radius: 4px !important;
    border: 2px solid rgb(var(--color-highlight));
}

.choices-container img {
    padding: 5px;
    height: auto;
    border-radius: 4px;
    margin: 0 auto;
    user-select: none;
    cursor: pointer;
}

@end

-->

# Holzarten: Eigenschaften, Verwendung und Aussehen II

![Holzfußboden](https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/LiaScript-Courses/refs/heads/main/courses/img/oakwoodbig.jpg)<!-- style="width: 800px" -->

_Quelle: Pixabay, Pexels_

## Fichte

_Quelle aller Holz-Abbildungen:_ _https://holz-werken.com/holz-datenbank/ bzw. HWK Dresden, Florian Riefling_

----------------

<!--style="color:green; font-size: large; font-weight: bolder"-->Fichte (FI / PCAB)

<section class="flex-container" style="padding: 1rem;">
<div class="flex-child" style="min-width:200px;">
<!--style="color:green; font-size: large; font-weight: bolder"-->Eigenschaften:

* angenehmer, harziger Geruch
* widerstandsfähig
* sehr harzhaltig
* offenporig
* lässt sich sauber bearbeiten
* gehobelte Fläche hat einen schönen Seidenglanz
* hell-gelb, bräunlich, rötlich

</div>
<div class="flex-child">
<!--style="color:green; font-size: large; font-weight: bolder"-->Verwendung:

* Bau- und Fensterholz
* Wand- und Deckenverkleidung
* Innenausbau

</div>
</section>

-------------------

Klicken Sie auf das richtige Holzarten-Bild.
===



@selectimages(@uid,10, @Hoelzer1.Fichte.src, @Hoelzer1.Kiefer.src|@Hoelzer1.Laerche.src|@Hoelzer1.Robinie.src)




## Lärche

_Quelle aller Holz-Abbildungen:_ _https://holz-werken.com/holz-datenbank/ bzw. HWK Dresden, Florian Riefling_

----------------

<!--style="color:green; font-size: large; font-weight: bolder"-->Lärche (LA / LADC)

<section class="flex-container" style="padding: 1rem;">
<div class="flex-child" style="min-width:200px;">
<!--style="color:green; font-size: large; font-weight: bolder"-->Eigenschaften:

* weich harzhaltig - dadurch widerstandsfähiger gegen Pilzbefall
* Jahresringe sind deutlich sichtbar
* sehr feinporig
* im Splint gelblich-weiß, im Kern rotbraun

</div>
<div class="flex-child">
<!--style="color:green; font-size: large; font-weight: bolder"-->Verwendung:

* Innenausbau
* Fassadenschalung


</div>
</section>

-------------------

Klicken Sie auf das richtige Holzarten-Bild.
===



@selectimages(@uid,10, @Hoelzer1.Laerche.src, @Hoelzer2.Eiche.src|@Hoelzer1.Robinie.src|@Hoelzer1.Fichte.src)



## Robinie

_Quelle aller Holz-Abbildungen:_ _https://holz-werken.com/holz-datenbank/ bzw. HWK Dresden, Florian Riefling_

----------------

<!--style="color:green; font-size: large; font-weight: bolder"-->Robinie (ROB / ROPS)

<section class="flex-container" style="padding: 1rem;">
<div class="flex-child" style="min-width:200px;">
<!--style="color:green; font-size: large; font-weight: bolder"-->Eigenschaften:

* sehr feine Markstrahlen
* groß-ringporig
* hart
* heller, schmaler Splint
* nachdunkelnder Kern zwischen gelb-grün und goldbraun

</div>
<div class="flex-child">
<!--style="color:green; font-size: large; font-weight: bolder"-->Verwendung:

* Spielplätze
* Gartenmöbel
* Rahmenbau (Fenster, Türen, Wintergarten)
* dekorative Möbeloberflächen, Treppen, Fußböden

</div>
</section>

-------------------

Klicken Sie auf das richtige Holzarten-Bild.
===



@selectimages(@uid,10, @Hoelzer1.Robinie.src, @Hoelzer1.Esche.src|@Hoelzer2.Vogelaugenahorn.src|@Hoelzer1.Laerche.src)


## Linde

_Quelle aller Holz-Abbildungen:_ _https://holz-werken.com/holz-datenbank/ bzw. HWK Dresden, Florian Riefling_

----------------

><!--style="color:red"-->_Florian: Laut einer DIN-Liste + holzvomfach.de lautet für Linde das EU-Kürzel TIXX - bei dir steht TILI. Bitte klären._

<!--style="color:green; font-size: large; font-weight: bolder"-->Linde (LI / TIXX)

<section class="flex-container" style="padding: 1rem;">
<div class="flex-child" style="min-width:200px;">
<!--style="color:green; font-size: large; font-weight: bolder"-->Eigenschaften:

* fein- bzw. zertreutporig
* feine Textur, unauffällige Maserung
* trockenes Holz
* weißlich-gelbliche Farbe, bisweilen auch etwas rötlich oder hellbraun

</div>
<div class="flex-child">
<!--style="color:green; font-size: large; font-weight: bolder"-->Verwendung:

* Bildhauerei
* Schnitzholz
* Drechselarbeiten
* Möbel, Spielzeuge, dekorative Furniere und Sperrholz
* Lamellen für Jalousien

</div>
</section>

-------------------

Klicken Sie auf das richtige Holzarten-Bild.
===



@selectimages(@uid,10, @Hoelzer1.Linde.src,@Hoelzer2.Nussbaum.src|@Hoelzer2.Zebrano.src|@Hoelzer2.Mooreiche.src)


## Birke

_Quelle aller Holz-Abbildungen:_ _https://holz-werken.com/holz-datenbank/ bzw. HWK Dresden, Florian Riefling_

----------------

><!--style="color:red"-->_Florian: Laut einer DIN-Liste + holzvomfach.de gibt es für Birke zwei EU-Kürzel: BEPU und BTXX. Ich habe nicht rausbekommen, welche die richtige ist. holzvomfach nutzt BTXX. Bitte klären._

<!--style="color:green; font-size: large; font-weight: bolder"-->Birke (BI / BEPU)


<section class="flex-container" style="padding: 1rem;">
<div class="flex-child" style="min-width:200px;">
<!--style="color:green; font-size: large; font-weight: bolder"-->Eigenschaften:

* sehr feinporig, zerstreut angeordnet
* mittelschweres Holz, zäh, elastisch
* gut form- und bearbeitbar
* farblich variabel von gelblich bis rötlich-weiß

</div>
<div class="flex-child">
<!--style="color:green; font-size: large; font-weight: bolder"-->Verwendung:

* Innenbereich für Möbel und Furnier
* Sperrholz
* Lebensmittelindustrie (Spatel, Küchengeräte, Löffel, Streichhölzer)
* Parkett

</div>
</section>


-------------------

Klicken Sie auf das richtige Holzarten-Bild.
===


@selectimages(@uid,10, @Hoelzer1.Birke.src, @Hoelzer2.Vogelaugenahorn.src|@Hoelzer2.Nussbaum.src|@Hoelzer2.Kirsche.src)

## Esche

_Quelle aller Holz-Abbildungen:_ _https://holz-werken.com/holz-datenbank/ bzw. HWK Dresden, Florian Riefling_

----------------


<!--style="color:green; font-size: large; font-weight: bolder"-->Esche (ES / FXEX)


<section class="flex-container" style="padding: 1rem;">
<div class="flex-child" style="min-width:200px;">
<!--style="color:green; font-size: large; font-weight: bolder"-->Eigenschaften:

* besonders hart
* groß-ringporig, strukturreich
* schmale Markstrahlen
* sehr elastisches Holz
* farblich variabel von weißlich über oliv bis braun

</div>
<div class="flex-child">
<!--style="color:green; font-size: large; font-weight: bolder"-->Verwendung:

* Möbel
* dekorative Furniere, Fußböden
* Treppen
* Sportgeräte, Werkzeugstiele, Leitern, Bootsriemen, Schlagstöcke (Musik)


</div>
</section>


-------------------

Klicken Sie auf das richtige Holzarten-Bild.
===



@selectimages(@uid,10, @Hoelzer1.Esche.src, @Hoelzer1.Kirschbaum.src|@Hoelzer1.Schwarzerle.src|@Hoelzer1.Birnbaum.src)


## Haben Sie sich die Kürzel je Holzart gemerkt?

Ziehen Sie die richtigen Kürzel zur jeweiligen Holzart in das entsprechende "+"-Feld.
===


<!--style="color:green; font-size: large; font-weight: bolder"-->Lärche-Kürzel deutsch: [->[  (LA) | LE ]]  ${/}$ Lärche-Kürzel EU: [->[  (LADC) | LAUC ]]

---------------

<!--style="color:green; font-size: large; font-weight: bolder"-->Robinie-Kürzel deutsch: [->[  (ROB) | ROE ]]  ${/}$ Robinie-Kürzel EU: [->[  ROBS | (ROPS) ]]

----------------

<!--style="color:green; font-size: large; font-weight: bolder"-->Fichte-Kürzel deutsch: [->[  FE | (FI) ]]  ${/}$ Fichte-Kürzel EU: [->[  PUCT | (PCAB) ]]

--------------

<!--style="color:green; font-size: large; font-weight: bolder"-->Esche-Kürzel deutsch: [->[  (ES) | EE ]]  ${/}$ Esche-Kürzel EU: [->[  (FXEX) | FDEX ]]


-----

<!--style="color:green"-->Gratulation 🎉
===
