### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Great Wall of China (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.

#### ~ tutorialhint  
استخدم بلوك  ``||agent.agent move||`` لتحديد موقع الروبوت، وبلوك ``||agent.agent place||`` لوضع الـ `Bamboo` الذي قدمناه للروبوت.

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
