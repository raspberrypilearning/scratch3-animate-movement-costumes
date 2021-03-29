**Hedgehog walking**: [See inside](https://scratch.mit.edu/projects/499398615/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499398615/?autostart=false" frameborder="0"></iframe>
</div>

You can `switch costumes`{:class="block3looks"} and `move`{:class="block3motion"} in a `repeat`{:class="block3control"} to animate a moving character. Change the `wait`{:class="block3control"} time to change the speed.

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

**Tip:** If you want to use all the costumes that a sprite has, then you can just use `next costume`{:class="block3looks"} in a loop.

**Tip:** Increase the number of steps in each `move`{:class="block3motion"} to go faster. Change the number in the `repeat`{:class="block3control"} block to adjust the distance.

**Tip:** To `move`{:class="block3motion"} backwards, you can use negative numbers, such as `move`{:class="block3motion"} `-3` `steps`{:class="block3motion"}. Or, you can use a `point in direction`{:class="block3motion"} `-90` block to change the sprite's direction before the sprite moves (`-90` points to the left). 

