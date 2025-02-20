### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Computer Scientist (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.

#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` و ``||agent:وكيل يحول||`` قم بتحريك الروبوت نحو كل بلوك باللون البني. ثم استخدم ``||agent:وكيل يدمر||`` في الاتجاه الذي ترغب في تدمير البلوك فيه، قم بإزالة البلوك باللون البني. كرر هذه العملية حتى يتم تدمير جميع البلوكات البنية.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.move(FORWARD, 1)
agent.destroy(DOWN)
agent.move(FORWARD, 2)
agent.destroy(DOWN)
agent.move(FORWARD, 2)
agent.destroy(DOWN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.turn(RIGHT_TURN)
agent.destroy(DOWN)
agent.move(FORWARD, 2)
agent.destroy(DOWN)
agent.move(FORWARD, 2)
agent.destroy(DOWN)
```
 
