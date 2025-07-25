**Laufender Igel**: [Ansehen](https://scratch.mit.edu/projects/499398615/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499398615/?autostart=false" frameborder="0"></iframe>
</div>

Du kannst `wechsle zu Kostüm`{:class="block3looks"} und `gehe`{:class="block3motion"} Schritt verwenden, um eine sich bewegende Figur mithilfe einer `wiederhole`{:class="block3control"}-Schleife zu animieren. Ändere die Zeit im `warte`{:class="block3control"}-Block, um die Geschwindigkeit einzustellen.

```blocks3
when flag clicked // Wechseln zwischen zwei Kostümen
repeat [20]
switch costume to [hedgehog-a v]
move [3] steps
wait [0.1] seconds
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] seconds
end
```

**Tipp:** Sieh dir alle Kostüme für eine Figur an, indem du den Block `nächstes Kostüm`{:class="block3looks"} in einer Schleife verwendest.

**Tipp:** Erhöhe die Anzahl der Schritte in allen `bewege`{:class="block3motion"}-Blöcken, damit sich die Figur schneller bewegt. Erhöhe die Anzahl in der `wiederhole`{:class="block3control"}-Schleife, um die Entfernung anzupassen.

**Tipp:** Damit sich die Figur rückwärts `bewegt`{:class="block3motion"}, verwendest du negative Zahlen, z. B. `bewege`{:class="block3motion"} `-3` `Schritt`{:class="block3motion"}. Außerdem gibt es einen `setze Richtung auf`{:class="block3motion"} `-90` Grad-Block, mit dem du die Richtung der Figur änderst, bevor sie sich zu bewegen beginnt (`-90` Grad nach links). 

