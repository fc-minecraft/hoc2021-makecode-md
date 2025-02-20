### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Computer Scientist

## Step 1
شخص ما قام بملء الطاقات الخاصة بعالمة الحاسوب التي تحتوي على التعليمات لأول خوارزمية بالثقوب . قم ببرمجة الروبوت لتدمير البلوكات البنية لتفعيل البطاقات.
#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` و ``||agent:وكيل يحول||`` لتحريك الروبوت نحو البلوك باللون البني. ثم استخدم ``||agent:وكيل يدمر||`` في الاتجاه الذي تريد تدمير البلوك البني فيه. كرر هذه العملية حتى يتم تدمير جميع البلوكات البنية.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
 
