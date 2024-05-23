**Ouriço caminhando**: [Ver interior](https://scratch.mit.edu/projects/572543578/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/572543578/?autostart=false" frameborder="0"></iframe>
</div>

Você pode usar os blocos `mude para a fantasia`{:class="block3looks"} e `mova`{:class="block3motion"} em um laço `repita`{:class="block3control"} para animar o movimento do personagem. Altere o tempo no bloco `espere`{:class="block3control"} para mudar a velocidade.

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

**Dica:** Se você quer usar todas as fantasias que o ator possui, você pode usar o bloco `próxima fantasia`{:class="block3looks"} em um laço.

**Dica:** Aumente o número de passos em cada bloco `mova`{:class="block3motion"} para fazer o ator ir mais rápido. Altere o número no laço `repita`{:class="block3control"} para ajustar a distância.

**Dica:** Para fazer com que o ator se `mova`{:class="block3motion"} para trás, você pode usar números negativos, por exemplo, `mova`{:class="block3motion"} `-3` `passos`{:class="block3motion"}. Ou, você pode usar o bloco `aponte para a direção`{:class="block3motion"} `-90` para mudar a direção do ator antes que ele se mova (`-90` aponta para à esquerda). 
