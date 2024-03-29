**हेजहॉग चलाना**: [अंदर देखें](https://scratch.mit.edu/projects/660127633/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/660127633/?autostart=false" frameborder="0"></iframe>
</div>

आप `switch costume to`{:class="block3looks"} और `move`{:class="block3motion"} खंडों को एक `repeat`{:class="block3control"} लूप में उपयोग करके एक चरित्र को एनिमेट कर सकते हैं। गति बदलने के लिए `wait`{:class="block3control"} ब्लॉक में समय बदलें।

```blocks3
when flag clicked // पोषक बदले
repeat [20]
switch costume to [hedgehog-a v]
move [3] steps
wait [0.1] seconds
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] seconds
end
```

**सुझाव:** यदि आप एक स्प्राइट के सभी परिधानों का उपयोग करना चाहते हैं, तो आप `next costume`{:class="block3looks"} खंड का उपयोग कर सकते हैं।

**सुझाव:** हर `move`{:class="block3motion"} खंड में कदमों की गिनती बढ़ाये ताकि आपकी स्प्राइट और तेज़ी से आगे बड़े। दूरी बदलने के लिए `repeat`{:class="block3control"} लूप में संख्या बदलें।

**सुझाव:** एक स्प्राइट को पीछे `चलाने (move)`{:class="block3motion"} के लिए, आप ऋणात्मक संख्या का उपयोग कर सकते हैं, उद्धरण के लिए, `move`{:class="block3motion"} `-3` `steps`{:class="block3motion"}. या, आप स्प्राइट की दिशा बदलने के लिए एक `point in direction`{:class="block3motion"} `-90` डिग्री खंड का उपयोग कर सकते स्प्राइट के दूसरी ओर मुड़ने के पहले (`-90` डिग्री का मतलब हैं बाईं ओर)।

