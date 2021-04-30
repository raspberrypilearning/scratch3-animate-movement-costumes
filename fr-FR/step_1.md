**Hérisson marchant** : [Voir à l'intérieur](https://scratch.mit.edu/projects/523659509/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/523659509/?autostart=false" frameborder="0"></iframe>
</div>

Tu peux utiliser `basculer sur le costume`{:class="block3looks"} et les blocs `mouvement`{:class="block3motion"} dans une boucle `répéter`{:class="block3control"} pour animer un personnage en mouvement. Change le temps dans le bloc `attendre`{:class="block3control"} pour changer la vitesse.

```blocks3
when flag clicked // basculer entre deux costumes
repeat [20]
switch costume to [hedgehog-a v]
move [3] steps
wait [0.1] seconds
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] seconds
end
```

**Astuce :** si tu veux utiliser tous les costumes d'un sprite, tu peux simplement utiliser le bloc `costume suivant`{:class="block3looks"} dans une boucle.

**Astuce :** augmenter le nombre de pas dans chaque bloc `avancer`{:class="block3motion"} pour aller plus vite. Change le nombre dans la boucle `répéter`{:class="block3control"} pour ajuster la distance.

**Astuce :** pour `avancer`{:class="block3motion"} en arrière, tu peux utiliser des nombres négatifs, tels que `avancer de`{:class="block3motion"} `-3` `pas`{:class="block3motion"}. Ou, tu peux utiliser un bloc `s'orienter à`{:class="block3motion"} `-90` pour changer la direction du sprite avant que le sprite ne bouge (`-90` points vers la gauche). 

