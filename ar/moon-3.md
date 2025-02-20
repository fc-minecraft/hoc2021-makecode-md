### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Mission Moon (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.

#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` و ``||agent:وكيل يحول||`` داخل البلوك ``||blocks:عند البدء||`` لترسل الحسابات إلى وحدة الفضاء. استخدم حسابات الرياضي لمساعدتك في تحديد المسار الذي يجب أن يسلكه الروبوت. تقدم 25 خطوة، ثم اتجه يمينا 17 خطوة، ثم 3 خطوات للأسفل

```ghost
    agent.move(FORWARD, 0)
    agent.turn(RIGHT_TURN)
```
```template
agent.move(FORWARD, 25)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 17)
agent.turn(RIGHT_TURN)
agent.move(DOWN, 3)
```
 
