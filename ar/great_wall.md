### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# سور الصين العظيم

## الخطوة 1
تستمر الباندا في أكل السقالات المصنوعة من الخيزران، مما يمنع المهندس من إكمال الجدار. قم بإبعاد الباندا عن الجدار. برمج الروبوت لوضع 5 قطع من "الخيزران" التي قدمناها للروبوت.

#### ~ tutorialhint  
استخدم بلوك ``||agent:وكيل ينقل||`` لتحريك الروبوت و``||agent:وكيل يضع||`` لوضع `الخيزران` الذي قدمناه للروبوت.

```ghost
    agent.place(FORWARD)
    agent.move(FORWARD, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```