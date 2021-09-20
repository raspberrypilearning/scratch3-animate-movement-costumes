**Ouriço caminhando**: [Ver interior](https://scratch.mit.edu/projects/572543578/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/572543578/?autostart=false" frameborder="0"></iframe>
</div>

Você pode usar `Alternar fantasia para`{:class="block3looks"} e `mover blocos`{:class="block3motion"} em um `repetir loop`{:class="block3control"} para animar o movimento do personagem. Mude o tempo no `Bloco esperar`{:class="block3control"} para mudar a velocidade.



```blocks3
when flag clicked // Alterne entre duas fantasias
repeat [20]
switch costume to [hedgehog-a v]
move [3] steps
wait [0.1] seconds
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] seconds
end
```


**Dica:** Se você quer usar todas as fantasias que o ator tem, você pode usar o bloco `próxima fantasia`{:class="block3looks"} em um loop.

**Dica:** Aumente o número de passos em cada bloco `mover`{:class="block3motion"} para fazer o ator ir mais rápido. Mude o número de loop no `Repetir`{:class="block3control"} para ajustar a distância.

**Dica:** Para fazer o ator mover para trás `mover`{:class="block3motion"}, você pode usar números negativos, por exemplo, `mover`{:class="block3motion"} `-3` `passos`{:class="block3motion"}. Ou, você pode usar o bloco `ponto na direção`{:class="block3motion"} `-90` para mudar a direção do sprite antes que ele se mova (`-90` pontos à esquerdat).
