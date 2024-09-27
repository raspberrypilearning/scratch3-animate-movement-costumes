**ハリネズミの歩み**: [中を見る](https://scratch.mit.edu/projects/591164798/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/591164798/?autostart=false" frameborder="0"></iframe>
</div>

`繰り返す`{:class="block3control"}ループの中で`コスチュームを～にする`{:class="block3looks"}と`動かす`{:class="block3motion"}ブロックを使って動くキャラクターをアニメ化できます。 `待つ`{:class="block3control"}ブロック内の時間を変更すると速さが変わります。

```blocks3
when flag clicked // 2つのコスチュームを切り替える
repeat [20]
switch costume to [hedgehog-a v]
move [3] steps
wait [0.1] seconds
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] seconds
end
```

**ヒント:** スプライトの全てのコスチュームを使いたいならば、単に`次のコスチューム`{:class="block3looks"}ブロックをループの中で使うことができます。

**ヒント:** `動かす`{:class="block3motion"}ブロックの歩数を増やすとスプライトが速く動きます。 `繰り返す`{:class="block3control"}ループの数字を変えて距離を調整します。

**ヒント:** スプライトを後退させるために`動かす`{:class="block3motion"}で負の数が使えます。例えば、`-3``歩`{:class="block3motion"}`動かす`{:class="block3motion"}。 あるいは、スプライトを動かす前に、`-90``度に向ける`{:class="block3motion"}ブロックを使ってスプライトの向きを変えます（`-90`度で左）。

