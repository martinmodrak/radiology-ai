---
title: "Část 2 - Hrajeme si s čísly"
output: 
  html_document:
    number_sections: true
---


# Seznamte se

Použijeme velmi populární dataset MNIST [ukázka 1](https://en.wikipedia.org/wiki/MNIST_database#/media/File:MNIST_dataset_example.png),
[ukázka 2](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png).

Dále využijeme online aplikaci, kde můžete nakreslit číslo a nechat si ho zklasifikovat modelem natrénovanám na MNIST:
https://zackakil.github.io/mnist-draw/


# Kdy to funguje hezky

Vyzkoušejte nakreslit pár dobře rozpoznatelných čísel (2, 3, 8). Kreslete co nejčitelněji a tak, aby číslice zabírala celý rámeček.
Zkuste  číslo rozdělit na více tahů a sledujte, jak se klasifikace vyvíjí během kreslení. 


# Jedničky

Vymyslete, jak spolehlivě nakreslit číslo, které pro vás vypadá jako "1", zabírá celý rámeček ale je klasifikováno jako nějaké úplně jiné. 

Podívejte se na ukázky z trénovacích dat (link výše), dokážete vysvětlit, proč dochází k omylu?

  <!-- Notes: česká jednička není moc v trénovacích datech, často klasifikuje jako 7, zvlášť, když je trochu našikmo -->

# Malá čísla 

Nakreslete nějaké z čísel, které model dobře rozpoznává, ale menší, umístěné do rohu rámečku. Co se stane? Napadá vás proč?


# Není to číslo

Nakreslete písmeno nebo náhodný klikihák. Co se stane?

Najděte písmeno/klikihák, které je spolehlivě a s velkou jistotou klasifikováno jako nějaké číslo
 <!-- Hodně svislých čar se často ukáže jako 4 -->


# Bonus: Tvorba trénovacích dat

Viděli jsme, co se model může (NE)naučit z trénovacích dat. Jak ale trénovací data vznikají?
Vyzkoušíme si na příkladu z biologie a pomůžeme vědě! 

Zooniverse je projekt, kde široká veřejnost může pomoci s trénováním modelů pro analýzu vědeckých obrázků (i jiných dat),
zkuste si zaklasifkovat pár mitochondrií na

https://www.zooniverse.org/projects/h-spiers/etch-a-cell-immunoexplorers/classify/workflow/29977
