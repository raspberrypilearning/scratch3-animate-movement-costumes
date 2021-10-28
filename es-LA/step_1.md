**Erizo caminando**: [Ver dentro](https://scratch.mit.edu/projects/499398615/editor){: target = "_ blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499398615/?autostart=false" frameborder="0"></iframe>
</div>

Puedes usar los bloques `cambiar disfraz a`{: class = "block3looks"} y `mover`{: class = "block3motion"} dentro de un bloque `repetir`{: class = "block3control"} para animar un personaje en movimiento. Cambia el tiempo en el bloque `esperar`{: class = "block3control"} para cambiar la velocidad.

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

**Consejo:** Si quieres usar todos los disfraces que tiene un objeto, puedes usar el bloque `siguiente disfraz`{: class = "block3looks"} en un bucle.

**Consejo:** Aumenta el número de pasos en cada `mover`{: class = "block3motion"} para que el objeto vaya más rápido. Cambia el número en el bloque `repetir`{: class = "block3control"} para ajustar la distancia.

**Consejo:** Para que el objeto se`mueva`{: class = "block3motion"} hacia atrás, puedes usar números negativos, por ejemplo `mover`{: class = "block3motion"} `-3` `pasos`{: class = "block3motion "}. O bien, puedes utilizar un bloque `apuntar en dirección`{: class = "block3motion"} `-90` para cambiar la dirección del objeto antes de que se mueva (`-90` apunta hacia la izquierda). 

