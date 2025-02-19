### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Human's Best Friends

## Step 1
لقد كانت الكلاب صديقة للناس لآلاف السنين. ولكن، هناك شيء ما أخاف الكلاب. قم ببرمجة الروبوت لإسقاط `Beetroot` التي قدمناها له على بعد 5 بلوكات لمساعدة الناس في ترويض الذئاب وتحويلها إلى كلاب.
#### ~ tutorialhint 
قم بتحريك الروبوت إلى المكان المناسب باستخدام الأزرار ``||agent.agent move||``و ``||agent.agent turn||``.وعند الوصول إلى النقطة الصحيحة، استخدم الزر   ``||agent.agent drop||`` لإسقاط `Beetroot` الذي قدمناه للروبوت. كرر هذه العملية حتى يتم وضع العدد المطلوب من`Beetroot`  على بعد 5 بلوكات.

```ghost
    agent.move(FORWARD, 0)
    agent.drop(FORWARD, 0, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
