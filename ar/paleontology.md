### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Paleontology Puzzle

## Step 1
تمت إزالة بعض العظام من هيكل الديناصور واستبدالها. قم ببرمجة الروبوت لتدمير البلوكات الأربعة البرتقالية ووضع `Bone Block` التي قدمناها له.
#### ~ tutorialhint  
استخدم ``||agent.agent move||`` لتحريك الروبوت، ثم استخدم  ``||agent.agent destroy||`` في الاتجاه الذي ترغب في تدمير البلوكات البرتقالية فيه، ثم استخدم  ``||agent.agent place||`` لوضع`Bone Block` التي قدمناها للروبوت. كرر هذه العملية حتى يتم وضع العدد المطلوب من البلوكات.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
