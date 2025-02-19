### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Big Band Jazz (Debug)

## Step 1
هناك خطأ في الكود أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتكتشف ما هو الخطأ وما التعديلات اللازمة لجعله يعمل بشكل صحيح.

#### ~ tutorialhint  
قم بسحب ``||agent:وكيل ينقل||`` إلى ``||blocks:عند البدء||``لإعطاء تعليمات لروبوت حول كيفية الحركة. احسب
المسافة والاتجاه الذي يحتاج الروبوت الحركة فيهما واستخدم بلوك حركة الروبوت (أعلى، أسفل، يسار، يمين) والمسافة اللازمة للوصول إلى البوق. في نهاية الكود، استخدم
 ``||agent:وكيل يجمع الكل||`` للحصول على البوق.
```ghost
    agent.move(FORWARD, 0)
    agent.collectAll()
```
```template
agent.move(FORWARD, 2)
agent.move(UP, 1)
agent.move(FORWARD, 2)
agent.move(DOWN, 3)
agent.move(FORWARD, 2)
agent.move(UP, 2)
agent.move(FORWARD, 1)
agent.collectAll()
```
```package
```
