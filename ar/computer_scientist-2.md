### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Computer Scientist (Debug)

## Step 1
هناك خطأ في الكود أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتكتشف ما هو الخطأ وما التعديلات اللازمة لجعله يعمل بشكل صحيح.

#### ~ tutorialhint 
استخدم ``||agent.agent move||`` و ``||agent.agent turn||`` قم بتحريك الروبوت نحو كل بلوك باللون البني. ثم استخدم ``||agent.agent destroy||`` في الاتجاه الذي ترغب في تدمير البلوك فيه، قم بإزالة البلوك باللون بالبني. كرر هذه العملية حتى يتم تدمير جميع البلوكات البنية.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.move(FORWARD, 1)
agent.destroy(UP)
agent.move(FORWARD, 2)
agent.destroy(UP)
agent.move(FORWARD, 2)
agent.destroy(UP)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.destroy(UP)
agent.move(FORWARD, 2)
agent.destroy(UP)
agent.move(FORWARD, 2)
agent.destroy(UP)
```
```package
```
