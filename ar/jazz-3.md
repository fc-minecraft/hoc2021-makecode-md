### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Big Band Jazz (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.

#### ~ tutorialhint  
قم بسحب ``||agent:وكيل ينقل||`` إلى ``||blocks:عند البدء||`` لإعطاء تعليمات لروبوت حول كيفية الحركة. احسب
المسافة والاتجاه الذي يحتاج الروبوت الحركة فيهما واستخدم بلوك حركة الروبوت (أعلى، أسفل، يسار، يمين) والمسافة اللازمة للوصول إلى البوق. في نهاية الكود، استخدم ``||agent:وكيل يجمع الكل||`` للحصول على البوق.
```ghost
    agent.move(FORWARD, 0)
    agent.collectAll()
```
```template
agent.move(FORWARD, 3)
agent.move(UP, 1)
agent.move(FORWARD, 2)
agent.move(DOWN, 2)
agent.move(FORWARD, 2)
agent.move(UP, 2)
agent.move(FORWARD, 1)
agent.collectAll()

```
 
