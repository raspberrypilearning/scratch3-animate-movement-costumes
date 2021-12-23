**Idący jeż**: [Zajrzyj do środka](https://scratch.mit.edu/projects/499398615/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499398615/?autostart=false" frameborder="0"></iframe>
</div>

Możesz użyć bloków `zmień kostium na`{:class="block3looks"} i `przesuń o`{:class="block3motion"} w blokach `powtórz`{:class="block3control"}, aby animować poruszającą się postać. Zmień czas w `czekaj`{:class="block3control"} aby zmienić szybkość.

```blocks3
when flag clicked // switch between two costumes
repeat [20]
switch costume to [hedgehog-a v]
move [3] steps
wait [0.1] seconds
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] seconds
end
```

**Wskazówka:** Jeśli chcesz użyć wszystkich kostiumów, które ma duszek, możesz po prostu użyć `następny kostium`{:class="block3looks"} w pętli.

**Wskazówka:** Zwiększ liczbę kroków w każdym bloku `przesuń`{:class="block3motion"}, aby duszek poruszał się szybciej. Zmień liczbę w `powtórz`{:class="block3control"}, aby dostosować odległość.

**Wskazówka:** Aby duszek `przesunął się`{:class="block3motion"} do tyłu, możesz użyć liczb ujemnych, na przykład `przesuń o`{:class="block3motion"} `-3` `kroki`{: class="block3motion"}. Możesz też użyć `ustaw kierunek na`{:class="block3motion"} `-90`, aby zmienić kierunek duszka, zanim duszek się poruszy (`-90` kieruje w lewo). 

