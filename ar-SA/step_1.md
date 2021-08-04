**القنفذ يمشي**: [انظر من الداخل](https://scratch.mit.edu/projects/499398615/editor){: target = "_ blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499398615/?autostart=false" frameborder="0"></iframe>
</div>

يمكنك استخدام `زي التحول إلى`{: فئة = "block3looks"} و `الخطوة`{: فئة = "block3motion"} كتل في `تكرار`{: فئة = "block3control"} حلقة لتحريك الشخصية. تغيير الوقت في `الانتظار`{: فئة = "block3control"} كتلة (تعليمة برمجية) لتغيير السرعة.

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

**نصيحة:** إذا كنت تريد استخدام جميع الأزياء التي يمتلكها الكائن ، يمكنك فقط استخدام `المظهر التالي`{: class = "block3looks"} في حلقة التكرار.

**نصيحة:** بزيادة عدد الخطوات في كل `حركة` للكتلة {: class = "block3motion"} لجعل الكائن يتحرك بشكل أسرع. قم بتغيير الرقم في الحلقة `كرر`{: class = "block3control"} لضبط المسافة.

**نصيحة:** لجعل الكائن `يتحرك`{: class = "block3motion"} للخلف ، يمكنك استخدام الأرقام السالبة ، على سبيل المثال ، `حرك`{: class = "block3motion"} `-3` `خطوات`{: class = "block3motion"}. أو يمكنك استخدام كتلة `في الاتجاه`{: class = "block3motion"} `-90` لتغيير اتجاه الكائن قبل أن يتحرك الكائن (`-90` نقاط إلى اليسار). 

