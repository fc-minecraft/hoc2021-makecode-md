### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Paleontology Puzzle (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.
#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` تحريك الروبوت، ثم استخدم ``||agent:وكيل يدمر||`` ي الاتجاه الذي ترغب في تدمير البلوكات البرتقالية فيه، ثم استخدم ``||agent:وكيل يضع||`` لوضع `Bone Block` التي قدمناها للروبوت. كرر هذه العملية حتى يتم وضع العدد المطلوب من البلوكات.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 4; index++) {
    agent.move(FORWARD, 2)    
    agent.destroy(DOWN)
    agent.place(DOWN)
}
```
```package
```
