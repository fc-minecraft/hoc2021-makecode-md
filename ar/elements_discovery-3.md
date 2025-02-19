### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Elements of Discovery (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.

#### ~ tutorialhint  
استخدم ``||agent.agent move||`` و ``||agent.agent turn||`` لنقل الروبوت إلى الرفوف المتوهجة باللون الأخضر، استخدم``||agent.agent destroy||`` في الاتجاه الذي ترغب في تدمير خزائن الكتب المتوهجة باللون الأخضر، كرر هذه العملية حتى يتم تدمير ثلاث خزائن كتب.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.move(UP, 1)
agent.move(FORWARD, 4)
agent.destroy(LEFT)
```
```package
```
