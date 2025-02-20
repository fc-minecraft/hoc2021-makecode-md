### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Great Wall of China (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.

#### ~ tutorialhint  
استخدم بلوك  ``||agent:وكيل ينقل||`` لتحديد موقع الروبوت، وبلوك ``||agent:وكيل يضع||`` لوضع الـ `الخيزران` الذي قدمناه للروبوت.

```ghost
    agent.place(FORWARD)
    agent.move(FORWARD, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 5; index++) {
    agent.place(DOWN)
    agent.move(FORWARD, 1)
}
```
```package
```
