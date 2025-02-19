### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Elements of Discovery (Debug)

## Step 1
هناك خطأ في الكود أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتكتشف ما هو الخطأ وما التعديلات اللازمة لجعله يعمل بشكل صحيح.

#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` و ``||agent:وكيل يحول||`` قم بتحريك الروبوت نحو الرفوف المتوهجة باللون الأخضر. استخدم ``||agent:وكيل يدمر||`` في الاتجاه الذي ترغب في تدمير خزائن الكتب المتوهجة باللون الأخضر، كرر هذه العملية حتى يتم تدمير ثلاث خزائن كتب.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.move(UP, 2)
agent.move(FORWARD, 3)
agent.destroy(LEFT)
```
```package
```
