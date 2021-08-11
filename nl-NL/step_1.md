**Lopende egel**: [Bekijk van binnen](https://scratch.mit.edu/projects/528197865/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/528197865/?autostart=false" frameborder="0"></iframe>
</div>

Je kunt `verander uiterlijk naar`{:class="block3looks"} en `neem stappen`{:class="block3motion"} blokken in een `herhaal`{:class="block3control"} lus gebruiken om een bewegende sprite te animeren. Verander de tijd in het `wacht`{:class="block3control"} blok om de snelheid te veranderen.

```blocks3
when flag clicked // wissel tussen twee uiterlijken
repeat [20]
switch costume to [hedgehog-a v]
move [3] steps
wait [0.1] seconds
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] seconds
end
```

**Tip:** Als je alle uiterlijken van een sprite wilt gebruiken, kun je gewoon het `volgend uiterlijk`{:class="block3looks"} blok in een herhaal-lus gebruiken.

**Tip:** Verhoog het aantal stappen in elk `beweeg`{:class="block3motion"} blok om de sprite sneller te laten bewegen. Verander het getal in de `herhaal`{:class="block3control"} lus om de afstand aan te passen.

**Tip:** Om een sprite achterwaarts te laten `bewegen`{:class="block3motion"}, kun je negatieve getallen gebruiken, bijvoorbeeld, `neem`{:class="block3motion"} `-3` `stappen`{:class="block3motion"}. Of je kunt een `richt naar`{:class="block3motion"} `-90 graden` blok gebruiken om de richting van de sprite te veranderen voordat de sprite beweegt(`-90` wijst naar links).
