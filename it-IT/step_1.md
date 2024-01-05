**Riccio che cammina**: [Guarda dentro](https://scratch.mit.edu/projects/499398615/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499398615/?autostart=false" frameborder="0"></iframe>
</div>

Puoi usare i blocchi `passa al costume`{:class="block3looks"} e `fai passi`{:class="block3motion"} in un ciclo `ripeti`{:class="block3control"} per animare un personaggio in movimento. Cambia il tempo nel blocco `attendi`{:class="block3control"} per cambiare la velocità.

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

**Suggerimento:** Se vuoi utilizzare tutti i costumi di uno sprite, puoi semplicemente utilizzare i `passa al costume seguente`{:class="block3looks"} in un ciclo.

**Suggerimento:** Aumenta il numero di passi in ognuno dei blocchi `fai passi`{:class="block3motion"} per muovere lo sprite più velocemente. Cambia il numero nel ciclo `ripeti`{:class="block3control"} per regolare la distanza.

**Suggerimento:** Per far muovere all'indietro lo sprite con il blocco `fai passi`{:class="block3motion"}, puoi usare numeri negativi, ad esempio, `fai`{:class="block3motion"} `-3` `passi`{: class="block3motion"}. Oppure puoi usare un blocco `punta in direzione`{:class="block3motion"} `-90` blocco per cambiare la direzione dello sprite prima che lo sprite si muova (`-90` punta a sinistra). 

