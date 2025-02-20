### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Human's Best Friends (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.
#### ~ tutorialhint  
قم بتحريك الروبوت إلى المكان المناسب باستخدام الأزرار ``||agent:وكيل ينقل||`` و ``||agent:وكيل يحول||``.وعند الوصول إلى النقطة الصحيحة، استخدم الزر ``||agent:وكيل يسقط||`` لإسقاط `الشمندر` الذي قدمناه للروبوت. كرر هذه العملية حتى يتم وضع العدد المطلوب من `الشمندر` على بعد 5 بلوكات.

```ghost
    agent.move(FORWARD, 0)
    agent.drop(FORWARD, 0, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 6; index++) {
    agent.drop(FORWARD, 1, 1)
    agent.move(FORWARD, 4)
}
```
```package
```
