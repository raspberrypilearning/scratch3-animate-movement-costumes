**Ходьба їжака**: [Переглянути код](https://scratch.mit.edu/projects/751018192/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/751018192/?autostart=false" frameborder="0"></iframe>
</div>

Ти можеш натиснути на блоки `змінити образ на`{:class="block3looks"} та `перемістити на`{:class="block3motion"} в циклі `повтор`{:class="block3control"}, щоб активувати анімацію руху персонажа. Змінюй час у блоці `чекати`{:class="block3control"}, щоб змінити швидкість.

```blocks3
when flag clicked // переключатися між двома образами
repeat [20]
switch costume to [hedgehog-a v]
move [3] steps
wait [0.1] seconds
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] seconds
end
```

**Порада:** щоб використати всі образи, які є у спрайта, можна просто використовувати циклічно блок `наступний образ`{:class="block3looks"}.

**Порада:** збільшуй кількість кроків у кожному блоці `перемістити на`{:class="block3motion"}, щоб спрайт рухався швидше. Змінюй число в циклі `повтор`{:class="block3control"}, щоб регулювати відстань.

**Порада:** щоб змусити спрайт `перемістити на`{:class="block3motion"} назад, можна використовувати негативні числа, наприклад, `перемістити на`{:class="block3motion"} `-3` `кроки(-ів)`{:class="block3motion"}. Або, можна використовувати блок `повернути в напрямку`{:class="block3motion"} `-90`, щоб змінити напрямок руху спрайта до того, як він почне рухатись (`-90` пунктів ліворуч).
