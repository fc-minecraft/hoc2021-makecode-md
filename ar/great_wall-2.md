### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Great Wall of China (Debug)

## Step 1
هناك خطأ في الكود أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتكتشف ما هو الخطأ وما التعديلات اللازمة لجعله يعمل بشكل صحيح.

#### ~ tutorialhint  
استخدم الـ ``||agent:وكيل ينقل||``  لتحديد موقع الروبوت و ``||agent:وكيل يضع||`` لوضع الـ `الخيزران` الذي قدمناه للروبوت

```ghost
    agent.place(FORWARD)
    agent.move(FORWARD, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 3; index++) {
    agent.place(UP)
    agent.move(BACK, 1)
}
```
```package
```
