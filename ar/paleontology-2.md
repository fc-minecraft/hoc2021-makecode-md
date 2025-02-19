### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Paleontology Puzzle (Debug)

## Step 1
هناك خطأ في الكود أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتكتشف ما هو الخطأ وما التعديلات اللازمة لجعله يعمل بشكل صحيح.
#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` لتحريك الروبوت، ثم استخدم ``||agent:وكيل يدمر||``ي الاتجاه الذي ترغب في تدمير البلوكات البرتقالية فيه، ثم استخدم ``||agent:وكيل يضع||`` لوضع `Bone Block` التي قدمناها للروبوت. كرر هذه العملية حتى يتم وضع العدد المطلوب من البلوكات.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 2)    
    agent.destroy(DOWN)
    agent.place(UP)
}
```
```package
```
