### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Great Pyramid at Giza (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.

#### ~ tutorialhint  
فكر في كيفية تحرك الروبوت لوضع العدد المناسب من البلوكات لكل مستوى من مستويات الهرم. استخدم الـ ``||agent:وكيل ينقل||`` استخدم البلوك لتحريك الروبوت للأمام، واستخدمها في كل خطوة. ``||agent:وكيل يضع||``  لوضع الـ `الحجر الرملي الأملس` الذي قدمناه للروبوت.

```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index=0); index < 3; index++){
agent.move(FORWARD, 1)
agent.place(BACK)
}
agent.move(UP, 1)
agent.turn(LEFT_TURN)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 1)
agent.move(FORWARD, 1)
agent.move(FORWARD, 1)
agent.place(BACK)
```
 
