### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Elements of Discovery

## Step 1
عندما غادرت الكيميائية الغرفة، قام شخص ما بإخفاء أبحاثها داخل خزانة الكتب. قم ببرمجة الروبوت لتدمير خزانة الكتب المتوهجة باللون الأخضر، حتى تتمكن من مشاركة اكتشافاتها مع العالم.

#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` و ``||agent:وكيل يحول||`` لنقل الروبوت إلى الرفوف المتوهجة باللون الأخضر.  ``||agent:وكيل يدمر||`` في الاتجاه الذي ترغب فيه بتدمير خزائن الكتب المتوهجة باللون الأخضر.

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
```package
```
