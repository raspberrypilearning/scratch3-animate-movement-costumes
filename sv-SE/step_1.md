**Gående igelkott**: [Se inuti](https://scratch.mit.edu/projects/827020326/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/827020326/?autostart=false" frameborder="0"></iframe>
</div>

Du kan använda `växla klädsel till`{:class="block3looks"} och `gå`{:class="block3motion"} block i en `repetera`{:class="block3control"} loop för att animera en rörlig karaktär. Ändra tiden i blocket `vänta`{:class="block3control"} för att ändra hastigheten.

```blocks3
when flag clicked // växla mellan två klädslar
repeat [20]
switch costume to [hedgehog-a v]
move [3] steps
wait [0.1] seconds
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] seconds
end
```

**Tips:** Om du vill använda alla klädslar som en sprajt har, kan du bara använda `nästa klädsel`{:class="block3looks"} blocket i en loop.

**Tips:** Öka antalet steg i varje `gå`{:class="block3motion"}-block för att få sprajten att gå snabbare. Ändra siffran i `repetera`{:class="block3control"}-loopen för att justera avståndet.

**Tips:** För att få sprajten `gå`{:class="block3motion"} bakåt kan du använda negativa tal, till exempel `gå`{:class="block3motion"} `-3` `steg`{:class="block3motion"}. Eller så kan du använda ett `-peka riktning`{:class="block3motion"} `-90` block för att ändra sprajtens riktning innan sprajten rör sig (`-90` punkter till vänster).
