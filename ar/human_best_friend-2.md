### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Human's Best Friends (Debug)

## Step 1
هناك خطأ في الكود أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتكتشف ما هو الخطأ وما التعديلات اللازمة لجعله يعمل بشكل صحيح.
#### ~ tutorialhint  
قم بتحريك الروبوت إلى المكان المناسب باستخدام الأزرار ``||agent:وكيل ينقل||`` و ``||agent:وكيل يحول||``. وعند الوصول إلى النقطة الصحيحة، استخدم الزر``||agent:وكيل يسقط||`` لإسقاط  `الشمندر` الذي قدمناه للروبوت. كرر هذه العملية حتى يتم وضع العدد المطلوب من `الشمندر` على بعد 5 بلوكات.

```ghost
    agent.move(FORWARD, 0)
    agent.drop(FORWARD, 0, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 5; index++) {
    agent.drop(FORWARD, 1, 1)
    agent.move(FORWARD, 1)
}
```
```package
```
